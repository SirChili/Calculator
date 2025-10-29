#include <iostream>
#include <vector>
#include <cmath>

//ISO C++14 Standard is the version of C++ I'm using

using namespace std;

void addition() {

	int num1 = 0;
	int num2 = 0;
	system("cls");
	cout << "Enter First Number: \n";
	cin >> num1;
	system("cls");
	cout << "Enter Second Number: \n";
	cout << num1 << " + ";
	cin >> num2;
	double total = num1 + num2;
	system("cls");
	cout << num1 << " + " << num2 << " = " << total << '\n';

}
void subtraction() {

	int num1 = 0;
	int num2 = 0;
	system("cls");
	cout << "Enter First Number: \n";
	cin >> num1;
	system("cls");
	cout << "Enter Second Number: \n";
	cout << num1 << " - ";
	cin >> num2;
	double total = num1 - num2;
	system("cls");
	cout << num1 << " - " << num2 << " = " << total << '\n';


}
void multiplication() {

	int num1 = 0;
	int num2 = 0;
	system("cls");
	cout << "Enter First Number: \n";
	cin >> num1;
	system("cls");
	cout << "Enter Second Number: \n";
	cout << num1 << " x ";
	cin >> num2;
	double total = num1 * num2;
	system("cls");
	cout << num1 << " x " << num2 << " = " << total << '\n';

}
void division() {

	int num1 = 0;
	int num2 = 0;
	system("cls");
	cout << "Enter First Number: \n";
	cin >> num1;
	system("cls");
	cout << "Enter Second Number: \n";
	cout << num1 << " / ";
	cin >> num2;
	double total1 = num1 / num2;
	double total2 = num1 % num2;
	system("cls");
	cout << num1 << " / " << num2 << " = " << total1 << '\n';
	cout << "Remainder Of " << total2 << "\n";

}
// Square Root Position
void quadraticOne() {
	// Formula: x = −(b) ± √ b^2 − 4ac / 2a

	double a,b,c;
	
	cout << "Choose A, B, C\n";
	cin >> a; cin >> b; cin >> c;

	double numerator = sqrt(pow((b), 2) - (4 * a * c));
	
	double rootOne = (-b + numerator) / (2 * a);
	double rootTwo = (-b - numerator) / (2 * a);

	cout << "{" << rootOne << "," << rootTwo << "}" << '\n';

}
void dividingPolynomials() {
	//Synthetic Division (Simplified Long Division (Doesn't Work if something is in front of x for d(x)))
	double a,b,c,d,e,f;
	double g;

	cout << "What is d(x)\n ex. -4 or 4?\n";
	cin >> g;
	system("cls");
	cout << "Input numbers for f(x)\nStarts on 5th Power, put 0 if the power is not there\n";
	cin >> a; cin >> b; cin >> c; cin >> d; cin >> e; cin >> f;

	g = -(g);

	system("cls");

	double g_Times_a = g * a;
	double x3 = g_Times_a + b;
	double x3_Times_g = g * x3;
	double x2 = x3_Times_g + c;
	double x2_Times_g = g * x2;
	double x = x2_Times_g + d;
	double x_Times_g = g * x;
	double cont = x_Times_g + e;
	double cont_Times_g = cont * g;
	double rem = cont_Times_g + f;

	cout << "\n(" << a << "x^4 " << x3 << "x^3 " << x2 << "x^2 " << x << "x " << cont << ") " << rem << "/ x " << -(g) << '\n';

	if (rem == 0) { cout << "Is a Factor\n"; }
	else { cout << "Not a Factor"; }
}
void distanceBetweenPoints() {
	// 2D Formula: d = √(x2 - x1)^2 + (y2 - y1)^2
	// 3D Formula: d = √(x2 - x1)^2 + (y2 - y1)^2 + (z2 - z1)^2

	char choice;

	cout << "Is it Three Dimensional? y/n\n";
	cin >> choice;
	system("cls");
	double x1, x2, y1, y2,z1,z2;

	if (choice == 'y') {

		//x1,y1,z1 values
		cout << "("; cin >> x1;
		system("cls");
		cout << "(" << x1 << ','; cin >> y1;
		system("cls");
		cout << '(' << x1 << ',' << y1 << ','; cin >> z1;
		system("cls");
		cout << '(' << x1 << ',' << y1 << ',' << z1 << ")\n";
		
		//x2,y2,z2 values
		cout << "("; cin >> x2;
		system("cls");
		cout << '(' << x1 << ',' << y1 << ',' << z1 << ")\n";
		cout << "(" << x2 << ','; cin >> y2;
		system("cls");
		cout << '(' << x1 << ',' << y1 << ',' << z1 << ")\n";
		cout << '(' << x2 << ',' << y2 << ','; cin >> z2;
		system("cls");
		cout << '(' << x1 << ',' << y1 << ',' << z1 << ")\n";
		cout << '(' << x2 << ',' << y2 << ',' << z2 << ")\n";

		double d = sqrt(pow((x2 - x1), 2) + pow((y2 - y1), 2) + pow((z2 - z1), 2));
		cout << "Distance: " << d << '\n';
	}
	if (choice == 'n') {

		//x1,y1 values
		cout << "("; cin >> x1;
		system("cls");
		cout << "(" << x1 << ','; cin >> y1;
		system("cls");
		cout << '(' << x1 << ',' << y1 << ')' << '\n';

		//x2,y2 values
		cout << "("; cin >> x2;
		system("cls");
		cout << '(' << x1 << ',' << y1 << ')' << '\n';
		cout << "(" << x2 << ','; cin >> y2;
		system("cls");
		cout << '(' << x1 << ',' << y1 << ')' << '\n';
		cout << '(' << x2 << ',' << y2 << ')' << '\n';

		double d = sqrt(pow((x2 - x1), 2) + pow((y2 - y1), 2));

		cout << "Distance: " << d << '\n';
	}
}

//------------------Incomplete-----------------------
void quadraticTwo() {
	//Formula: ax^2 + bx = 0

	
}

void radicalEquations() {

	double a = 0;
	double b = 0;
	double x = 0;

	double radical = a * (x) * b;

}

void squareRoot() {

	system("cls");
	int choice;

	cout << "1. Positive \n2. Negative\n";
	cin >> choice;

	if (choice < 3 && choice > 0) {
		int num1 = 0;
		system("cls");
		cout << "Enter Number: \n";
		cin >> num1;
		system("cls");

		if (choice == 1) {
			double total = sqrt(num1);
			if (total > 0.0) {
				cout << total << endl;
				cout << "Yes?";
			}
			else { cout << "_/" << num1 << " = " << total << "\nUnfinished"; }
		}
		if (choice == 2) {
			double total = sqrt(-1 * num1);
			if (total > 0.0) {
				cout << total << endl;
				cout << "Yes?";
			}
			else { cout << total << 'i' << "\nUnfinished"; }
		}
	}
	if (choice > 2 || choice < 1) { system("cls"); cout << "Invalid Input"; }
}



int main() {

	int choice;

	cout << "1. Addition \n2. Subtraction\n3. Multiplication\n4. Division\n5. Square Root\n6. Quadratic\n7. Dividing Polynomials\n8. Distance\n";
	cout << "\nEnter By Number.\n";
	cin >> choice;

	// Think of a better way rather than a ton of if statements
	if (choice == 1) { system("cls");  addition(); main(); }
	if (choice == 2) { system("cls"); subtraction(); }
	if (choice == 3) { system("cls"); multiplication(); }
	if (choice == 4) { system("cls"); division(); }
	if (choice == 5) { system("cls"); squareRoot(); }
	if (choice == 6) { system("cls"); quadraticOne(); }
	if (choice == 7) { system("cls"); dividingPolynomials(); }
	if (choice == 8) { system("cls"); distanceBetweenPoints(); }
	if (choice > 8 || choice < 1) { system("cls"); cout << "Invalid Input.\n\n"; main(); }

}
