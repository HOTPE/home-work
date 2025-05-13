#include <iostream>
#include <vector>
#include <sstream>
using namespace std;
int main()
{
    int n;
    cin>>n;
    cin.ignore();
    vector<int> a(n,0);
    for(int i = 0; i < n; i++)
    {
        string line;
        getline(cin,line);
        stringstream ss(line);
        int tmp;
        while(ss >> tmp)
        {
        a[i]++;    
        }
    }
    cout<<n<<endl;
    for(int i = 0; i < n; i++)
    {
        cout<<a[i]<<" ";
    }
    cout<<endl;
}
