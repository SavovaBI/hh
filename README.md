#include<iostream>
using namespace std;
int main(){
int arr[4][6];
for(int i=0;i<4;i++) {
	for(int j=0;j<6;j++) {
	cout<<"arr["<<i<<"]["<<j<<"]= ";
	cin>>arr[i][j];
		 }
	 }
cout<<"\n";
for(int k=0;k<4;k++) {
	for(int l=0;l<6;l++) {
	cout<<arr[k][l]<<"   ";
	 }
	cout<<"\n";
 }
return 0;
}
