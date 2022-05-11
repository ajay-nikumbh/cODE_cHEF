6. https://www.codechef.com/problems/FLOW006

```cpp
#include <bits/stdc++.h>
using namespace std;

int main() 
{
	
	ios_base::sync_with_stdio(NULL);
	cin.tie(NULL);
	int t;
	cin>>t;

	while(t--)
	{
	    int number;
		cin>>number;
		long sum = 0;
	
		while(number)
		{
			sum+=number%10;
			number/=10;
		}
		cout<<sum<<"\n";
	}

	return 0;
}

```
