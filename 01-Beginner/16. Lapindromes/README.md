16. https://www.codechef.com/problems/LAPIN

```cpp
#include <bits/stdc++.h>
using namespace std;
int main() {
    int t;
    cin>>t;
    while(t--)
    {
        string s;
        cin>>s;
        string first, second;
        int n = s.length();
        for(int i=0;i<n/2;i++)
        {
            first+=s[i];
            second+=s[n-i-1];
        }
        sort(first.begin(), first.end());
        sort(second.begin(), second.end());
        
        if(first == second)
        {
            cout<<"YES\n";
        }
        else
        {
            cout<<"NO\n";
        }
    }
}
```

```cpp
#include<bits/stdc++.h>
#include<iostream>
using namespace std;
int main()
{
    int t;
    cin>>t;
    while (t--)
    {
        string s,s1="",s2="";
        cin>>s;
        int l=s.length();
        if(l%2==0)
        {
            s1=s.substr(0,l/2);
            s2=s.substr(l/2,l);
        }
        else
        {
            s1=s.substr(0,l/2);
            s2=s.substr((l/2)+1,l);
        }
        sort(s1.begin(),s1.end());
        sort(s2.begin(),s2.end());
        if(s1==s2)
        {
        cout<<"YES"<<"\n";
        }
        else
        {
        cout<<"NO"<<"\n";
        }
    }
    return 0;
}
```
