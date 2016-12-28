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
