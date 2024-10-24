# EXP-9
## Aim
To study and implement C++ Pointer basics.

## Software Used
Visual Studio Code

## Theory
Pointers are symbolic representations of addresses.
They enable programs to stimulate call-by-preference as well as to create and manipulate dynamic data structures.
Iterating over elements in arrays or other data structures is one of the main use of pointers.
The address of the variable that we are working with is assigned to the pointer variable that points to the same data type.

## Code
a
```
// NAME - Sivapriya Nambiar 
// PRN - 23070123125
// EXPERIMENT - 9(A)  

// Program to illustrate pointers. 

#include <bits/stdc++.h> 
using namespace std;
void geeks()
{
    int var = 5;

    int* ptr;                  // Declaring pointer variable. 

    ptr = &var;

    cout<<"Value at ptr = "<<ptr<<"\n";
    cout<<"Value at var = " <<var<<"\n";
    cout<<"Value at *ptr = "<<*ptr<<"\n";

}

// Driver Program 

int main()
{
    geeks();
    return 0;
}
```
B
```
// NAME - Sivapriya Nambiar 
// PRN - 23070123125
// EXPERIMENT - 9(B)

// Program to create one-dimensional array of pointers. 

#include <iostream> 
using namespace std; 

int main() 
{
    int* p=new int[7];  // Creating an array 

    for (int i=0; i<5; i++)  // Initializing the aray p[]
    {
        p[i]=10*(i+1);
    }

    cout<<*p<<"\n"; 
    cout<<*p+1<<"\n";
    cout<<*(p+1)<<"\n";
    cout<<2[p]<<"\n";
    cout<<p[2]<<"\n";
    *p++;

    cout<<*p;                 // Pointing to next location. 

    return 0; 
}
```
c
```
// NAME - Sivapriya Nambiar 
// PRN - 23070123125 
// EXPERIMENT - 9(C) 

#include <iostream>
using namespace std;
int main()
{
    int *p ,b=10;
    p = &b ;
    cout <<*p << "  " << b << endl <<p <<"  "<< &b<<endl;
    p++;
    cout<<"After increment:" <<p<<endl;
    float *n, a=8.923;
    n=&a;
    cout<< endl<<*n<<"  "<<a<<endl<<n<<"  "<<&a<<endl;
    n++;
    cout<<" After increment" <<n <<endl;
    char *ch, c(10);
    c='#';
    ch=&c;
    cout<< endl<< (void*)ch<<"  "<<endl;
    ch++;
    cout<<" After increment:" << (void*)ch<<endl;
    return 0;
}
```
## Output

![image](https://github.com/user-attachments/assets/ae7ddb18-25ac-4a0f-9cdc-e9c6f42172f2)

![image](https://github.com/user-attachments/assets/e58fdcc0-5e3e-47e4-9481-4a7d5f621fe7)

![image](https://github.com/user-attachments/assets/c7140a67-3e32-404e-a440-0e233117f4a8)

## Conclusion
Learnt about pointers in C++.
