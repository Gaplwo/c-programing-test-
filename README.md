#define_CRT_SECURE_NO_WARNINGS
#include <stdio.h>
#include <cs50.h>
// #include <string.h>

int factorialof(int num);

int main()
{
    int num, factorial=0;
    printf("Plase Enter a Number: ");
    scanf("%d",&num);
    factorial = factorialof(num);
    printf("the factoril of %d is (\'%d\') \n", num, factorial);

}
int factorialof(int num)
{
    int fact =1;
    while(num > 0)
    {
        fact = fact *num;
        num --;
    }
    return fact;
}

    unsigned int getname(char[]);
    char name;
    unsigned int length;
    printf("Plase Enter Yuor Name :");
    gets(name);
    scanf("%s",&name);
    getname(&name);
    length = getname(&name);

    printf("yuor name length is :%d", length);





}
unsigned int getname(char name[55])
{
    strubr(name);
    return strlen(name);
}


void getName(void);
    getName();


}
    void getName(void)
    {
        char name[55];
        printf("Enter Yuor Name : ");
        // gets(name);
        scanf("%s",name);
        printf("\nYuor Naame is %s \n: ",name);



int add(int, int, int);

  int y, x, m;
    int getAge(int birth, int year, int get)
    {
        printf("Plase Enter birthdaey:");
        scanf("%d",&birth);
        printf("Enter the year now:");
        scanf("%d",&year);
        get = birth - year;
        return birth;
     }

    int a, b, c;
    printf("Plase Enter Two Numbers\n");
    scanf("%d\n %d",&a ,&b);
    c = add(a,b);
    add(a,b);
    printf("%d\n",c);
}
void add(int y, int x)
{
    printf("%d + %d = %d\n",y,x, y+x);
}





int salary[5];
    printf("plase enter asalary mangment:");
    scanf("%d",&salary[0]);
    printf("plase enter asalary ddident fly:");
    scanf("%d",&salary[1]);
    printf("plase enter asalary accaontent:");
    scanf("%d",&salary[2]);
    printf("the salers of:%d\n",salary[0]);
    printf("the salers of:%d\n",salary[1]);
    printf("the salers of:%d\n",salary[2]);


int rdr1[3][2] = {{22,33},{56,77},{43,66}};
    printf("aray number 1 of rwo 2 is:%d\n" ,rdr1[1][1]);


int rdr[5] = {12,33,23,35,55};
    printf("the array number 1:%d\n", rdr[0]);
    printf("the array number 2:%d\n", rdr[1]);
    printf("the array number 3:%d\n", rdr[2]);
    printf("the array number 4:%d\n", rdr[3]);
    printf("the array number 5:%d\n", rdr[4]);



int num1, num2 ,num3;
    int sum;
    double avrage;
    printf("plase enter anumber 1:");
    scanf("%d", &num1);
    printf("plase enter anumber 2:");
    scanf("%d", &num2);
    printf("plase enter anumber 3:");
    scanf("%d", &num3);
    sum= num1+num2+num3;
    avrage= sum / 3.0;
    printf("the avrage number is \"%f\" \n",avrage);



 int num1, num2, sum;
    printf("plase enter the first number:");
    scanf("%d",&num1);
    printf("plase enter the sconde number:");
    scanf("%d",&num2);
    sum = num1 +num2;
    printf("the sum numbers is :\"%d\" \n",sum);
    printf("%d+%d=%d\n",num1 ,num2 ,sum);


    int num1;
    int num2;
    printf("Plase Enter a Number 1:");
    scanf("%d",&num1);
    printf("Plase Enter a Number 2:");
    scanf("%d",&num2);
    printf("The Sum Number Is:%d\n",num1 + num2);
    char std;
    unsigned int id;
    float gards;
    printf("Plase Enter student first charcter?");
    scanf("%c",&std);
    printf("Plase enter a ID?\n");
    scanf("%d",&id);
    printf("plase enter a grade?\n");
    scanf("%f",&gards);
    printf("the first charcter is :    %c\n",std);
    printf("the id is %d\n",id);
    printf("the grades is %f\n",gards);
    char r ='A';
    char t ='Z';
    char y ='a';
    char u ='z';
    int scan;
    double h=1.1;
    printf("hello world %d\n",r);
    printf("hello world %d\n",t);
    printf("hello world %d\n",y);
    printf("hello world %d\n",u);
    printf("hello world %f\n",h);
    printf("Plase Enter anumber:");
    scanf("%d",&scan);

    for(int i=0; i<=5; i++)
    {
        printf("welcome %i\n",i,scan);

