Coding by Akashdip Mahapatra

[![YouTube](https://yt3.ggpht.com/7tPHyFi7-QyTnhpc484ZzTuRp0fZSY-CUuykvzuKdKYIwt0fmw98SWMqwRy_7pZ6LQzEYJlvXA=s88-c-k-c0x00ffffff-no-rj-mo)](https://www.youtube.com/channel/UCxvmp634YDc41xCWOdvWqoQ)

<p align="left"> <img src="https://komarev.com/ghpvc/?username=akashdip2001&label=Profile%20views&color=0e75b6&style=flat" alt="akashdip2001" /> </p>

 🔭 I’m currently working on [**my web-site**](https://akashdip2001.github.io/linktree/)
 <h3 align="right">Connect with me:</h3>
 
<h1 align="right">AKASHDIP MAHAPATRA</h1>
<p align="right">
<a href="https://akashdip2001.github.io/linktree/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="akashdip-mahapatra-330687204" height="30" width="40" /></a>
</p>

| <a href="https://akashdip2001.github.io/C-coding-Day_2/" class="previous">&laquo; Previous Day</a> <br/> |
|--------------------------------------------------------------------------------------|
| <a href="https://akashdip2001.github.io/404/" class="next">Next Day &raquo;</a> |

<br>
<a href="https://www.youtube.com/c/akash aot" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="akash aot" height="30" width="40" />My YouTube Channel</a>
<br>
<br>


---
# C-coding-Day_3
---

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
 7) Write a C program to take two integers from user and check whether the given integers are equal or not.
 ```
 #include<stdio.h>

 int main() {
    int a,b;
    printf("Enter two integers one-by-one \n");
    scanf("%d %d",&a,&b);
    
    if(a==b){
        printf("\nTwo integers are equal (%d=%d)",a,b);
    }else{
        printf("\nTwo integers are not equal (%d≠%d)",a,b);
    }
    return 0;
}
```
---
8) Write a C program to find maximum between two integers given by user.
```
 #include <stdio.h>

int main()
{
    int num1, num2;


    printf("Enter two numbers:\n");
    scanf("%d%d", &num1, &num2);


    if(num1 > num2)
    {
        printf("%d is maximum", num1);        
    }
    else if(num2 > num1)
    {
        printf("%d is maximum", num2);
    }
    else if(num1 == num2)
    {
        printf("Both are equal");
    }

    return 0;
}
```
---

| <a href="https://akashdip2001.github.io/C-coding-Day_2/" class="previous">&laquo; Previous Day</a> <br/> |
|--------------------------------------------------------------------------------------|
| <a href="https://akashdip2001.github.io/404/" class="next">Next Day &raquo;</a> |

---

<a href="https://akashdip2001.github.io/linktree/" target="blank"><img align="right" src="https://yt3.ggpht.com/7tPHyFi7-QyTnhpc484ZzTuRp0fZSY-CUuykvzuKdKYIwt0fmw98SWMqwRy_7pZ6LQzEYJlvXA=s88-c-k-c0x00ffffff-no-rj-mo" alt="akashdip2001" height="40" width="40" /></a>
<a href="https://www.youtube.com/c/akash aot" target="blank"><img align="right" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="akash aot" height="30" width="40" /></a>

