## Chapter 6 
## Exercise 6.1

#include<stdio.h> 
#include<stdlib.h> 
#include<math.h>

int main()

{
  float x1, x2, y1, y2, distance, square;
   printf("Ingesa el punto 1: ");
   scanf("%f %f",&x1,&y1);
    printf("Ingesa el punto 2: ");
   scanf("%f %f",&x2,&y2);

distance = sqrt(pow((x2-x1),2)+pow((y2-y1),2));

square = pow((distance),2);

 printf("La distancia entre esos puntos es de %.2f. ", distance);
 printf("El cuarado de la distancia entre esos puntos es de %.2f", square);

 return(0);
 }

## Exercise 6.2
