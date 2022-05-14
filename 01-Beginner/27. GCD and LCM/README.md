27. https://www.codechef.com/problems/FLOW016

```cpp
#include <bits/stdc++.h>
using namespace std;

int gcd(int x,int y)
{
    if (y==0)
    return x;
    return gcd(y,x%y);


}

int main() 
{   long long int t,x ,y ;
    cin>>t;
    while(t--)
    {
        cin>>x>>y;cout<<gcd(x,y)<<" ";cout<<((x*y)/gcd(x,y))<<endl;
    
    }
	return 0;
}


```
