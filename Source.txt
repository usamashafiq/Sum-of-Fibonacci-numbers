#include<iostream>
#include<conio.h>

#include<string>
using namespace std;
void main() {
	int F[30],p=0,q=1,sum=1;
	F[0] = 5;
	F[1] = 8;
	for (int i = 2; i <= 30; i++) {
		F[i] = F[p] + F[q];
		p++;
		q++;
		sum = sum + F[i];
		
		}
	
	cout << "sum is :" << sum << endl;

	
	_getch();

}
