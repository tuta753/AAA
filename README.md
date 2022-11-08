#include<stdio.h>  
#include<conio.h> 
main()  
{    
	char letter;
	int a=0,b=0,n;
	for (n=1; n<=10; n++)
	{
		printf("Enter letter a-z\n");
		letter = getch();
		printf("%c\n",letter);
		if((letter=='a')||(letter=='e')||(letter=='i')||(letter=='o')||(letter=='u'))
			a++;
		else
			b++;
	}
	printf("a e i o u = %d\n",a);
	printf("Other letter = %d",b);
	getch();
	return 0;
}
