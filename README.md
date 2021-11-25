#include<stdio.h>
#include<conio.h>

main()
{
 int aan,b;
 int hasil;
 printf("TUGAS UTS\n\n");
 printf("Nama : Aan Putra Bungsu\n");
 printf("Npm  : 2020210077\n");
 printf("===========================\n");
 for(aan=1; aan<=10; aan+=2)
 {
 	hasil=1;
 	for(b=1;b<=aan;b+=2)
 	{
 		if(b!=1)
 		printf("*");
 		printf("%i", b);
 		hasil*=b;
	 }
	 
printf("=%i\n", hasil);
}
printf("==========================");
getch();
}
