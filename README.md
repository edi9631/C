
#include<stdio.h>

 
int main() {
   int a, b, area,perimeter;
 
   printf("\n Въведи A : ");
   scanf("%d", &a);
   while(a<=0){
   Printf("\n Грешка");
   scanf("%d", &a);
   }
   printf("\n Въвдеи B : ");
   scanf("%d", &b);
   while(b<=0){
   Printf("\n Грешка");
   scanf("%d", &b);
   }
 
   area = a * b;
   
   perimeter=2*(a+b);

   printf("\n Лице на Правоъгълник : %d", area);
   printf("\n Периметър на Правоъгълник : %d", perimeter);

 
   return (0);
}
