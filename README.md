# Assignent-of-c-
#Write a program to accept two integers and check whether they are equal or not

#include<iostream>
using namespace std;

int main()
{
    int num1, num2;

    cout << "Input the values for Number 1 and Number 2 :";
    cin >> num1 >> num2;

    if (num1 == num2)
    {
        cout << "Number 1 and Number 2 are equal";
    }

    else
    {
        cout << "Number1 and Number2 are not equal";
    }
}
