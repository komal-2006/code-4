# code-4

#include<bits/stdc++.h>
using namespace std;

vector<int> passedBy(int a, int &b) {
     return{a+1, b+2};
      }
      
int main(){
int t;
cin>>t;
while(t--){
      int a, b;
      cin>>a>>b;
      Solution obj;
      vector<int> ans = obj.passedBy(a,b);
      cout<<ans[0] << " " << ans[1]<<"\n";
      }
return 0;
}
      
