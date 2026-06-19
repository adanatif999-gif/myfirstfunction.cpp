# myfirstfunction.cpp
#include <iostream>
using namespace std;

int sum(int x, int y);

void g();

int main()
{
    int num1, num2;

    cout << "Enter first number" << endl;
    cin >> num1;

    cout << "Enter second number" << endl;
    cin >> num2;

    cout << "The sum is " << sum(num1, num2) << endl;

    g();

    return 0;
}

int sum(int x, int y)
{
    int c = x + y;
    return c;
}

void g()
{
    cout << "Hello good morning" << endl;
}
