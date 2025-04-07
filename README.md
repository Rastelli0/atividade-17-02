#include <stdio.h>
*int main() {
int vet[10];
int i;
for( i = 0; i < 10; i++){
printf("Digite o n-%d do vetor ", i);
scanf("%d",&vet[i]);

}

for(int i = 0; i < 10; i++){
    printf("vetores: %d ", vet[i]);
    
    }

return 0;
}
//--------------------------------------------------------------------------------------------------------------------------------------------
//ex2
//--------------------------------------------------------------------------------------------------------------------------------------------
int main() {
    int vet[10];
    int vet2[10];
    int i;

    for( i = 0; i < 10; i++){
    printf("Digite o n-%d do vetor ", i);
    scanf("%d",&vet[i]);
    
    }
    
    for(int i = 0; i < 10; i++){

       vet2[i] = vet[i] * 2;
       
        }

    for(int i = 0; i < 10; i++){

        printf("vetores novos: %d \n", vet2[i]);
    
        }

  


    return 0;
}
//--------------------------------------------------------------------------------------------------------------------------------------------
//ex3
//--------------------------------------------------------------------------------------------------------------------------------------------
int main() {
    int vet[10];
    int vet2[10];
    int vet3[10];
    int i;

    for( i = 0; i < 10; i++){
    printf("Digite o n-%d do vetor ", i);
    scanf("%d",&vet[i]);
    
    }
    
    for(int i = 0; i < 10; i++){

       vet2[i] = vet[i] * 2;
       
        }

    for(int i = 0; i < 10; i++){

            vet3[i]= vet[9-i];
            
             }
     for(int i = 0; i < 10; i++){

                printf("vetores original: %d \n", vet[i]);
            
                }

    for(int i = 0; i < 10; i++){

        printf("vetores dobrados: %d \n", vet2[i]);
    
        }

        for(int i = 0; i < 10; i++){

            printf("vetores inverso: %d \n", vet3[i]);
        
            }
  


    return 0;
}
//--------------------------------------------------------------------------------------------------------------------------------------------
//ex4
//--------------------------------------------------------------------------------------------------------------------------------------------
int main() {
    int vet[10];
    int vet2[10];
    int vet3[10], 
    int soma = 0;
    float media;

    int i;

    for( i = 0; i < 10; i++){
    printf("Digite o n-%d do vetor ", i);
    scanf("%d",&vet[i]);
    
    }
//dobro
    for(int i = 0; i < 10; i++){

       vet2[i] = vet[i] * 2;
       
        }
//inverso
    for(int i = 0; i < 10; i++){

            vet3[i]= vet[9-i];
            
             }
//media
  for(int i = 0; i < 10; i++){

            soma += vet[i];
                
                 }
                 media = soma / 10.0;
     for(int i = 0; i < 10; i++){

                printf("vetores original: %d \n", vet[i]);
            
                }

    for(int i = 0; i < 10; i++){

        printf("vetores dobrados: %d \n", vet2[i]);
    
        }

        for(int i = 0; i < 10; i++){

            printf("vetores inverso: %d \n", vet3[i]);
        
            }
  
            printf("media dos vetores: %d \n", media);

    return 0;
}
//--------------------------------------------------------------------------------------------------------------------------------------------
//ex5
//--------------------------------------------------------------------------------------------------------------------------------------------
int main() {
    int vet[10];
    int vet2[10];
    int vet3[10];
    int soma = 0, maior, menor;
    float media;

    int i;

    for( i = 0; i < 10; i++){
    printf("Digite o n-%d do vetor ", i);
    scanf("%d",&vet[i]);
    
    }

    maior = menor = numeros[0];

//dobro e maior e menor
     for (int i = 0; i < 10; i++) {
        vet2[i] = vet[i] * 2;
        soma += vet[i];

        // Atualiza maior e menor
        if (vet[i] > maior) {
            maior = vet[i];
        }
        if (vet[i] < menor) {
            menor = vet[i];
        }
    }
//inverso
    for(int i = 0; i < 10; i++){

            vet3[i]= vet[9-i];
            
             }
//media
  for(int i = 0; i < 10; i++){

            soma += vet[i];
                
                 }
                 media = soma / 10.0;
     for(int i = 0; i < 10; i++){

                printf("vetores original: %d \n", vet[i]);
            
                }

    for(int i = 0; i < 10; i++){

        printf("vetores dobrados: %d \n", vet2[i]);
    
        }

        for(int i = 0; i < 10; i++){

            printf("vetores inverso: %d \n", vet3[i]);
        
            }
  
            printf("media dos vetores: %d \n", media);
            printf("O maior numero e: %d\n", maior);
            printf("O menor numero e: %d\n", menor);

    return 0;
}
//--------------------------------------------------------------------------------------------------------------------------------------------
//ex6
//--------------------------------------------------------------------------------------------------------------------------------------------
int main() {
    int vet[10];
    int vet2[10];
    int vet3[10];
    int soma = 0, maior, menor, pares = 0;
    float media;

    int i;

    for( i = 0; i < 10; i++){
    printf("Digite o n-%d do vetor ", i);
    scanf("%d",&vet[i]);
    
    }

    maior = menor = numeros[0];

//dobro e maior e menor
     for (int i = 0; i < 10; i++) {
        vet2[i] = vet[i] * 2;
        soma += vet[i];

        // Atualiza maior e menor
        if (vet[i] > maior) {
            maior = vet[i];
        }
        if (vet[i] < menor) {
            menor = vet[i];
        }
        if (vet[i] % 2 == 0) {
            pares++;
        }
    }
//inverso
    for(int i = 0; i < 10; i++){

            vet3[i]= vet[9-i];
            
             }
//media
  for(int i = 0; i < 10; i++){

            soma += vet[i];
                
                 }
                 media = soma / 10.0;
     for(int i = 0; i < 10; i++){

                printf("vetores original: %d \n", vet[i]);
            
                }

    for(int i = 0; i < 10; i++){

        printf("vetores dobrados: %d \n", vet2[i]);
    
        }

        for(int i = 0; i < 10; i++){

            printf("vetores inverso: %d \n", vet3[i]);
        
            }
  
            printf("media dos vetores: %d \n", media); 
            printf("O maior numero e: %d\n", maior);
            printf("O menor numero e: %d\n", menor);
            printf("Quantidade de numeros pares: %d\n", pares);

    return 0;
}
