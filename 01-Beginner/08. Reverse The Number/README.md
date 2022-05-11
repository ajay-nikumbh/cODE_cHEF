8. https://www.codechef.com/problems/FLOW007

```cpp
#include<iostream>
using namespace std;
int main()
{
    int T;
    long int n;
    int rev,mod;
    cin>>T;
    for(int i=0;i<T;i++)
    {
        cin>>n;
        mod=0;
        rev=0;
        while(n!=0)
        {
            mod=n%10;
            rev=rev*10+mod;
            n=n/10;
        }
        cout<<rev<<endl;
    }
    return 0;

}
```
