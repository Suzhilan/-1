├──week1
│├── code
││├── #include<stdio.h>
#include<stdlib.h>
int main()
{
	printf("NO") ;
	system("pause");
	return 0;
}
│└── #include<stdio.h>

int main()
{
	int n;
do{

	scanf("%d",&n);
	if(n==-1)
	{
		break;
	}
	else if(n==0)
	{
		printf("helloworld");
	}
	else if(n==1)
	{
		printf("HELLOWORLD");
	}
	else
	{
		printf("请重新输入");
	}
	}while (1);
	return 0;
}
├──week2
│├──code
││├──#include<stdio.h>
int main ()
{
    	typedef enum {
		GPIO_Speed_2MHz,GPIO_Speed_10MHz,GPIO_Speed_50MHz
	}GPIO_Speed2;
	
	typedef struct{GPIO_Speed2 GPIO_Speed;
	}GPIO_Speed1;

void GPIO_StructureInit(GPIO_Speed1*GPIO_3)
{
	GPIO_3->GPIO_Speed = GPIO_Speed_2MHz;
}
    GPIO_Speed1 GPIO_3;
    GPIO_StructureInit(&GPIO_3);
    
	return 0;
}
││└──README.md
