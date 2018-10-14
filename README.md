# 1

// 1. Напишите программу, проверяющую, является ли число составным. 

#include <iostream>
using namespace std;
int main() {

	int a, b, i;

	cin >> a;
	b = (a / 2);
	
	if (a == 2 || a == 3) cout << "Prime";

		

	

	if (a == 1) cout << "Unit";

		

	


	if (a != 1 && a != 2 && a != 3) {

		for (i = 2; i <= b; i++) {

			if (a%i == 0) {

				cout << "Composite";
				break;
			}
			if (i == b) {

				cout << "Prime";
		}
		}


		
	}


	return 0;



}
