Coding by Akashdip Mahapatra

[![YouTube](https://yt3.ggpht.com/7tPHyFi7-QyTnhpc484ZzTuRp0fZSY-CUuykvzuKdKYIwt0fmw98SWMqwRy_7pZ6LQzEYJlvXA=s88-c-k-c0x00ffffff-no-rj-mo)](https://www.youtube.com/channel/UCxvmp634YDc41xCWOdvWqoQ)

<p align="left"> <img src="https://komarev.com/ghpvc/?username=akashdip2001&label=Profile%20views&color=0e75b6&style=flat" alt="akashdip2001" /> </p>

 🔭 I’m currently working on [**my web-site**](https://akashdip2001.github.io/linktree/)
 <h3 align="right">Connect with me:</h3>
 
<h1 align="right">AKASHDIP MAHAPATRA</h1>
<p align="right">

 <a href="https://akashdip2001.github.io/linktree/" target="blank"><img align="right" src="https://yt3.ggpht.com/7tPHyFi7-QyTnhpc484ZzTuRp0fZSY-CUuykvzuKdKYIwt0fmw98SWMqwRy_7pZ6LQzEYJlvXA=s88-c-k-c0x00ffffff-no-rj-mo" alt="akashdip2001" height="40" width="40" /></a>
<a href="https://linkedin.com/in/akashdip-mahapatra-330687204" target="blank"><img align="right" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="akashdip-mahapatra-330687204" height="30" width="40" /></a>
<a href="https://www.youtube.com/c/akash aot" target="blank"><img align="right" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="akash aot" height="30" width="40" /></a>


</p>
<br/>

---
# C-cording-Day_3
C cording Day Day_3 

![Assignments](https://user-images.githubusercontent.com/81384987/201528266-ff46a95b-45fb-42c9-a33a-9801e1b0b1ce.png)


---
1) Write a C program to swap two integers (without third variable).
```
 #include<stdio.h>
int main() {
    float A,B;
    printf("Enter the Value of A & B\n");
    scanf("%f %f",&A,&B);

    printf("The value before swap is %.2f & %.2f\n",A,B);  //%f = 2.6000000  & %.2f = 2.60
    A=A+B;
    B=A-B;
    A=A-B;
    printf("The value after  swap is %.2f & %.2f",A,B);   //%f = 2.6000000  & %.2f = 2.60
    
    return 0;
}

 ```
 ---
 2) Write a C program to check whether an input integer given by user is divisible by 4 or not (using if-else).
 ```
 #include<stdio.h>
int main() {
    int A;
    printf("Enter the Value of A\t");
    scanf("%d",&A);

    if(A%4==0){
        printf("input integer-%d is divisible by 4",A);
    }else{
         printf("input integer-%d is not divisible by 4",A);
    }
    
    return 0;
}
```
---
3) Write a C program to take a number from user and check whether the given number is positive or not.
  ```
#include<stdio.h>
int main() {
    int n;
    printf("Enter the Value of n\t");
    scanf("%d",&n);

    if(n>=1) //condition1 - all numbers "equal to 1 or greater than 1"
    {
         printf("input %d is positive (+)",n);
    }
    else if(n<0) //condition2 - all numbers "smaller than 0"
    {
         printf("input %d is negative (-)",n);
    }
    else // the remaining number after condition 1 & 2 is "0"
    {
         printf("input %d is neutral (0)",n);
    }
    
    return 0;
}
   ```
---
4) Write a C program to take a negative number from user and convert that negative number to equivalent positive number.  
```   
  #include<stdio.h>
int main() {
    int n;
    printf("Enter the neg. Value \t");
    scanf("%d",&n);

    n=-n;
    printf("Now the value is %d",n);
    
    return 0;
}
```   
---
5) Write a C program to take sides of a triangle from user and check whether the triangle is equilateral or not.
```
 #include<stdio.h>
int main() {
    float a,b,c;
    printf("Enter the side one-by-one \n");
    scanf("%f %f %f",&a,&b,&c);

    if((a==b)&&(a==c)){
        printf("It's an equilateral triangle");
        printf("\n\n     0\n    000\n   00000"); // just for fun
    }else if((a==b)||(a==c)){
        printf("It's an Isosceles triangle");
    }else if((a!=b)&&(a!=c)){
        printf("It's an Scalene triangle");
    }
    
    return 0;
}
```
![typesoftringals](https://user-images.githubusercontent.com/81384987/201532170-645a8e9c-c20a-4e65-9a7f-ce5cc09da5fd.jpg)
---
6) Write a C program to find the area of a triangle using this formula: <br/>
           -  √𝑠(𝑠 − 𝑎)(𝑠 − 𝑏)(𝑠 − 𝑐)
``` 
#include<stdio.h>
#include <math.h>

int main() {
    float a,b,c,s,A;
    printf("Enter the side one-by-one \n");
    scanf("%f %f %f",&a,&b,&c);
    
    s=(a+b+c)/2;
    A=sqrt(s*(s-a)*(s-b)*(s-c));
    printf("Area of Triangle Using Heron's Formula is %.2f",A);
    
    return 0;
}
 ```
 
![Screenshot from 2022-11-13 22-04-09](https://user-images.githubusercontent.com/81384987/201533023-5ebaff93-e998-4f38-9633-daeaea914f38.png)

 ---
 7) Write a C program to check Even or Odd.
 ```
 #include<stdio.h>
 int main()
 {
    int number;
    printf("Enter the number \t");
    scanf("%d",&number);
              
    if(number%2==0)
    {
      printf("It's a even number\n");
    }
      else
    {
       printf("It's a odd number\n");
    }
   return 0;
  }
```
---
8) Write a C program to check the input is divisible by 3 or not.
```
 #include<stdio.h>
 int main()
 {
   int number;
   printf("Enter the number \t");
   scanf("%d",&number);
              
   if(number%3==0)
   {
    printf("It's divisible by 3\n");
   }
   else
   {
    printf("It's not divisible by 3\n");
   }
  return 0;
 }
```
---
9) Write a C program to check the input integer is square root or not ( Don't take imaginary value).
```
 #include<stdio.h>
 #include<math.h>
 int main()
 {
   int num;
   int iVar;
   float fVar;
      
   printf("Enter an integer number: ")
   scanf("%d",&num);  // example you enter 8
       
   fVar= sqrt((double)num); // double is use for - store the full floating value. example: 2.82842 🤔
          
   iVar = fVar;   // example: fVar= 2.82842 but iVar= 2 ( because "int iVar" )- it's save only integers 😁
   if(iVar==fVar)   // '==' chack fVar & iVar is equal or not , Example 2.82842 ≠ 2 😎
   { 
     printf("%d is a perfact squre.",num);
    } else {
      printf("%d is not a perfact aqure.",num);
     }
 return 0;
 }
```
---
10) Write a C program to swap two integers (with third varible).
```
 #include<stdio.h>
 int main() 
 {
  int a,b,temp;
       
  printf("Enter the value of A and B ");
  scanf("%d %d",&a,&b);  // Example A=4 , B=5
       
  printf("The value of A & B before is %d & %d \n",a,b);
       
  temp=a;  // value of A is copy to Temp -- Temp = 4 & A= empty
  a=b;     // value of B is copy to A  --  A = B = 5 & B= empty
  b=temp;  // value of Temp is copy to B -- B = Temp 
       
  printf("The value of A & B afterd is %d & %d \n",a,b);
       
 return 0;
}
```
![swap](https://user-images.githubusercontent.com/81384987/198898182-1d4636d1-8ed6-4e6c-9a75-66e44bc6272e.jpg)

<a href="https://akashdip2001.github.io/C-cording-Day_1/" class="previous">&laquo; Previous</a> <br/>
<a href="https://akashdip2001.github.io/404/" class="next">Next &raquo;</a>
<a href="https://akashdip2001.github.io/linktree/" target="blank"><img align="right" src="https://yt3.ggpht.com/7tPHyFi7-QyTnhpc484ZzTuRp0fZSY-CUuykvzuKdKYIwt0fmw98SWMqwRy_7pZ6LQzEYJlvXA=s88-c-k-c0x00ffffff-no-rj-mo" alt="akashdip2001" height="40" width="40" /></a>
<a href="https://www.youtube.com/c/akash aot" target="blank"><img align="right" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="akash aot" height="30" width="40" /></a>

