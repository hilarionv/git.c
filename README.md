
#include <stdio.h>
int main (){
 int n , i , j;
 int M ;
 int c= 0 ;

do {
        printf("Saisissez le nbre d'entier positif que vous vouliez : ");
        scanf("%d", &n);
    } while (n < 0);


    for (i=1 ; i<n ; i++){
       printf ("entrez la valeur");
       scanf ("%d", &n);
        if (n%i==0)
            c++;
  M= c/n ;

    }
printf ("la moyenne  des entiers pairs est : %d \n", M);
