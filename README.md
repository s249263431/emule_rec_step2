# emulesetp2
windows的动态/静态链接技术初步
通过一个加法计算库来演示windows的动态链接(dll)和静态链接(lib)技术以及dll中导出函数的查看方法。
加法计算库的原型如下：

int Add(int a,int b)
{
 return a+b;
}
