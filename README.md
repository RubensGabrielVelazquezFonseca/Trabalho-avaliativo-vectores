#include <vector>
#include <iostream>

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

        cout << "Saiu" << endl;
        
        
        
   int opcao;
   int soma;
   vector<int>::iterator it;
   do
   {
        cout << "Escolha a opção" << endl;
        cout <<"1: Imprimir o somatório de seus elementos" << endl;
        cout <<"2: Imprimir a média de seus elementos" << endl;
        cout <<"3: Imprimir a média e o somatório" << endl;
        cout <<"4: Substituir por zero todos os valores negativos e imprimir a média" << endl;
        cout <<"5: Substituir por zero todos os valores repetidos e imprimir a média e o somatório" << endl;
        cout<<"6:  mostrar o vetor ordenado" << endl;
        cout <<"0: Sair da aplicação" << endl;
        cin >> opcao;
        cin.ignore();
        switch (opcao) {
            case 1: // SOMA
            soma = 0;
            for (it = numeros.begin(); it != numeros.end(); it++)
            {
               soma += *it; 
            }
            cout << "A soma é: " << soma << endl;
            cout << "Pressione enter para continuar" << endl;
            cin.get();
           
            break; 
            
            
            case 2:
            break;
           
            case 3:
            break;
            
            case 4:
            break;
            
            case 5:
            break;
            
            case 6:
            break;
     
           case 0:
           break;
        } 
   }
   while (opcao != 0);
   cout << "Tchau!";
 
 return 0;
}
 
