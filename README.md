#define _CRT_SECURE_NO_WARNINGS

#include<stdio.h>

int main(void) {

   int x,y;
   scanf("%d %d", &x,&y);

   if ((x >= -1000 && x <= 1000) && (y >= -1000 && y <= 1000)) {
      if (x > 0 && y > 0) {
         printf("1");
      }
      if (x < 0 && y > 0) {
         printf("2");
      }
      if (x < 0 && y < 0) {
         printf("3");
      }
      if (x > 0 && y < 0) {
         printf("4");
      }
   }
   else {
      printf("올바르지 않은 범위입니다");
   }
}
