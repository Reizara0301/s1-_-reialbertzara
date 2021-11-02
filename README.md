# s1-_-reialbertzara
// summative code 1.cpp : This file contains the 'main' function. Program execution begins and ends there.
//

#include <iostream>
#include <exception>
#include <string>

using namespace std;
int main()
{

	cout << "Enter your full name";
	string name;
	cin >> name;

	cout << "Enter your age" << endl;
	string age;
	cin >> age;
	cout << "\nEnter The location" << endl << "A.Abu dhabi" << endl << "B.Sharjah" << endl << "C.Ajman" << endl << " D.Dubai" << endl << "E.Rak" << endl << " F.Umm - al - quwain" << endl << "G.Fujairah" << endl << " H.Al ain" << endl << "I.other" << endl;
	char letter;
	cin >> letter;
	switch (letter)

	{
	case 'A':
	case 'a':
		cout << "You Entered Lance name";
		cout << "Abu dhabi, transportation charge are AED 1000" << endl;
		break;
	case 'B':
	case 'b':
		cout << "Sharjah, transportation charge are AED 500" << endl;
		break;
	case 'C':
	case 'c':
		cout << "Ajman, transportation charge are AED 390" << endl;
		break;
	case 'D':
	case 'd':
		cout << "Dubai, transportation charge are AED 650" << endl;
		break;
	case 'E':
	case 'e':
		cout << "Rak, transportation charge are AED 250" << endl;
		break;
	case 'F':
	case 'f':
		cout << "Umm-al-quwain, transportation charge are AED 300" << endl;
		break;
	case 'G':
	case 'g':
		cout << "Fujairah, transportation charge are AED 300" << endl;
		break;
	case 'H':
	case 'h':
		cout << "Al ain, transportation charge are AED 1000" << endl;
		break;
	case 'I':
	case 'i':
		cout << "other,no transportation availble" << endl;
		break;
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
