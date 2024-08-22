
## Aim-
To learn how to use VS Code for programming and how to handle user input and output in C++.

## Software Used-
- VS Code

## Problem Statements-

1. **Print a Simple 'Hello World' Message**
   - Write a program that outputs the message "Hello World".

2. **Get User Input and Display It**
   - Write a program that takes input from the user and displays it back.

3. **Create a Basic Calculator**
   - Write a program that performs basic arithmetic operations (addition, subtraction, multiplication, division) based on user input.

## Theory-

- **`cout`**: Used to print messages or output to the console.
- **Namespace**: Helps to avoid naming conflicts by limiting the scope of variables and functions.
- **`endl`**: Used to insert a newline character and flush the output buffer.

---


## Program Codes-


```javascript
//Mukesh Rothe //23070123089 //CDS EXP1
#include<iostream>
using namespace std;
int main()
{
    string a;
    cout << "Enter your name ";
    getline(cin,a);
    cout<<"Hello  " <<a;
    return 0;
}

//Mukesh Rothe //23070123089 //CDS EXP1
#include <iostream>
using namespace std;
int main() 
{

    int a,b,product, sum,answer;
    float quotient;
    cout<<"Enter the value of a:\n";
    cin>>a;
    cout<<"Enter the value of b:\n";
    cin>>b;
    quotient=a/b;
    cout<<"The solution of a/b:"<<quotient<<"\n";
    product=a*b;
    cout<<"The solution of a*b:"<<product<<"\n";
    sum=a+b;
    cout<<"The solution of a+b:"<<sum<<"\n";
    answer=a-b;
    cout<<"The solution of a-b:"<<answer<<"\n";

    return 0;
}

//Mukesh Rothe //23070123089 //CDS EXP1
#include<iostream>
using namespace std;
int main()
{
    string a;
    cout << "Enter your name ";
    getline(cin,a);
    cout<<"Hello  " <<a;
    return 0;
}
```
# Output-
Hello World-

Calculator-

User Input-




## Conclusion-

In this tutorial, we learned how to:
- Take input from the user and display it using C++.
- Implement basic arithmetic operations such as addition (`+`), subtraction (`-`), multiplication (`*`), and division (`/`).

