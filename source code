/************************************************************************************
                        Banking system program
************************************************************************************/
#include<iostream>   //header file
#include<conio.h> 	//other header file

using namespace std;  //namespace

int main(){    //main function
         
	int balance[3]={100000,100000,100000},option=0; //assign acount balance
	string names[3]={"Tanveer","Ali","Adnan"};   //acount names
	int passwords[3]={1111,1234,2222};	//acounts passwards
	int choice=0;
	while(choice!=2){
		choice=0;
		system("cls");
		 cout<<"\t\t\t\t****Welcome to the Maher Tanveer Ahmad banking system****";
		cout<<"\n\n\n\t\t\t\tSelect one Option"<<endl;  
		cout<<"\t\t\t\t1). Log In"<<endl;
		cout<<"\t\t\t\t2). Exit"<<endl;
		cin>>choice;
		if(choice==1){
			system("cls");
    	    string name;
    	    int password;
    	    cout<<"Enter Your Account Name:"<<endl;
    	    cin>>name;
    	    cout<<"Enter the Password of Account:"<<endl;
	        cin>>password;
	        option=0;
			for(int i=0;i<=2;i++){
	        	if(name==names[i] && password==passwords[i]){
					 while(option!=5){
    system("cls");
    cout<<"Select one Option"<<endl;
	cout<<"1). Draw Money"<<endl;
	cout<<"2). Deposite Money"<<endl;
	cout<<"3). Transfer Money into Any Account"<<endl;
	cout<<"4). Check Money"<<endl;
	cout<<"5). Log out"<<endl;
	cin>>option;
    if(option==1){
    	int draw=0;
    	system("cls");
    	cout<<"Enter Amount of Money for Drawing "<<endl;
    	cin>>draw;
    	if(balance[i]>draw){
		  cout<<"You Drawed Money"<<endl;
		  balance[i]=balance[i]-draw;
	    }
    	else
    	cout<<"You Can't Draw Money "<<endl;
    	cout<<"Press any key to Go Back"<<endl;
		getch();
	}
	if(option==2){
    	int deposite=0;
    	system("cls");
    	cout<<"Enter Amount of Money for Depositing "<<endl;
    	cin>>deposite;
    	balance[i]=balance[i]+deposite;
    	cout<<"Your Money is Deposite"<<endl;
    	cout<<"Press any key to Go Back"<<endl;
		getch();
    }
    if(option==3){
    	system("cls");
    	string name;
    	int password,money;
    	cout<<"Enter the Account Name Where you Send Money"<<endl;
    	cin>>name;
    	cout<<"Enter the Password of Account"<<endl;
	    cin>>password;
	    for(int j=0;j<=2;j++){
	    	if(i!=j && name==names[j] && password==passwords[j]){
	    		cout<<"Enter the Money: ";
	    		cin>>money;
	    		if(balance[i]>money){
	    		balance[j]=balance[j]+money;
	            balance[i]=balance[i]-money;
				}
			}
		}
	}
	if(option==4){
		system("cls");
		cout<<"Your Balance is: "<<balance[i]<<endl;
    	cout<<"Press any key to Go Back"<<endl;
		getch();
	}
  }	
				}
			}
		}
	}
}
