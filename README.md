# Array-Dalam-C-Pengiriman-Parameter-1
    #include<stdio.h>

    void cetak_mundur(char S[]){
    int i, n;
    for(n=0;n<S[n];n++);
    printf("panjang array = %d\n", n);
    for(i=n-1;i>=0;i--){
        printf("%c", S[i]);
    }
    }

    void main(){
    char str[50]="antonius rachmat chrismanto";
    cetak_mundur(str);
    }
   ![img](https://raw.githubusercontent.com/BambangPriam/Array-Dalam-C-Pengiriman-Parameter-1/master/Pengiriman%20Parameter%201.png)
