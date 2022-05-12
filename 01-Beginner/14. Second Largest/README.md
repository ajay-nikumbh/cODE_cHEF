14. https://www.codechef.com/problems/FLOW017

```cpp
#include <iostream>
using namespace std;
int main()
{
    int t,n1,n2,n3;
    cin>>t;

    for(int i=0;i<t;i++)
    {
       cin>>n1>>n2>>n3;

	   if((n1>n2 && n1<n3) || (n1<n2 && n1>n3)) cout<<n1<<endl;
	   
	   else if((n2>n1 && n2<n3)||(n2<n1 && n2>n3)) cout<<n2<<endl;
	   
	   else cout<<n3<<endl;
    
        
    }
    return 0;
}

```
