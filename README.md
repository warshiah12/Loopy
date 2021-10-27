# Loopy
[ displaying numbers from 0 ]
#include <iostream>
using namespace std;
int main() {
	int myInt=0;    /*declaring variables and assigning value to it*/
	int counter;
	cout << "Enter a number: " ;
	cin >> counter;
	cout << "\nThe numbers from 0 to " << counter << " are: " << endl;
	do {  //using do-while loop
		cout << myInt << endl;   /*this statement will display the numbers from 0 to the number that the user entered. 
								 for example if user entered '5' the numbers will be displayed from 0 to 5*/
		myInt++;     //using increement operator
	}
	while (myInt <= counter);  //checking the condition

	return 0;
}
