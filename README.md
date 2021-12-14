
#include<iostream>
#include<stdlib.h>
using namespace std;
int main()
{ int n1,n2;
cout<<"digite un numero par menor o igual a 50\n";cin>>n1;
	 n2=n1;
	  	  
	if ((n1<51) and (n1%2==0))
		{cout<<"\n\n*********** el numero ("<<n1<<") es par************\n\n";
		cout<<"iniciando proceso de reduccion de numero de par en par...\n\n";
		    while (n1>=0)
			{cout<<n1<<"\n";
			n1=n1-2; 
	        }
	   }
	else 
		{cout<<n1<<" no es par o es mayor a 50";}
}
