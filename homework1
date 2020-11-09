//以合法形式打印日期 

#include <stdio.h>

int main()
{
	{
	int month, day, year;
	
	printf("Enter date (mm/dd/yy): ");
	scanf("%d/%d/%d",&month,&day,&year);
	
	printf("Dated is %d",day);
	switch (day) {
		case 1:case 21:case 31:
			printf("st");break;
		case 2:case 22:
			printf("nd");break;
		case 3:case 23:
			printf("rd");break;
		default:printf("th");break;
	}
	printf(" day of ");
	
	switch (month){
		case 1: printf("January");break;
		case 2: printf("February");break;
		case 3: printf("March");break;
		case 4: printf("April");break;
		case 5: printf("May");break;
		case 6: printf("June");break;
		case 7: printf("July");break;
		case 8: printf("Augest");break;
		case 9: printf("September");break;
		case 10: printf("October");break;
		case 11: printf("November");break;
		case 12: printf("December");break;
	}
	
	printf(", 20%.2d.\n", year); 
	
}
	{ 
    int a, b, c, d, C;
	
	printf("输入年份：");
	scanf("%d",&a);
	
	printf("输入月份：");//该公式中要把1月和2月分别当成上一年的13月和14月处理
	scanf("%d",&b);
	
	printf("输入日期：");
	scanf("%d",&c);
	
	C = ( a - ( a % 100) ) / 100;
	d=(c + 2*b + 3*(b+1)/5 + a + a/4 - a/100 + a/400) % 7;
	printf("输出星期：%d\n",d);//星期一用0表示，星期二用1表示……星期日用6表示
	} 
	
	return 0;
	 
} 
