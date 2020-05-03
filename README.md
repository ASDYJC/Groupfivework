# Groupfivework
home work of IT
5组建立的项目
[数据删除]基础应用.doc
半自动化建设.doc
判别器判断.doc
开关控制进制转换模块.doc
线路铺设.doc
自动化实践.doc
#include<stdio.h>
static int a=0;
double bintodec(char*str)
{
    a=a*2+(*str-'0');
    return 0;
}
int main()
{
    char ch;
    while(ch=getchar(),ch!='\n')
    {
        char *p=&ch;
        bintodec(p);
    }
    printf("%d",a);
}
