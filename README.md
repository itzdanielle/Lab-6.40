# Lab-6.40
#include <iostream>
using namespace std;
#include <iomanip> 

int main() {
double meter;
double discount;
double regualr;
double total;
cout << setprecision(2) << fixed;

cout << "Input the carpet length you wish to buy\n";
cin >> meter;

if ( meter >= 10)
{ 
discount = meter * 2.75 * 0.15;
total = meter * 2.75 - discount;
cout << " You got a 15% discount!\n ";
cout << "Your new total is $" << total << endl;

}

else 
{
regualr = meter * 2.75;
 cout << " Your total is $" << regualr << endl;
}
}
