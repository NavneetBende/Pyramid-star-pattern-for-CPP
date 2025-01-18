Pyramid star pattern
To print the Pyramid star pattern we need two loop. first is outer loop and second is inner loop.

first loop that is the outer loop works on the row or line and the another loop that is inner loop works on the column mean how many start you want to put in the single line.so here we need to now proper working of the loop that we can easily make a desired pattern.

Now we will discuss all possible star pattern using java. 


1. Write a Program to print the following pattern.
* 
* * 
* * * 
* * * * 
* * * * *
Working
Step 1- first you need to initialize two variable for loop.

Step 2- the first loop  for the row.

Step 3-  the second loop work for the column.

Step 4- now print the *.

Step 5- now out side of loop, put new line.

Step 5- stop.

C	JAVA	Python 1	Python 2	C++
#include<iostream.h>
using namespace std;
int main()
{
    int i, j;
    
    for(i=1; i<=5; i++)
    {
        for(j=1; j<=i; j++)
        {
            cout<<"* ";
        }
        
        cout<<"\n";
    }
    return 0;
}
2. Write a program to print the following pattern
* 
* * * 
* * * * * 
* * * * * * * 
* * * * * * * * *
C	JAVA	Python 1	Python 2	C++
#include<iostream>
using namespace std;
int main()
{
    int i, j, k=1;
    for(i=1; i<=5; i++)
    {
        for(j=1; j<=k; j++)
        {
            cout<<"* ";
        }
        
        cout<<endl;
        k = k + 2;
    }
    return 0;
}
3. Write a program to print the following pattern
        * 
      * * 
    * * * 
  * * * * 
* * * * *
C	JAVA	Python 1	Python 2	C++
#include<iostream>
using namespace std;
  
int main()  
{  
    int n,m=1;    
    for(int i=5;i>=1;i--)  
    {  
        for(int j=1;j<=i-1;j++)  
        {  
            cout<<" ";  
        }  
        for(int k=1;k<=m;k++)  
        {  
            cout<<"*";  
        }  
        cout<<endl;  
        m++;  
     }  
     return 0;  
}  
4. Write the code to print the following patter
                * 
            * * * 
        * * * * * 
    * * * * * * * 
* * * * * * * * *
C	JAVA	Python 1	Python 2	C++
#include<iostream>
using namespace std;
 
int main()  
{  
    int i,j,k=16,s=1;

    for(i=0;i<5;i++)
    {
        for(j=0;j<k;j++)
        {
            cout<<" ";
        }       
        k=k-4;        
        for(j=1;j<=s;j++)
        {
            cout<<"* ";
        }            
        s=s+2;
        cout<<endl;
    }
    return 0;
}  
5. Write the code to print the following pattern.
    *
   ***
  *****
 *******
*********
C	JAVA	Python 1	Python 2	C++
#include<iostream>
using namespace std;
 
int main()  
{  
    int i,j,k=0,row=5;
    //this loop work on the row
    for (i=1;i<=row;i++)
    {
        //this loop work for both the space and print *
        for(j=1;j<=row-i;j++)
        cout<<" ";
        //until value of the k is not equal to 2*i-i, it print star
        while(k!=(2*i-1))
        {
            cout<<"*";
            k++;
        }
        k=0;
        cout<<endl;
    }
    return 0;
}  
