- š Hi, Iām @RahulRoy2021
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
RahulRoy2021/RahulRoy2021 is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#include <stdio.h>

void sum(int*,int*);//declaration
void main()
{int x,y;
printf("Enter two numbers");
scanf("%d%d",&x,&y);
sum(&x,&y);//calling funtion
}
void sum(int *a,int *b)//define the function
{int sum=0;
sum=*a+*b;
printf("%d",sum);
}
