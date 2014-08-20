convers-o-usando-classes
========================

#include<iostream>
using namespace std;

 class a{};

 class b{

 public:
 
    b(const a & x){}

    b& operator = (const a& x)  {return*this;}

    operator a()  {returna();}


 };

 int main()
 

 {
 
     a foo;
     
     b bar = foo;
     
     bar = foo;
     
     foo = bar;
     
     return 0;


 }
