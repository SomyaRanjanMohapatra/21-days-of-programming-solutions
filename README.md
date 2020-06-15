# 21-days-of-programming-solutions
THIS REPOSITORY CONTAINS SOLUTIONS OF SPESTRUM 21 DAYS CODING EVENT SOLUTIONS
c++ programme for printing the discriminant and roots of the quadraric equation of the form ax*x+bx+c=0
#include <iostream.h>
#include <math.h>
void main()
{
  float a,b,c,d,r1,r2;
  cout<<"enter the value of a,b,c";
  cin>>a>>b>>c;
  d=(b*b)-4*a*c;
  cout<<"the value of discriminant is"<<d
  r1=(-b+sqrt(d))/(2*a);
  r1=(-b-sqrt(d))/(2*a);
  cout<<"the values of root 1 and root 2 are"<<r1<<r2;
  }
