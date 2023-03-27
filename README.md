# Multiplication-Program-using-Inline-Functions-in-C-
Inline Function: It is a function that is expanded in line when it is invoked. That is, the compiler replaces the function call with the corresponding function code.  The inline function is defined as follows  Inline return-type function_ name(arguments) {   function body; }
#include<iostream>
#include<stdio.h>

inline float mul( float a, float b)
{
    return(a*b);
}

inline float div(float a, float b)
{
    return(a/b) ;
}

int main()
{
    float x,y;
    cout<<"enter the value of x:";
    cin>>x;
    cout<<"enter the value of y:";
    cin>>y;
    cout<<mul(x,y)<<"\n";
    cout<<div(x,y)<<"\n";
    return 0;
}
