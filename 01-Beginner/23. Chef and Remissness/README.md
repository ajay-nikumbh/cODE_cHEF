23. https://www.codechef.com/problems/REMISS

```cpp
#include <iostream>
using namespace std;

int main() {
	// your code goes here
	int t;
	cin>>t;
	while(t--)
	{
	    int a,b,min;
	    cin>>a>>b;
	    if(a>b)
	    {
	        min=a;
	    }
	    else
	    {
	         min=b;
	    }
	    int max=a+b;
	    cout<<min<<" "<<max<<endl;
	}
	return 0;
}

```
