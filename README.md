# Python
习题记录

##### 习题1：输出hello world  
    print 'Hello World ' 
    
    [Hello World] 

##### 习题2：两数相加
    a=input()   
    b=input()  
    print a+b  
    
    [9 10 19]
> raw_input()，它把所有的输入都直接当作一串字符  
>：大于  
<：小于  
>=：大于等于  
<=：小于等于  
==：等于。比较两个值是否相等。之所以用两个等号，是为了和变量赋值区分开来。
> !=：不等与
> not：逻辑 “非”。如果 x 为 True，则 not x 为 False
> and：逻辑 “与”。如果 x 为 True，且 y 为 True，则 x and y 为 True
> or：逻辑 “或”。如果 x、y 中至少有一个为 True，则 x or y 为 True

##### 习题3：输出1到100
    for i in range (1,101):
        print i   

##### 习题4：1加到100的和 
    a=0
    for i in range (1,101):
        a+=i
    print a
    
    [5050]
##### 习题 5：等比数列  
    a=input()
    b=1
    for i in range (1,11):
        print b
        b=b*a
##### 习题 6：输出斐波纳契数列
    a=input()
    b=1
    c=1
    d=0
    for i in range (0,a):
        print b
        b=c+d
        d=c
        c=b
##### 习题 7：输出三角形  
    a=input()
    for i in range (0,a+1):
    for j in range (0,a-i):
        print '',
    for j in range (0,i):
        print '*',
    print  
>如果想让这 5 个 * 在同一行，就在 print 语句后面加上逗号  
print 后面没有写任何东西，是起到换行的作用，这样，每输出 5 个 *，就会换行。
