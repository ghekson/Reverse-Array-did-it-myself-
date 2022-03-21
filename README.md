# Reverse-Array-did-it-myself-

test

Working code C#. Visual Studio. Reverse Array. Did it myself.

#include <iostream>  

using namespace std;

int n, i, a[10], s = 0, ss = 0;
int size = 10;

int main()
{

	for (i = 0; i<10; i++)

		cin >> a[i];

	for (i = size - 1; i >= 0; --i)

		cout << a[i] << ' ';

	system("pause");

	return 0;


}
