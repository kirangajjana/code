#include<stdio.h>
#include<conio.h>
void cparking();
void bparking();
void bbparking();
void main()
{
	int a,b,c;
	printf("welcome to the smart parking");
	printf("\n1.car\n");
	printf("\n2.bike\n");
	printf("\n3.bus\n");
	scanf("%d",&a);
	switch(a)
	{
		case 1:
			printf("	WELCOME TO CAR PARKING     \n");
			 cparking();
			 break;
			 case 2:
			 	printf(" WELCOME TO BIKE PARKING    \n");
			 	bparking();
			 	break;
			 	case 3:
			 		printf("WELCOME TO BUS PARKING  \n");
			 		bbparking();
			 		break;
			 		default:
			 			printf(" plz enter any correct choice\n");
	}
}
void cparking()
{
	int a,b;
	printf("ENTER WHERE U WANT TO PARK YOUR CAR\n");
	printf("\n1.FIRST FLOOR\n");
	printf("\n2.SECOND FLOOR\n");
	printf("\n3.THIRD FLOOR\n");
	scanf("%d",&a);
	switch(a)
	{
		case 1 :
			printf("welcome to first floor plz pay your amount to park your car\n");
			scanf("%d",&b);
			if(b>40)
			{
				printf("you can park your car now\n");
			}
			else
			{
				printf("plz pay required amount to park ypour car\n");
			}
			break;
			
				case 2 :
			printf("welcome to second floor plz pay your amount to park your car\n");
			scanf("%d",&b);
			if(b>40)
			{
				printf("you can park your car now\n");
			}
			else
			{
				printf("plz pay required amount to park ypour car\n");
			}
			break;
			 	case  3:
			printf("welcome to third floor plz pay your amount to park your car\n");
			scanf("%d",&b);
			if(b>40)
			{
				printf("you can park your car now\n");
			}
			else
			{
				printf("plz pay required amount to park ypour car\n");
			}
			break;
			default:
				printf("plz press any correct button to park your car\n");
			
			
			
	}
	
}
void bparking()
{
		int a,b;
	printf("ENTER WHERE U WANT TO PARK YOUR CAR\n");
	printf("\n1.FIRST FLOOR\n");
	printf("\n2.SECOND FLOOR\n");
	printf("\n3.THIRD FLOOR\n");
	scanf("%d",&a);
	switch(a)
	{
		case 1 :
			printf("welcome to first floor plz pay your amount to park your bike\n");
			scanf("%d",&b);
			if(b>40)
			{
				printf("you can park your bike now\n");
			}
			else
			{
				printf("plz pay required amount to park ypour bike\n");
			}
			break;
			
				case 2 :
			printf("welcome to second floor plz pay your amount to park your bike\n");
			scanf("%d",&b);
			if(b>40)
			{
				printf("you can park your bike now\n");
			}
			else
			{
				printf("plz pay required amount to park ypour bike\n");
			}
			break;
			 	case  3:
			printf("welcome to third floor plz pay your amount to park your bike\n");
			scanf("%d",&b);
			if(b>40)
			{
				printf("you can park your bike now\n");
			}
			else
			{
				printf("plz pay required amount to park ypour bike\n");
			}
			break;
			default:
				printf("plz press any correct button to park your bike\n");
			
			
			
	}
	
	
}
void bbparking()
{
		int a,b;
	printf("ENTER WHERE U WANT TO PARK YOUR CAR\n");
	printf("\n1.FIRST FLOOR\n");
	printf("\n2.SECOND FLOOR\n");
	printf("\n3.THIRD FLOOR\n");
	scanf("%d",&a);
	switch(a)
	{
		case 1 :
			printf("welcome to first floor plz pay your amount to park your bus\n");
			scanf("%d",&b);
			if(b>40)
			{
				printf("you can park your bus now\n");
			}
			else
			{
				printf("plz pay required amount to park ypour bus\n");
			}
			break;
			
				case 2 :
			printf("welcome to second floor plz pay your amount to park your bus\n");
			scanf("%d",&b);
			if(b>40)
			{
				printf("you can park your bus now\n");
			}
			else
			{
				printf("plz pay required amount to park ypour bus\n");
			}
			break;
			 	case  3:
			printf("welcome to third floor plz pay your amount to park your bus\n");
			scanf("%d",&b);
			if(b>40)
			{
				printf("you can park your bus now\n");
			}
			else
			{
				printf("plz pay required amount to park ypour bus\n");
			}
			break;
			default:
				printf("plz press any correct button to park your bus\n");
			
			
			
	}
	
}
