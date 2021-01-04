# calculator

Hello, Everyone
Today, I'll show my code of calculator.
It is very exciting and interesting to make this.

So, my code is

```#include<bits/stdc++.h>
#include<stdlib.h>
using namespace std;

int main(){
    int p = 100;
    while(p>0){
    long long int n;
    printf("Please Enter the No. of digits after decimal that your answer contains\n");
    printf("__________________________________________________________\n");
    scanf("%d",&n);
    printf("Please Enter Two numbers from you want to perform mathematical operation\n");
    printf("INTEGERS :- \n");
    double a,b;
    scanf("%lf%lf",&a,&b);
    printf("______________________________________________________________\n");
    printf("INSTRUCTIONS\n");
    printf("PLEASE ENTER CORRESPONDING NUMBER FOR MATHEMATICAL OPERATION THAT YOU WANT TO PERFORM\n");
    printf(" ___________________________________________________________________\n");
    printf("|   Addition : +,  Subtraction : -, Multiplication: *, Division : / |\n");
    printf("|     |               |                |                |           |\n");
    printf("|     1               2                3                4           |\n");
    printf("|___________________________________________________________________|\n");
    int c;
    double d;
    scanf("%d",&c);
    system("cls");
    if(c==1){
        d = a+b;
         cout << fixed << setprecision(n) << d<<endl;
    }
    else if(c==2){
        d = a-b;
         cout << fixed << setprecision(n) << d<<endl;
    }
    else if(c==3){
        d = a*b;
         cout << fixed << setprecision(n) << d<<endl;
    }
    else if(c==3){
        d = a/b;
         cout << fixed << setprecision(n) << d<<endl;
    }
    printf("PRESS 1 IF YOU WANT TO CONTINUE YOUR CALCULATIONS??\n");
    int q;
    scanf("%d",&q);
    if(q==1){
    while(q==1){
    a = d;
    printf("PLEASE ENTER NEXT INTEGER THAT YOU WANT TO PERFORM OPERATION WITH YOUR ANSWER\n");
    double m;
    scanf("%lf",&m);
    int c;
    double d;
        printf("PLEASE ENTER CORRESPONDING NUMBER FOR MATHEMATICAL OPERATION THAT YOU WANT TO PERFORM\n");
    printf(" ___________________________________________________________________\n");
    printf("|   Addition : +,  Subtraction : -, Multiplication: *, Division : / |\n");
    printf("|     |               |                |                |           |\n");
    printf("|     1               2                3                4           |\n");
    printf("|___________________________________________________________________|\n");
    scanf("%d",&c);
    system("cls");
    if(c==1){
        d = a+m;
         cout << fixed << setprecision(n) << d<<endl;
    }
    else if(c==2){
        d = a-m;
         cout << fixed << setprecision(n) << d<<endl;
    }
    else if(c==3){
        d = a*m;
         cout << fixed << setprecision(n) << d<<endl;
    }
    else if(c==3){
        d = a/m;
         cout << fixed << setprecision(n) << d<<endl;
    }
    printf("PRESS 1 IF YOU WANT TO CONTINUE YOUR CALCULATIONS??\n");
    scanf("%d",&q);
    if(q==1){}
    else{printf("THANKS FOR USING\n");
        system("cls");
        break;}
      }
      }
    else{printf("THANKS FOR USING\n");
       system("cls");
        break;
        }

     p--;
    }
return 0;
}
```


Don't Forget to star if you love my work. You can use it anywhere if you want.
