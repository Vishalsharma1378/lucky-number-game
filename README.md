# lucky-number-game
#include <stdio.h>

int main() {
int secretnum ,gueesnum;
secretnum= 4;
int i;
int guesslimit =3;
for(i=1 ; i<=guesslimit ;i++)
{
   printf("your lucky num%d :=",i);
     scanf("%d",&gueesnum);
     if(gueesnum == secretnum){
         printf("you won");
         break;
     }
    
    
}
if(gueesnum!=secretnum){
    printf("you lose");
}


    return 0;
}
