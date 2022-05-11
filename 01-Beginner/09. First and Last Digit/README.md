9. https://www.codechef.com/problems/FLOW004

```cpp

#include<iostream>
using namespace std;

int main()
{
	int test;
	cin>>test;
	
	while(test--)
	{
		int number;
		cin>>number;
		int first=0, last;
		last= number%10;
		
		while(number>0)
		{
			first= number%10;
			number= number/10;
		}
		
		cout<<first+last<<endl;
	}
	return 0;
	
}
```
