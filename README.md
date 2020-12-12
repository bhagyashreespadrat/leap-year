# leap-year
#leap year
#include <stdio.h>

int main() {
   int year;
   printf("\n enter year:");
   scanf("%d",&year);
   if(year%400==0)
   {
       printf("%d is a leap year\n",year);
   }
   else if(year%100==0)
   {
       printf("%d is not a leap year\n",year);
   }
   else if(year%4==0)
   {
        printf("%d is a leap year\n",year);
   }
   else
   {
        printf("%d is not a leap year\n",year);
   }
}
/*OUTPUT:
enter year:2004
2004 is a leap year

*/
