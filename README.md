# Hello-world
#include <stdio.h>
#ifdef LABEL
    statement 1;
    statement 2;
#endif

int main()
{
  #ifdef PCAT
    code for a PC/AT
  #else
    code for aa PC/XT
  #endif
  code common to both computers
  return 0;
}
