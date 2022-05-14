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
