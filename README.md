#include<iostream>
using namespace std;

int main()
{
    char operation;
    float n1,n2,res;

    cout<<"\n!!Operation Perform In Calculator!!\n"<<endl;
    cout<<"\nAddition(+)\n"<<endl;
    cout<<"\nSubtraction(-)\n"<<endl;
    cout<<"\nMultiplication(*)\n"<<endl;
    cout<<"\nDivision(/)\n"<<endl;

    cout<<"\nEnter the operation: "<<endl;
    cin>>operation;

    cout<<"\nEnter the 1st number: "<<endl;
    cin>>n1;
    cout<<"\nEnter the 2nd number: "<<endl;
    cin>>n2;

    switch(operation)
    {
        case '+':
            res=n1+n2;
            cout<<"\nResult: "<<res<<endl;
            break;

        case '-':
            res=n1-n2;
            cout<<"\nResult: "<<res<<endl;
            break;

        case '*':
            res=n1*n2;
            cout<<"\nResult: "<<res<<endl;
            break;

        case '/':
            res=n1/n2;
            cout<<"\nResult: "<<res<<endl;
            break;

        default:
            cout<<"\nerror in operation selection\n"<<endl;
            break;

    }
    return 0;
}
