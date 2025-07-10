# python13
functions
def add(student1,student2):
    return student1+student2
student1=int(input("enter money"))
student2=int(input("enter money"))
total=add(student1, student2)
print("total amount:",total)


#
def value():
    return 3.14159
result=value()
print("value in the function is",result)





#
def get_name():
    name=input("enter your name:")
    return name
username=get_name()
print("welcome",username)




#
def info(name='unknown',age=22):
    print("name:",name)
    print("age:",age)
info("srk",22)
info("mark")
info(age=23)
info()


#
def cal(a,b):
    return a+b,a-b,a*b,a/b
a=int(input("enter a:"))
b=int(input("enter b:"))
sum,diff,pro,div=cal(a,b)
print("sum=",sum)
print("subtract=",diff)
print("product=",pro)
print("divioson=",div)



#
def eo(numbers):
    e=0
    o=0
    for n in numbers:
        if n % 2==0:
            e+=1
        else:
            o+=1
    return e,o
num=input("enter the numbers as space separated:")
num_list=list(map(int,num.split()))
e,o=eo(num_list)
print("even  count:",e)
print("odd count:",o)



#
def max_min(a,b,c):
    return max(a,b,c),min(a,b,c)
a=int(input("enter a:"))
b=int(input("enter b:"))
c=int(input("enter c:"))
maxi,mini=max_min(a,b,c)
print("maximum",max)
print("minimum",min)
