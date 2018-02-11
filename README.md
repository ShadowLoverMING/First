# First
first code
- 第一个程序

 `hello world`
- 选择代码
```
/*   求方程的根 */
#include"stdio.h"
#include "math.h"
main( )
{   float a, b, c, d, x1, x2, q,m,n; 
    printf("Please input a, b, c\n"); 
    scanf("%f,%f,%f", &a, &b, &c); 
    d=b*b-4*a*c;
    if(d>=0)      
       {  q=sqrt (d);       /*求实根*/
          x1=(-b+q)/(2*a); 
          x2=(-b-q)/(2*a);
          printf("d=%.2f,x1=%.2f, x2=%.2f \n ",d, x1, x2); 
        }
    else
       { m=-b/(2*a);     /*求实部*/
         n= sqrt(-d)/(2*a);      /*求虚部*/
         printf("d=%.2f,x1=%.2f+%.2fi",d,m,n);
         printf("\t,x2=%.2f-%.2fi",m,n);
       } 
 }
 ```
