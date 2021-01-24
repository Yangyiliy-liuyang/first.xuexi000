# first.xuexi000
初步学习  郝斌C语言入门
 /*
#include <stdio.h>
int main ()
{
	int a;
	a = 10;

	printf ("a++ = %d\n", a++);
	printf ("a = %d\n", a);

	printf ("++a = %d\n",++a);
	printf ("a = %d\n", a);

	return 0;
}



#include <stdio.h>

int main()
{
	int A;
	int B;
	int X, Y, Z, W;
	scanf("%d %d", &A, &B);
	X = A + B;
	Y = A - B;
	Z = A * B;
	W = A / B;
	printf("%d + %d = %d\n" ,A, B, X);
	printf("%d - %d = %d\n", A, B, Y);
	printf("%d * %d = %d\n", A, B, Z);
	printf("%d / %d = %d\n", A, B, W);
	
    return 0;
}

#include <stdio.h>
int main ()
{
	printf ("hellow!\n");

	

	return 0 ;
}

#include <stdio.h>
int main()
{
	printf ("%d", 12+13);//                  %d  输出后面的整值
	return 0; 
}


//                                             %     取余
#include <stdio.h>
int main ()
{
	printf ("h!\n");//                         输出


	

	return 0 ;
}    


#include <stdio.h>
int main ()
{
//	printf ("100-23=%d\n", 100-23);               加减法  
	int                 price       = 0  ;     //               定义 一个变量 price       
//  类型名称           变量名称        初始值为零

	printf ("请你输入价格（元） :  ");
	scanf ("%d ", &price);                    //      &     ?           

	int chance = 100 - price;         //          
	printf ("找你%d元。\n", change);

	

	return 0 ;
}





//                修改




#include <stdio.h>
int main ()
{
//	printf ("100-23=%d\n", 100-23);               加减法  
	int                 price       = 0  ;     //               定义 一个变量 price       
//  类型名称           变量名称        初始值为零
	int amount = 0;


	printf ("请你输入价格（元） :  ");
	scanf ("%d ", &price);                       

	printf ("请输入票面");
	scanf ("%d", &amount);


	int change = amount - price;                 
	printf ("找你%d元。\n", change);

	

	return 0 ;
}

#include <stdio.h>
int main ()
{

	int a;
	int b;

	printf ("请输入两个整数：");
	scanf ("%d %d", &a,&b);
	printf ("%d + %d = %d",a ,b ,a+b);            //          带个整数输入示例
	return 0;
}



#include <stdio.h>
int main ()
{
	printf ("%f\n", 10.0/3*3);                   //浮点数   %f   带小数点

	return 0;
}

#include <stdio.h>
int main ()
{ 
	printf ("请输入身高的英尺和英尺，" "如输入\"5 7\"表示5英尺7英寸：");

	int foot;
	int inch; 

	scanf ("%d %d", &foot, &inch );

	printf ("身高是%f米。\n", ((foot + inch / 12.0) * 0.3048));

	return 0;
}
/
/
//
//
///
////
/////                                        缺失
/////
//////

#include <stdio.h>
int



p17交换变量


#include <stdio.h>
int main ()
{
	int a = 5;
	int b = 6;
	int t;

	t = a;
	a = b;
	b = t;

	printf ("a = %d , b = %d\n",a , b);

	return 0;
}

                              //    复合运算符  +=  
                              //total += （sum + 100）/2     优先计算后面

                              //递增递减运算符

                                //a++  为a加一以前的值       ++a 为a加一以后的值

                             //eg
#include <stdio.h>
int main ()
{
	int a ;
	a = 10;

	printf ("a++ = %d\n" ,a++);
	printf ("a = %d\n" ,a);

	printf ("++a = %d\n" ,++a);

	return 0;
}
                                 
                                          //scanf 读取

#include <stdio.h>
int main ()
{
	int  hour 1 , minute 1;
	int  hour 2 , minute 2;

	scanf ("%d %d", &hour 1 , &minute 1);
	scanf ("%d %d", &hour 2 , &minute 2);

	int ih = hour 2 - hour 1;
	int im = minute 2 - minute 1;

	if ( im < 0 )
	{
		im = 60 + im;                  //          不等于  !=
		                                //     大于或者等于  >=
	    ih --;
	}
	printf ("时间差是%d小时%d分钟。\n" , ih ,im); 

	return 0;
}                                    //一个错误
	

                                   //找零计算器
#include <stdio.h>
int main ()
{
	printf ("%d\n", 5==3);
	printf ("%d\n", 5>3);      //关系运算结果     
	printf ("%d\n", 5<=3);     //  6>5>4  运算结果应该为6>5成立则为1 而1>4 错误 结果为0
                               //  a==b==6   先a与b是否相等 再计算1 0 是否和6相等  这里结果为0
	return 0;
}
 

#include <stdio.h>
int main ()
{
	int price = 0;
	int bill = 0;

	printf ("请输入金额：");
	scanf ("%d", &price);
	printf ("请输入票面：");
	scanf ("%d" , &bill);

	printf ("应该找你：%d\n", bill - price);

	return 0;
}

02-0. 整数四则运算(10)
时间限制 
400 ms
内存限制 
65536 kB
代码长度限制 
8000 B
判题程序 
Standard 
作者 
乔林（清华大学）
本题要求编写程序，计算2个正整数的和、差、积、商并输出。题目保证输入和输出全部在整型范围内。
输入格式：
输入在一行中给出2个正整数A和B。
输出格式：
在4行中按照格式“A 运算符 B = 结果”顺序输出和、差、积、商。
输入样例： 
3 2
输出样例： 
3 + 2 = 5
3 - 2 = 1
3 * 2 = 6
3 / 2 = 1
                                       //02-0习 
#include <stdio.h>
int main ()
{ 
	int A = 3;
	int B = 2;
	int q, w, e, r;
	scanf ("%d %d",&A , &B);
	q = A + B;
	w = A - B;
	e = A * B;
	r = A / B;

    
	printf("%d + %d = %d\n" ,A, B, q);
	printf("%d - %d = %d\n", A, B, w);
	printf("%d * %d = %d\n", A, B, e);
	printf("%d / %d = %d\n", A, B, r);

	return 0;
}
  


//                                     if 语句

#include <stdio.h>
int main ()
{
	int price = 0；
	int bill = 0;
	//读入金额与票面
	printf ("请输入金额：");
	scanf ("%d",&price);
	printf ("请输入票面：")；
	scanf("%d",&bill);
	//计算找零
	if (bill >= price);
	{
		printf ("应该找零：%d\n",bill-price);
	}
    else
	{
		printf("你的钱不够\n");
	}
	return 0;
}
                                          //错错错一处

#include <stdio.h>
int main()
{
	int a , b ;

	printf ("请输入俩个整数：");
	scanf ("%d %d",&a,&b);

	int max = b;
	if (a > b)
	{
		max = a;
	}
	printf ("大的那个是：%d\n",max);
	return 0;
}

#include <stdio.h> 
int main ()
{
	int a , b ;

	printf ("请输入俩个整数：");
	scanf ("%d %d",&a,&b);

	int max = 0;
	if (a > b)
	{
		max = a;
	}
	else 
	{
		max = b;
	}
	printf ("大的那个是：%d\n",max);
	return 0;
}

02-1. 厘米换算英尺英寸(15)
时间限制 
400 ms
内存限制 
65536 kB
代码长度限制 
8000 B
判题程序 
Standard 
作者 
翁恺（浙江大学）
如果已知英制长度的英尺foot和英寸inch的值，那么对应的米是(foot+inch/12)*0.3048。现在，如果用户输入的是厘米数，那么对应英制长度的英尺和英寸是多少呢？别忘了1英尺等于12英寸。
输入格式：
输入在一行中给出1个正整数，单位是厘米。
输出格式：
在一行中输出这个厘米数对应英制长度的英尺和英寸的整数值，中间用空格分开。
输入样例： 
170
输出样例： 
5 6

                                          //02-1习
#include <stdio.h> 
int main ()
{
	int cm;
	scanf ("%d",&cm);

	int foot =  cm / 30.48;
	int inch = ( cm / 30.48 - foot) * 12;
	printf ("%d %d",foot,inch);
	return 0;
}

02-2. 然后是几点(15)
时间限制 
400 ms
内存限制 
65536 kB
代码长度限制 
8000 B
判题程序 
Standard 
作者 
翁恺（浙江大学）
有时候人们用四位数字表示一个时间，比如1106表示11点零6分。现在，你的程序要根据起始时间和流逝的时间计算出终止时间。读入两个数字，第一个数字以这样的四位数字表示当前时间，第二个数字表示分钟数，计算当前时间经过那么多分钟后是几点，结果也表示为四位数字。当小时为个位数时，没有前导的零，即5点30分表示为530。注意，第二个数字表示的分钟数可能超过60，也可能是负数。
输入格式：
输入在一行中给出2个整数，分别是四位数字表示的起始时间、以及流逝的分钟数，其间以空格分隔。注意：在起始时间中，当小时为个位数时，没有前导的零，即5点30分表示为530；流逝的分钟数可能超过60，也可能是负数。
输出格式：
输出四位数字表示的终止时间。题目保证起始时间和终止时间在同一天内。
输入样例： 
1120 110
输出样例： 
1310
                                          //02-2习

#include <stdio.h> 
int main ()
{
	int i,j,x = 0,y,z;
	scanf ("%d %d",&i,&j);
	if (i >= 1000)
	{
		x = i / 1000;
		y = (i % 1000) / 100;
		z = (i % 1000) % 100;
	}
	else 
	{
		y = i / 100;
		z = i % 100;
	}
	int s = (10 * x + y) * 60 +z;
	int n = s + j;
	i = n /60 * 100 + (n - ((n / 60) * 60));
	printf ("%d", i);
	return 0;
}

02-3. 逆序的三位数(10)
时间限制 
400 ms
内存限制 
65536 kB
代码长度限制 
8000 B
判题程序 
Standard 
作者 
翁恺（浙江大学）
程序每次读入一个正3位数，然后输出按位逆序的数字。注意：当输入的数字含有结尾的0时，输出不应带有前导的0。比如输入700，输出应该是7。
输入格式：
每个测试是一个3位的正整数。
输出格式：
输出按位逆序的数。
输入样例： 
123
输出样例： 
321
                                       //02-2习

#include <stdio.h>
int main ()
{
	int i;
	scanf ("%d",&i);
	int a = i / 100;                   //除法   得到百分位数字
	int b = i % 100 % 10;               //  取余之后得到个位与十位 再次取余得到个位
	int c = i % 100 / 10;               // 取余之后得到个位与十位 再次除法之后得到十位
	i = a + b * 100 + c *10;
	printf ("%d",i);
	return 0;
}

#include <stdio.h>
int main ()
{
	int a,b,c;
	scanf ("%d %d %d", &a,&b,&c);

	int max = 0;

	if (a>b)
	{
		if (a>c)
		{
			max = a;
		}
		else 
		{
			max = c;
		}
	}
	else
	{
		if(b>c)
		{
			max = b;
		}
		else
		{
			max = c;
		}
	}
	printf ("the max is %d \n", max);
	return 0;
}

                                         //if  else 后始终加上个{}

#include <stdio.h>
int main()
{
	int x;

	scanf ("%d"，&x);

	int f = 0;

	if ( x < 0 )
	{ 
		f = -1;
	}
	else if ( x == 0)                    //后面不能加分号
	{
		f = 0;
	}
	else
	{
		f = 2 * x;
	}
		
	printf("%d\n", f);


	return 0; 
}
                                         //一个错




#include<stdio.h>
int main()
{
	int type;
	scanf ("%d",&type);

	if (type == 1)
	{
		printf ("你好\n");
	}
	else if (type == 2)
	{
		printf ("早上好\n");
	}
	else 
	{
		printf ("啊，什么啊\n");
	}
	return 0;
}


                                              //多支分路


                                             // switch-case 语句使用示例


#include <stdio.h>
int main ()
{
	int type;
	scanf ("%d", &type);             //scanf 读取    

	switch (type)                                   //switch (控制表达式)     控制表达式必须是整数型
	{
		case 1:                                     //          此处case 后面要用     : 
			printf ("你好\n");
			break;                                   //   此处若没有break 将顺序执行到下个case里去 直到下个break  或者 switch
		case 2:                                        //case 为入口
			printf ("早上好\n");
			break;
		case 3:
			printf ("晚上好\n");
			break;
    default:
		printf ("啊 什么啊？\n");
		break;
	}
	return 0;
}
 
03-4. 成绩转换(15)
时间限制 
400 ms
内存限制 
65536 kB
代码长度限制 
8000 B
判题程序 
Standard 
作者 
沈睿（浙江大学）
本题要求编写程序将一个百分制成绩转换为五分制成绩。转换规则：

大于等于90分为A；
小于90且大于等于80为B；
小于80且大于等于70为C；
小于70且大于等于60为D；
小于60为E。 
输入格式：
输入在一行中给出1个整数的百分制成绩。
输出格式：
在一行中输出对应的五分制成绩。
输入样例： 
90
输出样例： 
A


                                             //03-4习

#include <stdio.h>

int main()
{
  int i;
  scanf("%d", &i);

  if(i >= 90)
    printf("A\n");
  else if(i < 90 && i >= 80)
    printf("B\n");
  else if(i < 80 && i >= 70)
    printf("C\n");
  else if(i < 70 && i >= 60)
    printf("D\n");
  else if(i < 60)
    printf("E\n");
    
  return 0;
}

#include <stdio.h>
int main ()
{
	int grate;
	scanf ("%d",&grate);

	grate /=10;
	if (grate >= 9 )
	{ 
		printf ("A\n");
	}
	else if (grate >= 6 )
	{
		printf ("B\n");
	}
	else if (grate >= 7)
	{
		printf ("C\n");
	}
	return 0;
}  
#include <stdio.h>
int main()
{
	int grade;
	grade /= 10;
	switch (grade)
	{
	case 10:                           //case 后面用的是冒号  :
	case 9:
	printf ("A\n");
	break;                             //结束要有 break ;

	case 8:
	printf ("B\n");
	break;

    case 7:
	printf ("c\n");
	break;
	}

	return 0;
}


                                                 //程序实现   程序写的是一个过程
	
#include<stdio.h>	
int main ()
{
	int x;
	int n = 1;
	scanf ("%d",&x);

	if(x > 999)                                      //出现级联时 大于号 要求从大到小  高处往下走
		                                                 //小于号低处往上走
		                                  //否则计算结果都是第一个无法计算下一个
										  //  x>0  后面是x>99   直接跳过了
	{
		n = 4;
	}
	else if (x > 99)
	{
		n = 3;
	}
	else if (x > 9)
	{
		n = 2;
	}
	return 0 ;
}
	
#include<stdio.h>	
int main ()
{
	int x;
	int n;
	scanf ("%d",&x);

	n++;
	x /= 10;                            //      x /= 10    等于    x = x / 10

	if (x > 0)
	{
		n++;
		x \= 10 ;
		if ( x > 0)
		{
			n++;
			x /= 10;
			if ...
		}
		printf ("%d\n",n);

		return 0;
	}

#include <stdio.h>
int main ()
{
	int x;
	int n = 0;

	scanf ("%d",&x);

	n++;                           //n++是将n+1然后访问n+1     ++n是将n+1然后访问n
	x /= 10; 
	while (x >0 )                                 //while 循环
	{                                             //循环体中要留下出口  改变条件的机会   否则成为死循环
		n++;
		x /= 10;
	}
	printf ("%d\n",n);
	return 0;
}                                             //  scanf ("%d",&示例)
                                                //  printf ("%d\n",示例)
				    //         	printf ("x = %d,n = %d\n",x,n);                   //程序适当的位置插入printf来输出变量的内容 来检验

                                           //do-while 循环

#include <stdio.h>
int main ()
{
	int  x;
	int n = 0;
	scanf ("%d", &x);
	do
	{
		x /= 10;
			n++;
	}
	while (x > 0);                             //当心   while 后要有分号;
	printf ("%d", n);
	return 0;
}
                                             //问题变成程序
                                           
                                    




                                           //循环计算 


                                 //x 是2的几次方
#include <stdio.h>
int main ()
{
	int x;
	int ret = 0;
	scanf ("%d", &x);

	int t = x;                    //  建议   计算之前保留原始数字 
	while (x > 1)
	{
		x /= 2;
		ret++;
	}
	printf ("log2 of %d.", t, ret);
	return 0;
}

                                           
                                            //  计数循环
#include <stdio.h>
int main ()
{
	int count = 100;                         //count = 3时循环101次
	while (count >= 0)
	{
		count--;
		printf ("%d\n",count);
	}
	printf("发射！\n");
	return 0;
}

2 1 0 -1

n
3
2
1
0
-1                                //循环结果

#include <stdio.h>
int main ()
{
	int n = 3;                       //n = 3时   循环四次
	while (n >= 0)
	{
		printf ("%d\n",n);
		n--;
		
	}
	printf("发射！\n");                               //       \n     表示输出换行
	return 0;
}

3 2 1 0
 
n
3
2
1
0
-1                               //循环结果
           


                                                    //算平均数
#include <stdio.h>
int main ()
{
	int number;
	int sum = 0;
	int count = 0;
	scanf ("%d", &number);                      // 读取的 & 别丢

	do
	{
		if (number != -1)
		{
			sum += number;                         //每读到一个 number 都把它读到 sum 里面去
			count ++;                               //读进来的数只要不是-1 都要加进来 计数
		}
	}

	while (number != -1);            //当心            while    后要有分号   ;
	                                     //number不等于-1要继续  回去做 do
										 //最后的number输出值为 -1

	printf ("%f\n",1.0*sum/count);                      //       \n     表示  回车输出换行
	                                      // 乘以1.0 让它变成浮点数  前面也要改为  %f
	             
				   
	return 0;                    
}



                                                    //算平均数
#include <stdio.h>
int main ()
{
	int number;
	int sum = 0;
	int count = 0;
	scanf ("%d", &number);                      
	while (number != -1)
		{
			sum += number;                        
			count ++;                              
			scanf ("%d",&number);                           //scanf 再次读取这个数
		}

	
	printf ("%f\n",1.0*sum/count);                  
	                                          
	return 0;                    
}
 

  
#include <stdio.h>
#include <stdlib.h>
#include <time.h>
int main ()
{
	srand (time(0));
	int a = rand();                              //rand 生成一个随机数
	//上面两行会随机生成随机数
	printf("%d\n",a%100);                       // x/n  得到1到100之间的数       对a取余 每次得到100以内的数
	return 0;
}


                                                //猜数游戏
#include <stdio.h>
#include <stdlib.h>
#include <time.h>
int main ()
{
	srand(time(0));
	int number = rand()%100 + 1;
	int count = 0;
	int a = 0;
	printf ("我已经想好了一个1到100之间的数。");
		do
		{
			printf ("请你猜这个1到100之间的数：");
			scanf("%d", &a);
			count++;
			if (a > number)
			{
				printf("你猜的数大了。");
			}
			else if (a < number)
			{
				printf ("你猜的数小了。");
			}
		}
		while (a != number);
		printf ("太好了，你用了%d次就猜到了答案。\n", count);
		return 0;
}




                                               //整数的分解 
                              //若对一个整数 %10 可以得到他的个位数
                              //若对一个整数 /10 可以去掉最后的个位数  再次%10 可以得到原来的十位数 





                              //数的逆序
#include <stdio.h>
int main ()
{
	int x;
	scanf ("%d", &x);

	int digit;                      // 表示它的每一位
	int ret = 0;                     // 定义一个结果

	while () 
	{
	digit = x % 10;               //把最后一位表示出来了
	printf ("%d" , digit);
	ret = ret * 10 + digit;
	printf ("x = %d, digit = %d,ret = %d\n", x, digit, ret);


	x /= 10;                      //把最后一位扔掉了
	                              
									
									  // 在C语言中/=是复合赋值运算符的一种，是两种运算（除、赋值）的结合，x/=10等同于x=x/10
                                     //类似的其他运算符还有：+=、 -=、 *=、 %=、 &=、 |=、 ^=、 <<=、 >>=其中等号左边的运算符分别是：加、减、乘、取余、按位与、按位或、按位异或、左移、右移。
	}
	return 0;
}
                                    //第四周4 4.整数的逆序                没懂



                                //素数  
#include <stdio.h>
int main ()
{
	int x;
	//scanf ("%d",&x);
	x = 12;
	int i;
	int isPrime = 1;                       //  x是素数
	for ( i=2; i<x; i++)                              //for 循环
	{
		if (x % i == 0)                  // x % i == 0  表示此时的x不是一个素数
		{
			printf("不是素数。\n");
		}
	}
	printf ("是素数\n");
	if ( isPrime ==1 )
	{
	printf("不是素数\n");
	}


	
	return 0;
}

#include <stdio.h>

int main()
{
  int i;
  scanf("%d", &i);

  if(i >= 90)
    printf("A\n");
  else if(i < 90 && i >= 80)
    printf("B\n");
  else if(i < 80 && i >= 70)
    printf("C\n");
  else if(i < 70 && i >= 60)
    printf("D\n");
  else if(i < 60)
    printf("E\n");
    
  return 0;
}


#include <stdio.h>
int main ()
{
	int grate;
	scanf ("%d",&grate);

	grate /=10;
	if (grate >= 9 )
	{ 
		printf ("A\n");
	}
	else if (grate >= 6 )
	{
		printf ("B\n");
	}
	else if (grate >= 7)
	{
		printf ("C\n");
	}
	return 0;
}  


#include <stdio.h>
int main()
{
	int grade;
	grade /= 10;
	switch (grade)
	{
	case 10:
	case 9:
	printf ("A\n");
	break;

	case 8:
	printf ("B\n");
	break;

    case 7:
	printf ("c\n");
	break;
	}

	return 0;
}

                              //数的逆序
#include <stdio.h>
int main ()
{
	int x;
	scanf ("%d", &x);

	int digit;                      // 表示它的每一位
	int ret = 0;                     // 定义一个结果

	while (x>0) 
	{
	digit = x % 10;               //把最后一位表示出来了
	printf ("%d" , digit);
	ret = ret * 10 + digit;
	printf ("x = %d, digit = %d,ret = %d\n", x, digit, ret);


	x /= 10;                      //把最后一位扔掉了
	                              
									
									  // 在C语言中/=是复合赋值运算符的一种，是两种运算（除、赋值）的结合，x/=10等同于x=x/10
                                     //类似的其他运算符还有：+=、 -=、 *=、 %=、 &=、 |=、 ^=、 <<=、 >>=其中等号左边的运算符分别是：加、减、乘、取余、按位与、按位或、按位异或、左移、右移。
	}
	return 0;
}












///////                                                                                /////////作业一

#include <stdio.h>
int main ()
{
	int x;
	scanf("%d", &x);
    
	int digit;
	int ret = 0;
	while (x > 0)
	{
		digit = x % 10;
		printf("%d", digit);
		ret = ret * 10 + digit;
		x /= 10;
	}
	return 0;
}

#include <stdio.h>
int main ()
{
	int x;
	scanf ("%d", &x);
	int digit;
	int ret = 0;
	while (x > 0)
	{
		digit = x % 10;
		
		ret = ret * 10 + digit;
		x /= 10;
	}
	printf ("%d", ret);
	return 0;
}
/////                               ///第二题

                           //输入一个整数n，输出n除3的余数
#include <stdio.h>
int main ()
{
	int n;
	scanf ("%d", &n);
	//int x = 0;
	while (n > 0)
	{
		n /= 3;
	}
		printf ("%d", n);
	return 0;
}

#include <stdio.h>
int main ()
{
	int age;
	double salary = 4000;

	age = 7;
	if (age > 6)                        //对的为 1  执行
		                                    //age 不大于60 为错误 0  即不进行if里面的操作           
		                                     //if else 后面要有 {}
											//if 后面不能加分号 ;
											//if () 括号里面要求值是 零 或者 非零
											//少用一个 = 就变成赋值 把a的值改了
											//只要啊a = b 中 b 不是 0 这个if都是成立的 都会执行
	{
		salary = salary * 1.2;
		printf ("%d %f\n", age, salary);
	}
	return 0;
}

#include <stdio.h>
int main ()
{
	int x;
	scanf("%d", &x);

	int i;
	int isprime = 1;                           //isprime = 1 表示是一个素数

	for ( i = 2; i < x; i++)          //  进行一个for循环 i 从 2 开始 小于等于 x-1为止 每次循环i+1

		                              //  for ()括号里面是分号 :
		if(x % i == 0)                     //为零不是素数
		{
			isprime = 0;
			break;                          // break 离开该循环
			                                // continue 这一轮循环放弃 直接下一轮
		}
	}
	{
	if (isprime == 1)
	{
		printf ("是素数\n");
	}
	else 
	{
		printf ("不是素数\n");
	}
	return 0;

                                    //第五周 2 2p
#include <stdio.h>
int main ()
{
	int x;
	//scanf("%d", &x);
	x = 2;
	int cnt = 0;                             //输出50个素数


	//for (x = 2; x < 100; x++)               //输出100以内          //循环的嵌套  多重循环  
	//while (cnt < 50)
	for (x = 2; cnt < 50; x++)
	{
		int i;                       //计数器  记录素数的个数
		int isprime = 1;                           //isprime = 1 表示是一个素数

		//for ( i = 2; i < x; i++)          //  进行一个for循环 i 从 2 开始 小于等于 x-1为止 每次循环i+1
		while (cnt < 50)
		{							  //  for ()括号里面是分号 :
			if(x % i == 0)                     //为零不是素数
			{
				isprime = 0;
				break;                          // break 离开该循环
												// continue 这一轮循环放弃 直接下一轮
			}
		}
		if (isprime == 1)
		{
			printf ("%d", x);
			cnt++;
		}
		//x++;
	}
	printf("\n");

	return 0;
}
                                      // /////////for循环适合的场合是 次数是固定或者一个范围 例2到100


                                        //凑硬币
#include <stdio.h>
int main ()
{
	int x;
	int one, two, five;
	int exit = 0;
	//scanf ("%d", &x);
	x = 2;
	for (one = 1; one < x * 10; one++)
	{
		for (two = 1; two < x * 10 / 2; two++)
		{
			for (five = 5; five < x * 10 / 5; five++)
			{
				if(one + two * 2 + five * 5 == x * 10)
				{
					printf ("可以用%d个一角加%d个二角加%d个五角得到%d元\n", one, two, five, x);
					exit = 1;
				//	break;                         //只跳出本回合
					goto out;
				}
			}
		//if (exit == 1) break;
		}
	//if (exit == 1) break;
	}
out:
	return 0;
}
                                     //  //接力break
                                     //  // goto

#include <stdio.h>
int main()
{ 
	int n;
	int i;
	double sum = 0.0;

	//scanf ("%d", &n);
	n = 10;
	for (i = 1; i <=n; i++)
	{
		sum += 1.0 / i;
	}
	printf ("f(%d) = %f\n", n, sum);
	return 0;
}



#include <stdio.h>
int main()
{ 
	int n;
	int i;
	double sum = 0.0;
	int sign = 1;

	//scanf ("%d", &n);
	n = 10;
	for (i = 1; i <=n; i++)
	{
		sum += 1.0 / i;
		sign = -sign;
	}
	printf ("f(%d) = %f\n", n, sum);
	return 0;
}

                             //最大公约数
                                           //枚举法
#include <stdio.h>
int main ()
	{
		int a,b;
		int min;
		scanf ("%d %d", &a, &b);
		if ( a < b)
		{
			min = 0;
		}
		else 
		{
			min = b;
		}
		int ret;
		int i;
		for (i = 1; i < min; i++)
		{
			if (a%i == 0)
			{
				ret =i;
			}
		}
	
	printf ("%d和%d的最大公约数是%d.\n", a, b, ret);
	return 0;
	}


                                  //辗转相乘法    第五周3 2p
                               
#include <stdio.h>
int main ()
{
	int a,b;
	int t;
	scanf ("%d %d", &a, &b);

	while (b != 0)
	{
		t = a % b;
		a = b;
		b = t;
		printf ("a = %d, b = %d, t = %d\n", a, b, t);
	}
	printf("gcd = %d\n", a);
	return 0;
}

                                      
#include <stdio.h>
int main ()
{
	int x;
	scanf("%d", &x);
	do 
	{
		int d = x % 10;
		printf ("%d ", d);
		x /= 10;
	}
	while (x > 0);
	return 0;
}
            //得到逆序的结果  12345 得到 5 4 3 2 1 






#include<stdio.h>
int main ()
{
	int x;
	scanf("%d", &x);
//	x = 70000;

	int cnt = 0;
	int mask = 1;
	int t = x;

	while(t > 9)                                // //满足while就做该步骤
	{
		t /= 10;
		mask *= 10;
		cnt++;
	}
	printf ("cnt = %d\n", cnt);

                                             // //做一个循环去计算位数
	//int mask = pow(10, cnt-1);
	int mask = 10000;
	do 
	{
		int d = x / mask;
		x %= mask;
		mask /= 10;
		printf ("%d", d);
		if (x > 9)
		{
			printf ("");
		}
		x %= mask;
		mask /= 10;
	//	printf ("x = %d, mask = %d, d = %d\n", x, mask, d);
	}
	while (mask > 0);                         //
	printf ("\n");
	return 0;
}


                                 //
#include <stdio.h>
int main ()
{
	int x;
	double sum = 0;
	int cnt = 0;
	int number[100];                      /// 数组最大为99 下标减一   
	//    定义number 一个数组 大小为一百 数据类型为int                    
	scanf ("%d", &x);
	while (x != -1)
	{
		number[cnt] = x;
		sum += x;
		cnt ++;
		scanf ("%d", &x);
	}
	if (cnt > 0)
	{
		printf ("%f\n", sum / cnt);
		int i;
		for (number [i] > sum / cnt)
		{
			if(i = 0; i < cnt; i++)
			{
				printf ("%d\n", number[i]);
			}
		}
	}
	return 0;
}






//

#include <stdio.h>


void sum (int begin, int end)                        //函数
  //函数头      void 返回类型      sum 函数名    （参数表） 一定要有圆括号
{
	int i;
	int sum = 0;
	for ( i = begin; i <= end; i++)
	{
		sum += i;
	}
	printf ("%d到%d的和是%d\n", begin, end, sum);
}
                                            //函数体

int main()
{
	sum (1,10);
	sum (20,30);
	sum (35, 45);

	return 0;
}


#include <stdio.h>
int main ()
{
	int x;
	double sum = 0;
	int cnt = 0;
	int number[100];                      /// 定义数组                  
	scanf ("%d", &x);
	while (x != -1)
	{
		number[cnt] = x;        //   对数组中的元素赋值


		sum += x;
		cnt ++;
		scanf ("%d", &x);
	}
	if (cnt > 0)
	{
		printf ("%f\n", sum / cnt);
		int i;
		for (i = 0; i < cnt; i++)
		{
			if(number [i] > sum / cnt)
			{
				printf ("%d\n", number[i]);
			}
		}
	}   
	return 0;
}

 
                                           //
#include <stdio.h>
int main (void)
{
	const int number = 10;                      //
	int x;
	int count[number];

	int i;
	for (i = 0; i < number; i++)
	{
		count [i] = 0;
	}

	scanf ("%d", &x);
	while (x != -1)
	{
		if (x >= 0 && x <= 9)
		{
			count[x]++;
		}
		scanf ("%d", &x);           //循环结束再次读取那个x
	}
	for (i = 0; i < number; i++)
	{
		printf ("%d:%d\n", i, count[i]);
	}
		return 0;
}


#include <stdio.h>
int main(void) 
{ 	
	int i, j ;
 	for(i=1;i<=9;i++) 	
	{ 	
		for(j=1;j<=i;j++) 
			printf("%d*%d=%d\t",i,j,i*j);	
		{ 	
 		} 		 
			printf("\n"); 
	} 	 
	return 0; 	
} 
                         //

#include <stdio.h>
int max (int a, int b)                   //函数要写到上面
{
	int ret;
	if (a > b)
	{
		ret = a;
	}
	else 
	{
		ret = b;
	}
	return ret;
}
int main ()
{
	int a, b, c;
	a = 5; 
	b = 6;
	c = max(10,12);
	c = max(a,b);
	c = max(c,23);
	printf ("%d\n", max(a,b));
return 0;
}
 
#include <stdio.h>

int max (int a, int b) ;              //函数的原型声明

int main ()
{
	int a, b, c;
	a = 5; 
	b = 6;
	c = max(10,12);
	c = max(a,b);
	c = max(c,23);
	printf ("%d\n", max(a,b));
return 0;
}

int max (int a, int b)               ///声明定义         
{
	int ret;
	if (a > b)
	{
		ret = a;
	}
	else 
	{
		ret = b;
	}
	return ret;
}


 




                                  
#include <stdio.h>

void swap{int a, int b};           

int main ()
{
	int a, b;
	a = 1;
	b = 2;
	swap (a, b);
	printf("a = %d, b = %d", a, b);
	return 0;
}

void swap{int x, int y}
{
	int swap;
	int t = y;
	int y = t;
}
                                        


#include<stdio.h>

void sum {int begin, int end};           //函数原型

int main ()
{
	sum{1,10};
	sum{20,30};            //调用时这里是值  不是作为参数调用
	sum{35,45};

	return 0;
}

void sum(int begin, int end)
{
	int i;
	int sum = 0;
	for (i = begin; i <= end; i++)
	{
		sum += i;
	}
	printf ("%d和%d的和是%d\n", begin, end, sum);
}


                                      ///块内   块外   本地变量
void swap(int a, int b);
int main()
{
    int a = 5;
    int b = 6;
    swap(a,b);
    printf("%d-%d\n", a, b);
    return 0;
}
void swap(int a, int b)
{
    int t = a;
    a = b;
    b = t;
}

                                     //void swap (void)

#include <stdio.h>
int main ()

	for (i = 0; i < 3; i++)
	{
		for (j = 0; j < 5; j++)
		{
			a[i][j] = i * j;
		}
	}


#include <stdio.h>
int main ()

const int size = 3;
int board[size][size];
int i, j;
int numOfX;
int numOfO;
int result = 1;
for (i = 0; i < size; i++)
{
	for(j = 0; j < size; j++)
	{
		scanf ("%d", &board[i][j]);
	}
}
for (i = 0; i < size && result == -1; i++)
{
	numOfO = numOfX = 0;
	for (j = 0; j < size; j++)
	{
		if (board[i][j] == 1)
			numOfO ++;
	}
	else 
	{
		numOfO ++;
	}
}
if (numOfO == size) 
{
	result = 0;
}
else if (numOfX == size)
{
	result = 1;
}
  





                                /////数组的大小 sizeof(a)/sizeof(a[0])
									//sizeof 整个数组所占据的内容的大小 单位是字节


   // prime [count++] = i;





*/
#include <stdio.h>
int amount [] = {1, 5, 10, 25, 50};
char *name [] = {"pennyy", "nickl", "dime", "quarter", "half-dollar"};
int search{int key, int a[], int len)
{
	int ret = -1;















                                                  




	







































 
