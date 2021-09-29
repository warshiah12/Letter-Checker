# Letter-Checker
#include < iostream>
using namespace std;
int main()
{
	char alpha;
	cout << "Enter the Alphabet: " << endl;
	cin >> alpha;
	if (alpha == 'a' || alpha == 'e' || alpha == 'i' || alpha == 'o' || alpha == 'u')
	{
		cout << "You entered a vowel " << endl;
	}
	else 
	{
		cout << "You entered a consonant " << endl;
	}
	
	return 0;
}
