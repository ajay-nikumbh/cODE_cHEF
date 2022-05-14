30. https://www.codechef.com/problems/FLOW005

```cpp
#include <iostream>
using namespace std;

int main() 
{
    int t;
    cin >> t;

     while(t--)
    {
        int n;
        cin >> n;
        
        cout<<(n/100)+(n%100)/50+(n%50)/10+(n%10)/5+(n%5)/2+(n%5)%2<<'\n';
    }
	return 0;
}
```
