# Function
learned functions
#include<stdio.h>
int add(int,int);
int sub(int,int);
int main()
{
  int a,b,c,d;
  scanf("%d", &a);
  scanf("%d", &b);
  c=add(a,b);
  d=sub(a,b);
  printf("%d + %d = %d/n",a,b,c);
  printf("%d - %d = %d",a,b,d);
}
int add(int p, int q)
{
    return  (p+q);
}
int sub(int p, int q)
{
    return  (p-q);
}
