15. https://www.codechef.com/problems/AMR15A

```cpp

#include <iostream>
using namespace std;

int main() {
	int n,i;
	cin>>n;
	int a[n];
	for(i=0;i<n;i++)
	{
	   cin>>a[i];
	}
	int count=0;
	int temp=0;
	
	for(i=0;i<n;i++)
	{
	    if(a[i]%2==0)
	    {
	        count++;
	    }
	    else
	    {
	       temp++;
	    }
	}
	if(count>temp)
	{
	    cout<<"READY FOR BATTLE";
	}
	else
	{
	    cout<<"NOT READY";
	}
	return 0;
}

```
