29. https://www.codechef.com/problems/PRB01

```cpp
#include <iostream>
using namespace std;

int main()
{
     int T;
     cin>>T;
     while (T--)
     {
        int n,r=0;
        cin>>n;
        for(int i=1;i<=n;i++)
        {
            if(n%i==0)
            {
                r++;
            }
        }
            if(r==2)
            {
                cout<<"yes"<<endl;
            }
            else
            {
                cout<<"no"<<endl;
            }
    }
	return 0;
}


```
