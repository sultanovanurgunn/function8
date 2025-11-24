# function8
#include <iostream>
using namespace std;

void printCemveFerqveHasilveBolme(int a, int b){
    int C=a+b;
    int F=a-b;
    int H=a*b;
    int B=a/b;
    cout<<"cem="<<C<<endl;
    cout<<"ferq="<<F<<endl;
    cout<<"hasil="<<H<<endl;
    cout<<"bolme="<<B<<endl;
}
 int main(){
     int a,b;
     cout<<"iki eded daxil edin"<<endl;
     cin>>a>>b;
     
     printCemveFerqveHasilveBolme(a,b);
    
    return 0;
}
