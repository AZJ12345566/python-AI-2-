# python-AI-2-
python+AI 笔记(2)
# 1阶段 - 第二章 - 4.数据类型
#变量也可以存储类型的信息
#在python中，变量是没有类型的，但是变量存储的数据是有类型的

# 1阶段 - 第二章 - 5.数据类型转换
num_str=str(11)
print(type(num_str),，num_str) #print可以输出多份内容，内容之间可以用逗号隔开

float_str=str(11.345)
print(type(float_str),float_str)  #强制类型转换的内容是不会被改变的

#在python中，只要用双引号引起来的都是字符串，因此如何类型转字符串都是可以的
#将字符串转换成数字
num=int("11")
print(type(num),num)

num2=float("11.345")
print(type(num2),num2)

num3=int("黑马")  #这里是转换不出来的
print(type(num3),num3)
#万物皆可转字符串，但是当转换成字符串时，必须要确保转换对象是数字才可以

float_num=float(11)
print(type(float_num),float_num)  #可行

int_num=iint(11.345)
print(type(int_num),int_num)  #这里可以转换成功，但是会丢失精度

# 1阶段 - 第二章 - 6.标识符
#在python中标识符的命名可以是英文，中文，数字，下划线这四个元素
#不推荐使用中文，数字不可以使用用在开头，不能用关键字来命名
#python中构建嘴大小写敏感

# 1阶段 - 第二章 - 7.运算符
print("1+1=",1+1)
#//取整除，**乘乘是求平方

# 1阶段 - 第二章 - 8.字符串的三种定义方式
#1.单引号定义法‘’  2.双引号定义法“” 3.三引号定义法“”“ ”“”
#注意三引号定义法，如果用变量接收，他就是字符串。不用变量接收，就作为多行注释使用
