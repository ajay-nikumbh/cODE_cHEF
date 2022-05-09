2. https://www.codechef.com/problems/HS08TEST

```cpp
//  We have populated the solutions for the 10 easiest problems for your support.
// Click on the SUBMIT button to make a submission to this problem.

#include <iostream>
using namespace std;

int main()
{
    int w;
    float ac_bl;
    cin>>w;
    cin>>ac_bl;

    if(w%5==0 && w<=ac_bl-0.5)
    {
        cout<<((ac_bl-w)-(0.5));
    }
    
    else
    {
        cout<<ac_bl;
    }
	return 0;
}
```
