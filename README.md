//Keeping the record of an employee using structures..
#include <stdio.h>
struct employee_data{
    int salary;
    char name[20],id[20],dateofbirth[30];
}s1;
int main() {
    printf("Enter in as the following sequence :\n\nName\nId\nDate of Birth\nMonthly Salary\n\n");
    gets(s1.name);
    gets(s1.id);
    gets(s1.dateofbirth);
    scanf("%d",&s1.salary);
    printf("The Employee details are as follows :\nName= ");
    puts(s1.name);
    printf("Id= ");
    puts(s1.id);
    printf("Date of Birth= ");
    puts(s1.dateofbirth);
    printf("Monthly salary= %d",s1.salary);
    
    return 0;
}
