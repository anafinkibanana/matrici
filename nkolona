//Elementite na kvadratna matrica posle n-tata kolona da se podredat pod n-tiot red.
#include <stdio.h>

int main()
{
    int a[100][100], b[100][100], n, i, j, k, m;
    scanf("%d", &n);
    for(i=0; i<n; i++){
        for(j=0; j<n*2; j++){
            scanf("%d", &a[i][j]);
        }
    }
    
    for(j=0, m=0; j<n; j++, m++){
        for(i=0, k=0; i<n; i++, k++){
            b[k][m] = a[i][j];

        }
     }
     
     for(j=n, m=0; j<n*2; j++, m++){
         for(i=0, k=n; i<n; i++, k++){
             b[k][m] = a[i][j];
         }
     }
   for(k=0; k<n*2; k++){
        for(m=0; m<n; m++){
            printf("%d ", b[k][m]);
        }
        printf("\n");
    }

    return 0;
}
