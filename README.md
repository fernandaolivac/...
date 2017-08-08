# algoritmo-labo

#include "stdafx.h"
#include "stdlib.h"
#include <iostream>
#include "conio.h"
using namespace std;
void main()
{int n,i,s;
do {cout<<"\n digite n:";
cin>>n;
}
while (n<0);
s=0; // Es nuestro acumulador
for(i=2;i<=n;i=i+2)
	s=s+i;
cout<<"La suma es igual a :"<<s<<endl;
getch();
}
