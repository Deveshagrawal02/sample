# Simple-Calculator

//C++ Code

#include <iostream>
using namespace std;
int main()
{
	int a , b ;
	cout << "enter the numbers :";
	cin >> a >> b ;
	char op;
	cout << "enter the operator :";
	cin >> op;
	switch (op)
	{
		case '+':
			cout << a + b << endl ;
			break; 
			case '-':
			cout << a - b << endl ;
			break;
			case '*':
			cout<< a * b << endl ;
			break;
			case'/':
			cout<< a / b << endl ;
			break;
			case '%':
			cout << a % b << endl ;
			break;
			default:
			cout<< "invalid operation ";	
	}
	return 0;
}
  
