28. https://www.codechef.com/problems/PALL01

```cpp
#include <iostream>
#include <cstring>
using namespace std;
int main()
{
	// your code goes here
	int t;
	cin>>t;
	while(t!=0) 
	{
	    int n, x=0;
	    cin>>n;
	    int num=n;
	    
	    while(n!=0) 
	    {
	        int m=n%10;
	        x=x*10+m;
	        n=n/10;
	    }
	    
	    if(num==x) cout<<"wins"<<endl;
	    else cout<<"loses"<<endl;
	    t--;
	}
	return 0;
}

```
