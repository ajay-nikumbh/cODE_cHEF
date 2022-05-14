26. https://www.codechef.com/problems/CIELRCPT

```cpp
#include <iostream>
using namespace std;

int main()
{
	// your code goes here
	int t,n;
	cin>>t;
	while(t--)
	{
	     cin>>n;
	     int arr[]={2048,  1024, 512,  256,  128,  64, 32, 16, 8,  4,  2,  1};
      	     int c=0;
        
	     for (int i = 0; i < 12; i++)
       	     {
		c=c+n/arr[i];
		n=n-n/arr[i]*arr[i];
	     }
      cout<<c<<endl;
      
   }
   return 0;
}

```

```cpp
#include <bits/stdc++.h>
using namespace std;
#define ll long long
int main()
{
    int t;
    cin >> t;
    while (t--)
    {
        int arr[12] = {1, 2, 4, 8, 16, 32, 64, 128, 256, 512, 1024, 2048};
        sort(arr, arr + 12, greater<int>());
        ll p;
        cin >> p;
        ll ans = 0;
        for (int i = 0; i < 12; i++)
        {
            if (p / arr[i] != 0)
            {
                p -= arr[i];
                i--;
                ans++;
            }
        }
        cout << ans << endl;
    }
    return 0;
}

```

```cpp
#include<bits/stdc++.h>
using namespace std;

int main()
{

int t;
cin>>t;
while(t--)
{
	int k;
	cin>>k;
	int i=11;
	int x=0;
	while(i>=0)
	{
		x+=k/(int)(pow(2,i));
		k=k% (int)(pow(2,i));
		i--;
	}
	cout<<x<<endl;
}



return 0;
}

```
