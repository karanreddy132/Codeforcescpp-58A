# Codeforcescpp-58A
#include<bits/stdc++.h>
 
using namespace std;
 
int main(){
  string s;
  cin >> s;
  string str = "hello";
  int j = 0;
  int len = s.length();
  for(int i=0;i<len;i++){
    if(s[i]==str[j]){
      j+=1;
      }
    if(j==5){
      cout << "YES";
      break;
    }
  }
  if(j<5){
    cout << "NO";
  }
  return 0;
}
