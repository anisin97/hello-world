# hello-world
// here is a program to print hello-world on the screen, but in a fashionable way.
#include<stdio.h>
void main(){
  int i,j;
  char ar[12]={'h','e','l','l','o','-','w','o','r','l','d','.'};
  for(i=0;i<6;i++)
  printf("%c\n",ar[i]);
  for(j=6;j<12;j++)
  printf("%c",ar[j]);
  }
