# sgdr#include <iostream>
using namespace std;
 
int isEven(int num)
{
    return !(num & 1);
}
 
int main(){
 
    int num;
 
    // Nhập số từ người dùng
    cout<<"Enter any number: ";
    cin>>num;
 
    // Nếu hàm isEven() function trả về 0, thì số là số chẵn
    if(isEven(num))
    {
        //in số chẵn
        cout<<"The entered number is even.";
    }
    else
    {
        //in số lẻ
        cout<<"The entered number is odd.";
    }
 
    return 0;
 
}
 
