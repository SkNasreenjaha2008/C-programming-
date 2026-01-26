#include <stdio.h> 
int main()
{ 
    int marks; 
    printf("Enter marks: "); 
    scanf("%d", &marks); 
    if (marks >= 90) 
    { 
        printf("Grade A+\n"); 
    }
    else if (marks >= 75)
    { 
        printf("Grade A\n"); 
    }
    else
    {
        printf("Grade B\n"); 
    } 
    return 0; 
}

output: Enter marks: 76 
Grade A

