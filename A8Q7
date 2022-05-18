#include<bits/stdc++.h>
using namespace std;
int n,m,d,a[100],s[100],ans;
int main(){
    cin>>n;
    for(int i = 1; i<=n; i++){
        cin>>a[i];
        s[i] = s[i-1] + a[i];
    }
    cin>>d>>m;
    for(int i = m; i<=n; i++){
        if(s[i] - s[i-m] == d){
            ans++;
        }
    }
    cout<<ans<<endl;
    return 0;
}
