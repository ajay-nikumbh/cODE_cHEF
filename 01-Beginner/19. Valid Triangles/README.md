19. https://www.codechef.com/problems/FLOW013

```cpp
#include <iostream>
using namespace std;

int main()
{
	// your code goes here
	int t;
	cin>>t;
	
	while(t--)
	{
	    int a,b,c;
	    cin>>a>>b>>c;
	    
	    if(a+b+c == 180)
	    {
	        cout<<"YES"<<endl;
	    }
	    
	    else 
	    {
	        cout<<"NO"<<endl;
	    }
	}
	return 0;
}

```
