# ASSIGNMENT-1
Assignment 1, parts 1-5

//Part 1- 

#include <stdio.h> 

  int main() {
    //N,A,B on readme 
    int d, n, a, b;
int sum = 0 ;

printf("enter 3 integers:"); 
scanf("%d %d %d", &n, &a, &b);

int i = 1;
while (i < n) {
  if (i % a == 0 || i % b == 0) {
sum += i;

  }
i++;
}
printf("%d\n", sum); 

return 0;

  }
