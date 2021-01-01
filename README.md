### Hi there 👋

<!--
**iremtopcam/iremtopcam** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

#include <stdio.h>
#include <stdlib.h>

int main()
{

  //c dilinde sayileri tersten yazdirmak

  int sayi,bir,iki,uc,dort,bes;
  printf("bes basamakli sayi giriniz");
  scanf("%d",&sayi);
  printf("\n");

  bir=sayi/10000;
  iki= (sayi/1000)%10;
  uc=(sayi/100)%10;
  dort= (sayi/10)%10;
  bes=sayi%10;

  printf("%d%d%d%d%d",bes,dort,uc,iki,bir);



    return 0;
}
