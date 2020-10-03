# cse-assignment

//Assignment 01 



#include <stdio.h>


int main() {




   int i, j, rows=5;
   
   
   
   for (i = rows; i >= 1; --i) {
   
   
   
      for (j = 1; j <= i; ++j) {
      
      
         printf("* ");
      }
      printf("\n");
   }
   return 0;
}

//Assignment 02


#include <stdio.h>


int main() {


   int rows=5, i, j, number = 1;
   
   
   for (i = 1; i <= rows; i++) {
   
   
      for (j = 1; j <= i; ++j) 
      
      {
         printf("%d ", number);
         ++number;
      }
      printf("\n");
   }
   return 0;
}
