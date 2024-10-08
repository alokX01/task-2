# task-2//simple calculator
#include <iostream>
using namespace std;

// Driver code
int main()
{
	char op;
	float num1, num2;

	
	cin >> op;
	cin >> num1 >> num2;
	switch (op) {
	// If user enter +
	case '+':
		cout << num1 + num2;
		break;

	// If user enter -
	case '-':
		cout << num1 - num2;
		break;

	// If user enter *
	case '*':
		cout << num1 * num2;
		break;

	// If user enter /
	case '/':
		cout << num1 / num2;
		break;

	default:
		cout << "Error! operator is not correct";
	}
	
	return 0;
}
