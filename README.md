#include <stdio.h>

int main(void)
{
    int score[10][6];
    int total;
    double avg;
    int i,j;
    
    for (i = 0; i < 10; i++)
    {
        printf("6전공 과목의 점수를 입력 : ");
        for (j = 0; j < 6; j++)
        {
            scnaf("%d", &score[i][j]);
        }
    }
    
    for (i = 0; i < 10; i++)
    {
        total = 0;
        for (j = 0; j < 6; j++)
        {
            total += score[i][j];
        }
        avg = total / 4.5;
        printf("총점 : %d, 평균 : %.2lf\n", total, avg);
    }
    
    return 0;
}
