# code
'''C++'''

#include <iostream>

using namespace std;

int F[100000], n;

int main()
{
    cout<<"Enter n: ";
    cin>>n;

    F[0]=1;
    F[1]=1;
    for(int i=2; i<n; i++)
        F[i]=F[i-1] + F[i-2];

    for(int i=0; i<n; i++)
    cout<<F[i]<<" ";

    return 0;
}
