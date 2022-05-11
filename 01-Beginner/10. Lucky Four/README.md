10. https://www.codechef.com/problems/LUCKFOUR

```cpp
#include <iostream>
using namespace std;

int main()
 {
	int test;
	cin>>test;

	while(test--)
	{
	 string n;
	 cin>>n;
	 int ans=0;
	 
	 for(char i:n)
	 {
	 
	  if(i=='4')
	  {
		ans++;
	  }
	 
	}
	
	cout<<ans<<endl;

	}
	return 0;
}

```
