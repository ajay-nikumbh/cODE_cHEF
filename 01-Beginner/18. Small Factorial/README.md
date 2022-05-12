18. https://www.codechef.com/problems/FLOW018

```cpp
#include <iostream>
using namespace std;

int main() {
	// your code goes here 
	long t;
	cin >> t;
	while(t--)
	{
	    int n;
	    cin >> n;
	    int fact = 1;
	    for(int i=1; i<=n; i++)
	    {
	        fact = fact*i;
	    }
	    cout << fact << endl;
	}
	return 0;
}

```
