#include <iostream>
using namespace std;

int cq, cj, cp, cr, cc;
int total;
float totald;
const int pq = 15, pj = 18, pp = 20, pr = 12, pc = 25;


main(){
	cout<<"ingrese la cantidad de queso";cin>>cq;
	cout<<"ingresa la cntidad de jamon";cin>>cj;
	cout<<"ingresa la cantidad de papas";cin>>cp;
	cout<<"ingresa la cantidad de refresco";cin>>cr;
	cout<<"ingresa la cantidad de cerveza";cin>>cc;
	
	total = cq * pq + cj * pj + cp * pp + cr * pr + cc * pc;
	
	if(total > 150)
	{
		totald = total - (total * .15);
		cout<<"tu consumo es de :"<<totald;
	}
	else
	{
		cout<<"\ntu consumo es de :"<<total;
	}
	
	system ("pause");
	return 0;
}
