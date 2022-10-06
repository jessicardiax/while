#include <stdio.h>
 int main()
 {
float N1,N2, M;
int num;
printf("informe 1p/ continuar e 2p/ para sair: ");
scanf ("%d",&num);
while (num==1){
    printf("digite as 2 notas:");
    scanf("%f%f",&N1,&N2);
    M= (N1+N2/2);
    printf("media %f",M);
    printf("sua média é:");
}
}
