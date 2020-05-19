
# 实验
## 实验平台<br>
[NJUPT Online Judge](https://acm.njupt.edu.cn)<br>

## 实验一<br>
[NOJ1004 线性表操作](https://acm.njupt.edu.cn/problem/NOJ1004)<br>
```C
/*************************************************
Copyright (C), 2018-2022,Literature Tech. Co., Ltd.
source:    南京邮电大学《数据结构A》课程实验 NOJ1004
Author:    Written by Mr.YangWenxuan
Version:   1.0
Date:      2020.05.20
Description:  线性表是n个元素的有序集合（n≥0），n是线性表中元素的个数，
              称为线性表的长度。可以用一组地址连续的存储单元依次存储线性表中元素，
              采用这种存储方式的线性表称为顺序表。
              请在顺序表上实现运算，实现顺序表的逆置，删除表中所有元素值等于x的元素。
Others:   None
Function List:  main
History:  The first edition 2020.05.19
*************************************************/

#include<stdio.h>
#include<stdlib.h>
int main()
{
    int k, *a, A;
	int n1, n2, n3;
	char *c, B;
	double *d, C;
	//输入 
	/*************************/ 
	scanf("%d", &n1);
	//动态申请数组空间存入元素 
	a = (int*)malloc(sizeof(int)*n1);
	for (k = 0;k < n1;k++)		
		{
		    scanf("%d", &a[k]);
		}
	scanf("%d", &A);	
	scanf("%d\n", &n2);	
	//动态申请数组空间存入元素 
	c = (char*)malloc(sizeof(char)*n2);	
	for (k = 0;k < n2;k++)	
		{
		    scanf("%c ", c+k);	
		}
	scanf("%c", &B);	
	scanf("%d", &n3);
	//动态申请数组空间存入元素 
	d = (double*)malloc(sizeof(double)*n3);	
	for (k = 0;k < n3;k++)		
	    {
		    scanf("%lf", &d[k]);
		}
	scanf("%lf", &C);
	//输出
	/************************/				
	for (k = n1 - 1;k >= 0;k--)	 //逆序输出 
		{
		    printf("%d ", a[k]);
		}
	printf("\n");
	for (k = n1 - 1;k >= 0;k--)	
		{
			if (a[k] == A)        //排除相同元素 
				continue;	
			printf("%d ", a[k]);	
		}
	printf("\n");
	for (k = n2 - 1;k >= 0;k--)	 //逆序输出 
		{
		    printf("%c ", c[k]);
		}
    printf("\n");	
	for (k = n2 - 1;k >= 0;k--)	  //排除相同元素
		{
		    if (c[k] == B)		
				continue;	
			printf("%c ", c[k]);
		}
	printf("\n");
	for (k = n3 - 1;k >= 0;k--)	   //逆序输出 
	    {
		    printf("%g ", d[k]);   
		}
	printf("\n");
	for (k = n3 - 1;k >= 0;k--)   //排除相同元素
		{		
			if (d[k] == C)		
				continue;	
			printf("%g ", d[k]);
		}
    return 0;

}
```

[NOJ1005 多项式加法](https://acm.njupt.edu.cn/problem/NOJ1005)<br>
```javascript
document.getElementById("ts").innerHTML="Hello"
```

[NOJ1006 多项式乘法](https://acm.njupt.edu.cn/problem/NOJ1006)<br>
```javascript
document.getElementById("ts").innerHTML="Hello"
```

## 实验二<br>
[NOJ1018 深度遍历二叉树](https://acm.njupt.edu.cn/problem/NOJ1018)<br>
```javascript
document.getElementById("ts").innerHTML="Hello"
```

[NOJ1019 计算二叉树的高度和结点数](https://acm.njupt.edu.cn/problem/NOJ1019)<br>
```javascript
document.getElementById("ts").innerHTML="Hello"
```

[NOJ1020 层次遍历二叉树](https://acm.njupt.edu.cn/problem/NOJ1020)<br>
```javascript
document.getElementById("ts").innerHTML="Hello"
```

[NOJ1021 二叉树复制和左右子树互换](https://acm.njupt.edu.cn/problem/NOJ1021)<br>
```javascript
document.getElementById("ts").innerHTML="Hello"
```

[NOJ1022 哈夫曼编码与译码](https://acm.njupt.edu.cn/problem/NOJ1022)<br>
```javascript
document.getElementById("ts").innerHTML="Hello"
```

## 实验三<br>
[NOJ1047 图的深度优先遍历序列](https://acm.njupt.edu.cn/problem/NOJ1047)<br>
```javascript
document.getElementById("ts").innerHTML="Hello"
```

[NOJ1048 图的宽度优先遍历序列](https://acm.njupt.edu.cn/problem/NOJ1048)<br>
```javascript
document.getElementById("ts").innerHTML="Hello"
```

[NOJ1049 飞机最少换乘次数问题](https://acm.njupt.edu.cn/problem/NOJ1049)<br>
```javascript
document.getElementById("ts").innerHTML="Hello"
```


## 实验四<br>
[NOJ1061 简单选择排序](https://acm.njupt.edu.cn/problem/NOJ1061)<br>
```javascript
document.getElementById("ts").innerHTML="Hello"
```

[NOJ1062 直接插入排序](https://acm.njupt.edu.cn/problem/NOJ1062)<br>
```javascript
document.getElementById("ts").innerHTML="Hello"
```

[NOJ1063 冒泡排序](https://acm.njupt.edu.cn/problem/NOJ1063)<br>
```javascript
document.getElementById("ts").innerHTML="Hello"
```

[NOJ1064 快速排序](https://acm.njupt.edu.cn/problem/NOJ1064)<br>
```javascript
document.getElementById("ts").innerHTML="Hello"
```

[NOJ1065 两路合并](https://acm.njupt.edu.cn/problem/NOJ1065)<br>
```javascript
document.getElementById("ts").innerHTML="Hello"
```

[NOJ1066 堆排序](https://acm.njupt.edu.cn/problem/NOJ1066)<br>
```javascript
document.getElementById("ts").innerHTML="Hello"
```



