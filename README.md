# ESTRUCTURA-DE-DATOS

//1.Leer 5 números enteros en un arreglo y mostrarlos en el mismo orden.

#include <iostream>
using namespace std;

int main(){
    
    const int N=5 ;
    int v[N];
    
    for(int i=0; i<N; i++){
        cin>>v[i];
    }
    
    for(int i=0; i<N; i++){
        cout<< v[i]<<" ";
    }
    
    return 0;
}