11. https://www.codechef.com/problems/TSORT

```cpp
#include <iostream>
#include <bits/stdc++.h>
using namespace std;

int main()
{
	int t;
	cin >>t;
	int a[t];
	
	for(int i=0;i<t;i++)
	{
	    cin >> a[i];
	}
	
	sort(a,a+t);
    
    for(int i=0;i<t;i++)
    {
	    cout<< a[i] <<endl;;
	}
	return 0;
}

```
