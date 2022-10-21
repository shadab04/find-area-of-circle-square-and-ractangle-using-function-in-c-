# find-area-of-circle-square-and-ractangle-using-function-in-c-
#include<stdio.h>
  float squareArea(float side);
  float circleArea(float rad);
  int ractangleArea(int a, int b);
 int main()
 {

     float r=5,side=4;
     int a=6,b=10;
     printf("\n square area is:%f",squareArea(side));
     printf("\n circle area is:%f",circleArea(r));
     printf("\n rectangle area is:%d",ractangleArea(a,b));
     return 0;
 }
 float squareArea(float side)
 {
     return side*side;
 }
  float circleArea(float r)
{
    return 3.14*r*r;
}
  int ractangleArea(int a,int b)
{
    return a*b;
}
