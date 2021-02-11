#include <stdio.h>

int main(void)
{
    int score[10][6];
    int total;
    double avg;
    int i,j;
    
    for (i = 0; i < 10; i++)
    {
        printf("6ㅈㅓㄴㄱㅗㅇ ㄱㅗㅏㅁㅗㄱㅇㅡㅣ ㅈㅓㅁㅅㅜㄹㅡㄹ ㅇㅣㅂㄹㅕㄱ : ");
        for (j = 0; j < 6; j++)
        {
            scnaf("%d", &score[i][j]);
        }
    }
    
    return 0;
}
