    #include <stdio.h>
    #include <stdlib.h>

    int main() {
    
    int dogumyili;
    int yil;
    int yas;

    printf("Lutfen dogum yilinizi giriniz ");
    scanf("%d", &dogumyili);

    printf ("Gunumuz yilini giriniz ");
    scanf(" %d", &yil);

    yas= (yil-dogumyili);

    printf ("-------------------\n");
    printf ("Hesaplanan yasiniz= %d", yas);
    
    return 0; 
    }

