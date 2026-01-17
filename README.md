# C-Programming

# 1.HELLO WORLD

#include<stdio.h>
void main(){
  printf("HELLO WORLD\n");
}

# 2.ARITHMETIC OPERATOR

#include<stdio.h> 
void main()
{
  int a=5,b=10; 
  printf("a+b=%d\n",a+b); 
  printf("a-b=%d\n",a-b); 
  printf("a*b=%d\n",a*b); 
  printf("a/b=%d\n",a/b); 
  printf("modulus=%d\n",a % b); 
  printf("+a=%d\n",+a); 
  printf("-a=%d\n",-a);
}

# 3.RELATIONAL OPERATOR

#include<stdio.h> 
void main()
{
  int a=10,b=100;
  printf("a<b=%d\n",a<b); 
  printf("a>b=%d\n",a>b); 
  printf("a<=b=%d\n",a<=b); 
  printf("a>=b=%d\n",a>=b); 
  printf("a==b=%d\n",a==b); 
  printf("a!=b=%d\n",a!=b);
}

 # 4.LOGICAL OPERATOR

#include <stdio.h> 
void main(){
  int a=90,b=50;
  /* 
  printf("(a<b)&&(a>b)=%d\n",(a<b)&&(a>b));
  printf("(a<b)||(a>b)=%d\n",(a<b)||(a>b)); 
  printf("!a=%d\n",!a);
  printf("(a>=b)&&(a>b)=%d\n",(a>=b)&&(a>b));
  printf("(a>b)||(a<b)=%d\n",(a>b)||(a<b)); printf("!b=%d\n",!b);
  */
  
  printf("10&&-10=%d\n",10&&-10);
  printf("1 && 0 =%d\n",1 && 0);
  printf("10 ||-10=%d\n",(10)||(-10));
}
 
# 5.ASSIGNMENT OPERATOR

#include<stdio.h> 
void main()
{
  int a=30,b=40; 
  printf("a+=b	%d\n",a+=b); 
  printf("a-=b	%d\n",a-=b); 
  printf("a*=b	%d\n",a*=b); 
  printf("a/=b	%d\n",a/=b); 
  printf("a%=b	%d\n",a%=b);
}

# 6.UNARY OPERATOR

#include<stdio.h> 
void main(){
  int a=23;
  printf("a++ = %d\n",a++); 
  printf("a-- = %d\n",a--); 
  printf("++a = %d\n",++a); 
  printf("--a = %d\n",--a);
}

# 7.UNARY 2

#include<stdio.h> 
void main()
{
  int a=10,b=10,c=10,d=10;
  printf("a++ = %d\n",a++); 
  printf("%d\n",a);
  printf("++b = %d\n",++b);
  printf("c-- = %d\n",c--);
  printf("--d = %d\n",--d);
}

# 8.conditional operator 

#include<stdio.h>
void main()
{
  int a=100,b=10;
  (a==b)?printf("a is equal to b"):printf("a is not equal to b");
}

# 9. Bitwise operator

#include<stdio.h> 
void main()
{
  char a=0x56,b=0x32,c; 
  c=a&b;
  printf("c=%x\n",c); 
  c=a|b; 
  printf("c=%x\n",c); 
  c=a^b; 
  printf("c=%x\n",c); 
  c=a;~b; 
  printf("c=%x\n",c); 
  c=a<<4;
  printf("c=%x\n",c); 
  c=a>>5;
  printf("c=%x\n",c);
}

# 10.comma operator 

#include <stdio.h> 
void main(){
  int a,b,z; 
  z=(a=20,b=30,a+b);
  printf("%d",z);
}

# 11.address operator 

#include<stdio.h> 
void main()
{
  int a=100; 
  printf("%p\n",&a); 
  int b=1000; 
  printf("%p",&b);
}

# 12.operator precedence 

#include<stdio.h>
void main()
{
  int a=10,b=5,c=3,d=4,e;
  e=a>b+c&&d; 
  printf("%d\n",e);
}

# 13.switch case 

#include<stdio.h> 
void main(){
  int a;
  printf("Enter the lucky number:"); 
  scanf("%d",&a);

  switch (a)
  {
    case 1:
      printf("success");
      break; 
    case 2:
      printf("resilience"); break;
    default:
      printf("Better luck next time");
  }
}

# 14.while loop

#include<stdio.h> 
void main()
{
  int a=10,b=20;
  while((a+b)<50);
    {
      printf("a+b = %d\n",(a+b));
      a++;
      b++;
    }
  printf("The value is greater than 50 ");
}

# 15.do while 

#include<stdio.h> 
void main()
{
int a=2,b=6; 
do
  {
    printf("a+b = %d\n",(a+b)); 
    a++;
    b++;
  }while((a+b)<10);
}

# 16.For loop 
#include<stdio.h> 
void main()
{
  int a =10;
  for(int a =10;a<20;a++)
  {
      printf("%d\n",a);
    }
}
 
#include<stdio.h> 
void main()
{
int a=0;
{
int a=10; printf("%d\n",a);
}
printf("%d\n",a); 
printf("asif1%d",printf("asif2"));
}

# 17.break statement 
#include<stdio.h> 
void main()
{
int a=10; while(a<20)
{
printf("%d\n",a);
a++; 
if (a>15)
  {
  break;
  }
}
}

# 18.continue statement

#include<stdio.h> 
void main()
{
int a=10; 
do
  {
    if(a==15)
    {
       a=a+1;
       printf("%d\n",a); 
       continue;
    }
  printf("%d\n",a); a++;
  }while(a<20);
}


/*#include<stdio.h> 
void main()
{
int a=10; 
while(a<20)
  {
  printf("%d\n",a); a++;
  continue; printf("Hello");
  }
}*/

# 19.Array

/*#include<stdio.h> 
void main()
{
char a[4]={10,20,30,40};
printf("a[0]=%d\n",&a[0]);
printf("a[1]=%d\n",&a[1]);
printf("a[2]=%d\n",&a[2]);
printf("a[3]=%d\n",&a[3]);
}
*/

#include<stdio.h> 
void main()
{
//int a[5]= {1,2,3,4,5};
int i,p; for(i=0;i<5;i++)
{
scanf("Enter the array values a[%d]=%d",&i,&p);
}
for(i=0;i<5;i++)
  {
    printf("a[%d]=%d\n",i,p);
  }
}

# 20.pointers

#include <stdio.h> 
void main()
{
int a =10; int * ptr=&a;
int **dptr=&ptr; 
printf("%p\n",dptr); 
printf("%d\n",**dptr); 
printf("%p\n",&a);
printf("%p\n",ptr); 
printf("%d\n",*ptr);
*ptr=20;
**dptr=20; printf("%d",a);
}

# 21.memory allocation

#include<stdio.h> 
#include<stdlib.h> 
void main()
{
int*ptr=(int*)malloc(4);
*ptr=10; printf("%d\n",*ptr);
}

# 22. functions
//no retrurn no passing 

#include<stdio.h>
void hello(void);
void main()
{
  hello();
}
void hello(void)
{
printf("hello");
}

//passing No return 
#include<stdio.h> 
void hello(int);
void main()
{
hello(10);
}
void hello(int b)
{
printf("hello\n");
printf("a=%d\n",b);
}


//return no passing 
#include<stdio.h> 
int hello(void);
int main(void)
{
int a=hello(); printf("a=%d\n",a);
}
int hello(void)
{
return 10;
}

//passing and return #include<stdio.h> int hello(int);
int main(void)
{
int a=hello(10);
printf("a=%d\n",a); return 0;
}
int hello(int b)
{
printf("b=%d\n",b); return 20;
}

# 23.pointers in functions

#include<stdio.h> 
int *hello(int*a);
int main(void)
{	
  int c=100; 
  int*a=hello(&c); 
  printf("a=%d\n",*a);
  return 0;

}
int*hello(int*a)
{ 
  static int y=10; 
  printf("a=%d\n",*a);
  return &y;
}

# 24.structure 

#include<stdio.h> 
struct student{
  int a; 
  char b;
  float c;}x;
void main()
{
struct student x={10,'a',3.56};
// x.a=10;
//x.b='a';
//x.c=3.56; printf("a=%d\n",x.a);
printf("b=%c\n",x.b);
printf("c=%f\n",x.c);
}

# 25.union

#include<stdio.h>
union student
{
  int a;
  char b;
  //float c;
};
void main()
{
  union student x;
  
  x.a=10;
  printf("a=%d\n",x.a);
  printf("b=%d\n",x.b); x.b='a';
  //x.c=3.56; printf("a=%c\n",x.a);
  printf("b=%c\n",x.b);
  //printf("c=%f\n",x.c);
}

# 26. size of
// #include<stdio.h> 
#pragma pack(1) 
struct packets
{
  int a; char b; char c;
  // float e;
};
int main()
{
  struct packets p; printf("%d",sizeof(p));
}


# 27.string copy

#include<stdio.h>
#include<string.h>
int main()
{
char src[8]="WELCOME"; 
char dest[20]; 
strcpy(dest,src); 
printf("%s",dest);
}

# 28.string concatenation

#include<stdio.h> 
#include<string.h> 
int main()
{
  char src[8]="BEST";
  char dest[20]=" OF LUCK"; 
  strcat(src,dest); 
  printf("%s",src);
}

# 29.factorial

#include<stdio.h>
int factorial(int n);
int main()
{
  int n=3,a;
  a=factorial(n);
  printf("%d",a);

}
int factorial(int n)
{
  if(n==0)
  {
  return 1;
  
  }
  else
  {
  return n*factorial(n-1);
  }
}

# 30.pointer to structure

#include<stdio.h>
struct student
{
  int a; 
  char b;
  float c;
}p1={24,'f',3.45};
int main()
{
  struct student *ptr;
  ptr = &p1;
  printf("%d\n%c\n%f\n",ptr->a,ptr->b,ptr->c); 
  return 0;
}
# 31.structure using array

#include<stdio.h> 
int main()
{
struct packets{ 
  int a;
  char c;
};
struct packets p[2]={{20,'A'},{30,'B'}};
int i=0;
for(i=0;i<2;i++) printf("%d\n%c\n",p[i].a,p[i].c);
}

# 32.structure using set

#include<stdio.h> 
struct packet{
  int a;
  char c;
};
struct packet p1={55,'T'}; 
void display(struct packet);
int main()
{
  display(p1);
}
void display(struct packet p)
{
  printf("%d\n%c\n",p.a,p.c);
}

//If else

#include<stdio.h>
int main()
{
  int n=10; 
  if(n%2==0)
  {
     printf("THE NUMBER IS EVEN %d\n",2*n);
   }
   else { 
     printf("THE NUMBER IS ODD"); 
   } 
  return 0;
  }
  
  # 34. macros 
  #include<stdio.h> 
  #define PI 3.142 
  float pi=3.142; 
  void main() {
    printf("PI=%f\n",PI); 
    printf("pi=%f\n",pi); 
  }
  
  # 35.macros if 
  #include<stdio.h> 
  #define a 100 
  int main() {
    #ifdef a 
      printf("a is defined");
    #else 
      printf("a is not defined"); 
    #endif 
      return 0; 
}
