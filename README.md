#include <stdio.h>
#include<math.h>
#include<stdlib.h>

int main() 
{
    char color[21];
    char pluralNoun[15];
    char celebrityF[18];
     char celebrityL[18];

    printf("Enter the color: ");
    scanf("%s", color);
    printf("Enter the plural noun: ");
    scanf("%s", pluralNoun);
    printf("Enter the celebrity name: ");
   scanf ("%s%s", celebrityF,celebrityL);
    
    
  printf("Roses are the %s \n", color);
  printf("%s are blue\n", pluralNoun),
  printf("I love %s %s \n, celebrityF, celebrityL);
  
  
  
  
      return 0;
}
