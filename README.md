# Letter-Checker
#include < iostream>
using namespace std;
int main()
{
	char alpha;   //declaring variable with datatype char
	cout << "Enter the Alphabet: " << endl;
	cin >> alpha;
	if (alpha >= 'A' && alpha <= 'Z' || alpha >= 'a' && alpha <= 'z') //using nested if else statement
	{
		if (alpha == 'a' || alpha == 'e' || alpha == 'i' || alpha == 'o' || alpha == 'u')
		{
			cout << "You entered a vowel " << endl;
		}
		else
		{
			cout << "You entered a consonant " << endl;
		}
	}
	else
	{
		cout << "Incorrect command! " << endl;  //displays this message if a number or special character is entered
	}
	
	return 0;
}
