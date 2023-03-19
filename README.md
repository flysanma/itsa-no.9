# itsa-no.9
#include <iostream>  
#include <math.h>  
using namespace std;  
   
int main() {  
    int a=0;                //定義變數
    int b=0;  
    cin>>a;                 //輸入一個變數
    for (int i = 1; i <= a; i++)             //for迴圈,只要i小於a,i便會一直加一
    {  
        if(i%3==0){b+=i;}    //檢查當前的i是否可以被3整除,若是i的倍數，就把i的值加到b上
    }  
    cout<<b<<'\n';            //輸出總和
       
    return 0;  
}  
