# BASICS
## EXPERIMENT 2
## AIM: -
To study and implement C++ Program Structure (Data Types)

## Theory: -

In C++, variables are declared using data type to restrict storage type. The compiler allocates memory based on the data type, which requires different memory allocations. C++ supports various data types, including Character (char), Integer (int), Boolean (bool), Floating point (float), Double Floating point (double), Void (), and Wide Character sizeof() operator. These data types can have modifiers, such as Short Long Signed Unsigned, which can increase or decrease the variable's size. For example, Long can extend an integer to 4 bytes. The storage representation and machine instructions for each data type differ from machine to machine. 

Variables in C language can be stored in different storage classes, such as Auto, extern, static, and register. Auto variables are the default storage class for variables declared within a function or block, and can only be accessed within the block. Extern variables are global variables initialized with a legal value and can be overwritten or changed in different blocks.

Static variables are used to declare static variables, which preserve their value even after they are out of their scope. They are initialized once and exist until the program's termination, without new memory being allocated. Global static variables can be accessed anywhere in the program and are assigned 0 by the compiler.

Register variables are declared with the same functionality as auto variables, but the compiler attempts to store them in the microprocessor's registers if a free register is available. This makes them faster to access than variables stored in memory during program runtime. Register variables are typically declared with the register keyword to improve program runtime efficiency.

Data types can have modifiers, such as Short Long Signed Unsigned, which can make variables either increase or decrease in size. For example, Long can extend an integer to be 4 bytes.


### DATA TYPES: - THEIR SIZES AND RANGE 
### Data Type	Size (in bytes)	Range
#### short int
(2 bytes )
#### unsigned short int 
(2 bytes) 	
#### unsigned int
(4 bytes)
#### int
(4 bytes)	
#### long int 
(4 bytes)
#### unsigned long int
(4 bytes)  
#### long long int
(8 bytes) 
#### unsigned long long int
(8 bytes)	
#### signed char
(1 byte)	
#### unsigned char
(1 byte) 	
#### float
(4 bytes)	
#### double
(8 bytes) 
#### long double
(12 bytes)	


## CODE 
```

//experiment 2
#include<iostream>
using namespace std;
int main(){
    int a,b,c,add,sub;
    int div,prod,mod;

    cout<<"Enter the value for A"<<endl;
    cin>>a;
    cout<<"Enter the value for B"<<endl;
    cin>>b;

    if(b>0 && b<200  && a>0 && a<250){
     //--------COMPARISON OPERATOR //-------LOGICAL OPERATORS

         add=a+b;   //--------ARITHMETIC OPERATORS  //--------ASSIGNMENT OPERATOR
         sub=a-b;   //--------ARITHMETIC OPERATORS
         div=a/b;   //--------ARITHMETIC OPERATORS 
         prod=a*b;  //--------ARITHMETIC OPERATORS
         mod=a%b;   //--------ARITHMETIC OPERATORS

       
         ++a;       //------INCREMENT OPERATOR
         --b;       //------DECREMENT OPERATOR
         

    

    cout<<"Sum of the entered value is "<<add<<endl<<endl;        
    cout<<"Difference of the entered value is "<<sub<<endl<<endl;
    cout<<"Division of the entered value is "<<div<<endl<<endl;
    cout<<"Product of the entered value is "<<prod<<endl<<endl;
    cout<<"Modulus of the entered value is "<<mod<<endl<<endl;
   
    cout<<"Incremented A is "<<a<<endl<<endl;
    cout<<"Decremented B is "<<b<<endl<<endl;
    }
  
    else{
        cout<<endl<<"CHECK THE VALUES OF A AND B, IT SHOULD BE LESS THAN 250(for A) AND 200(for B)"<<endl;
        cout<<"                                    or"<<endl;
        cout<<"               ENTER NON-ZERO NUMBER FOR THE VALUE OF A and B"<<endl<<endl<<endl<<endl;
    };  //--------COMPARISON OPERATOR

    return 0;
}

```

### OUTPUT OF THE CODE
![image](https://github.com/user-attachments/assets/b9f2e86b-cee6-4305-a893-8ca6e9ca3600)


## CONCLUSION
Learnt different types of data type and how to use them in c++.
