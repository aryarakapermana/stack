#include<iostream>
using namespace std;


//buat top
#define MAX 5
int stack_arr[MAX];
int top = -1;

//push
void push(int data){
	if (top==MAX-1){
		cout<<"Eror STACK OVERFLOW!!!!!.\n";
		
	}
	else{
		top++;
		stack_arr[top] = data;
		cout<<data<<" berhasil di push.\n";
	}
}

//pop
void pop(){
	if (top == -1){
		cout<<"Eror Tidak ada memori yang bisa di ambil.\n";
	}
	else{
		cout<<stack_arr[top]<<" berhasil pop.\n";
		top--;
	}
}

//display
void display(){
	if(top == -1){
		cout<<"Stack kosong.\n";
	}
	else {
		cout<<"Isi Stack nya (TOP KE BOTTOM): ";
		for(int i=top;i>=0;i--){
			cout<<stack_arr[i]<<" ";
		}
		cout<<"\n";
	}
	
}

int main(){
	push(15);
	push(13);
	push(12);
	push(19);
	pop();
	display();
	
	return 0;
}
