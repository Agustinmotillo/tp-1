#include <bits/stdc++.h>
using namespace std;
bool EsMultiplo (int e);

int main(){
	int a,e;
	string flag="NO ES MUES  MULTIPLO";
	cout<<"ingrese un numero"<<endl;
	cin>>a;
	if ( EsMultiplo(a)){
		flag="es multiplo";
	}
	
	cout<<flag<<endl;
	
	return 0;
}
	
	
bool EsMultiplo (int a){
		bool es = false;
		if(a%3 == 0){
			es = true;
		}
		 
	return es;
	}

