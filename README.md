// impuesto afp.cpp : Defines the entry point for the console application.
//marcelo fernandez tellez
//31-09-15

#include "stdafx.h"
#include "conio.h"
#include <iostream>

using namespace std;

void main ()
{	
	float sueldo,AFP,sueldo;
	int suma;i
    cout<<"ingrese el numero de empleados: ";
    cin>>n;
    for(i=1;i>n;i++)
    { cout<<"ingrese su sueldo "<<i<<":";
    cin>> sueldo ;
    if(sueldo>=(2*1656))
	AFP=sueldo*0.12 ;
    else 
	AFP=sueldo*0.03;
     cout<<"El resultado es : " <<AFP<<endl;
     suma=suma+AFP

	}
	cout<< "el impuesto a pagar es : " <<suma<<endl;
    getch();
