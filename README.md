# RA2111013010056-Simple-Result-System
#include <stdio.h>
#include <conio.h>
int main()
{
    int marks,i;
    /* Read student marks */
    printf("Enter the marks (in percentage ) of Student:");
    scanf("%d",&marks);
    /* display result */
    if(marks < 40)
    {
        for(i=0;i<40;i++)
        printf("_");printf("\n\n");
        printf("Result = Failed\n");
        for(i=0;i<40;i++)
        printf("_");printf("\n\n");
    }
    else
    {
        for(i=0;i<40;i++)
        printf("_");printf("\n\n");
        printf("Result = Passed\n");
        for(i=0;i<40;i++)
        printf("_");printf("\n\n");
    }
    system("pause");
    return 0;
}
