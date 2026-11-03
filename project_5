/******************************************************************************

                            Online C Compiler.
                Code, Compile, Run and Debug C program online.
Write your code in this editor and press "Run" button to compile and execute it.

*******************************************************************************/

#include <stdio.h>

void main()
{
    FILE *fp;
    char name[300];


    // 1. Writing data into file
    fp = fopen("mohammed aarif.txt", "w");

    if (fp == NULL)
    {
        printf("File cannot be opened");
        return;
    }

    fprintf(fp, "c program class is very good and it was nice and the sir teach very well");

    fclose(fp);

    printf("Data Written successfully\n"); 

    // 2. Appending data into file
    fp = fopen("student.txt", "a");

    if (fp == NULL)
    {
        printf("File cannot be opened");
        return;
    }

    fprintf(fp, "\nWelcome to File Handling");

    fclose(fp);

    printf("Data appended successfully\n");


    // 3. Reading data from file
    fp = fopen("student.txt", "r");

    if (fp == NULL)
    {
        printf("File cannot be opened");
        return;
    }

    printf("\nFile Contents:\n");

    while (fgets(name, sizeof(name), fp) != NULL)
    {
        printf("%s", name);
    }

    fclose(fp);

}
