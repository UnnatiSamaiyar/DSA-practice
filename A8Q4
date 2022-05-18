#include <bits/stdc++.h>
using namespace std;
int main(){
    int n,m;
    cin>>n>>m;
    vector<int>a(n);
    for(int i = 0; i<n; i++){
        cin>>a[i];
    }
    vector<int>b(m);
    for(int j = 0; j<m; j++){
        cin>>b[j];
    }
    int ans = 0;
    for(int x = 1; x<=100; x++){
        bool ok = true;
        for(int i = 0; i<n; i++){
            if(x%a[i]!=0){
                ok = false;
            }
        }
        for(int i = 0; i<m; i++){
            if(b[i]%x!=0){
                ok = false;
            }
        }
        if(ok){
            ans++;
        }
    }
    cout<<ans<<endl;
    return 0;
}
