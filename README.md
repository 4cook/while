#include <stdio.h>
int main(){
    int i=1;
    while(i<=100){


        printf("thiago %i\n",i);
        i=i+1;

    }
}


-------------------------------------------------------------------------------------------------

#include <stdio.h>
int main(){
float x, soma;
while(x!=0){//Enquanto x nao for 0
  scanf("%f",&x);
  soma = soma+x;//acumula x em soma
}
printf("Resultado:%.1f",soma);
}

------------------------------------------------------------------------------------
#include <stdio.h>
int main(){
float x, soma,c,media;
while(x!=0){//Enquanto x nao for 0
  scanf("%f",&x);
  soma = soma+x;//acumula x em soma
  c=c+1;

}
media=soma/c;
printf("Resultado:%.1f",soma);
printf("\nmedia%f",media);
}
