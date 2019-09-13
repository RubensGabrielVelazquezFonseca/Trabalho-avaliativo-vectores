#include<iostream>
#include<vector>

using namespace std;

int main(){

int x;
string continuar;

vector<int> numeros;

    numeros.size();

    do{
            
            
            cout << "Digite um numero: ";
            cin >> x;

            numeros.push_back(x);

            cout << "Deseja continuar? (s/n)";
            cin >> continuar;

    }while(continuar == "s");

        cout << "Saiu";

 

 

 

return 0;
}
 
