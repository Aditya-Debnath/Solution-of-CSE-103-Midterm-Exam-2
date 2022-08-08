# Solution-of-CSE-103-Midterm-Exam-2
The solution of CSE 103 Midterm Exam at 07 August 2022

Question 1.
1.1

#include<stdio.h>
int main()
{

    float a[]= {1,2,3,4,5,6,7,8,9,10};
    printf("%d", sizea[]/sizea[0][0]); 

}

Ans :- 

size[]/sizea[0][0]
= 4*4/4
= 4
Ans = 4

1.2

#include<stdio.h>
int main()
{

    int marks[10], i, n, sum = 0, Average ;
    scanf("%d",&n);

    Ans:-
    //                                                      {{ "//" this thing for special mark }} 
    for(i=0;i<n;i++)
    {
        scanf("%d",marks[i]);
        sum = sum + marks[i];
    }
    printf("%d",sum);
    //

    Average = sum/n;
    printf("%d",Average);
    
}

1.3

Whats wrong with this code?
Find the problem.

#include<stdio.h>
int()
{

    int i;
    int A[3][4] = {
                  {1,2,3,4,5,6}
                  {7,8,9,10,11}
                  {12.13.14.15}
                  };
    for(i=0;i<3;i++)
    {
    for(j=0;j<4;j++)
    {
    printf("%d",A[i][j]);
    }
    
}

Ans:-

Beshi value chilo, array size a tulonay. 

Array 3*4=12 < 15

Question 2.
2.1

#include<stdio.h>
int main()
{

     int i, j;
     for(i=0;i<7;i++)
     {
     for(j=0;j<i;J++)
     {
     printf("%d", i*j);
     }
     
}

i)
Ans:- 1 time.
ii)
Ans:- 1 time.
iii)
Ans:- 0 6 12 18 24 30.........

2.2
Just like,

Input
a[9] = 1,2,3,4,5,6,7,8,9.
Output
E[4] = 2 4 6 8.
O[5] = 1 3 5 7 9.

Ans:-

#include<stdio.h>
int main()
{

    int A[5],E[5],O[5];           //  The amount of Array size and value is independent.
    int count = 0;
    int down = 0;
    for(int i = 0; i < 5 ; i++)   // You can take any amount of size(It should be bigger then A[size])
        {
        printf("index %d : ", i);
        scanf("%d", &A[i]);
        }
        for(int i = 0; i<5;i++)
        {
        if(A[i] % 2 == 0)
        {
            E[count] = A[i];
            count += 1;
        }
        else
        {
            O[down] = A[i];
            down += 1;
        }
    }
    printf("The Even number in array : \n");
    printf("E[%d] = ",count);
    for(int i =0;i<count;i++)
    {
        printf("%d\t",E[i]);
    }
    printf("\nThe odd number in array : \n");
    printf("O[%d] = ",down);
    for(int i = 0;i<down;i++)
    {
        printf("%d\t",O[i]);
    }

    return 0;
}

2.3 Not solved

    int v = 4, a, n, A[10] = {1,2,3,4,5,6,7,8,9};
    3*3 matrix
    [i][j] - [v-(a-1)}   Some thing like this.

    Ans:- 404 ; If you have sharp memory just like "Sherlock Holmes", then please inform me about the question. :)

Question 3.

3.1

    #include<stdio.h>
    int main()
    {
    int A[3][3] = {1,2,3,4,5,6,7,8,9};
    printf("%d %d",a[0][0], a[3][2]);
    }

Ans:-
Try yourself.

3.2

1
12
123
1234
12345

Ans:-

Please wait for some time. IDK.

3.3
i) 3*3 matrix's only coloum sum 

Ans:-

#include<stdio.h>
int main()
{

    int i,j,a[3][3];
    int sum = 0;
    int coloum_sum = 0;
    for(i=0;i<3;i++)
    {
        for(j=0;j<3;j++)
        {
            scanf("%d",&a[i][j]);
        }
    }
    for(i=0;i<3;i++)
    {
        sum=0;
        for(j=0;j<3;j++)
        {
            sum = sum + a[j][i];
        }
        printf("The Sum of Column = %d\n",sum);
    }
    return 0;

}

ii)99 100

Ans:- wait for later.











