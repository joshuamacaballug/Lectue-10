# Lectue-10
// Some counting.cpp : This file contains the 'main' function. Program execution begins and ends there.
//

#include <iostream>
using namespace std;
int main()
{
	cout << "This code will print from 0-50\n";
	for (int x = 0; x < 51; x++) {
		cout << "" << x << "\n";
	}

	cout << "This code will print from 50-0\n";
	for (int x = 50; x >= 0; x--) {
		cout << "" << x << "\n";
	}
	cout << "This code will print from 30-50\n";
	for (int x = 30; x < 51; x++) {
		cout << "" << x << "\n";
	}
	cout << "This code will print from 50-10 (counts down by 2)\n";
	for (int x = 50; x >= 10; x = x - 2) {
		cout << "" << x << "\n";
	}
	cout << "This code will print from 100-200(counts up by 5)\n";
	for (int x = 100; x < 205; x = x + 5) {
		cout << "" << x << "\n";
	}
}
// Run program: Ctrl + F5 or Debug > Start Without Debugging menu
// Debug program: F5 or Debug > Start Debugging menu

// Tips for Getting Started: 
//   1. Use the Solution Explorer window to add/manage files
//   2. Use the Team Explorer window to connect to source control
//   3. Use the Output window to see build output and other messages
//   4. Use the Error List window to view errors
//   5. Go to Project > Add New Item to create new code files, or Project > Add Existing Item to add existing code files to the project
//   6. In the future, to open this project again, go to File > Open > Project and select the .sln file
