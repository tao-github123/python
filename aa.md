#!/usr/bin/python
# _*_ coding:UTF-8 _*_
import math
#计算圆的面积
area = 2 * 2 * math.pi
print('{:.10f}'.format(area))


for i in range(1,11):
    print('舒缓走了第{}天，想她'.format(i))
a = 1
while a <= 10:
    print (a)
    a = a + 1
for a in range(1,10):
    if a == 5:
        break
    print(a)
a = 0
while a < 10:
    a = a + 1
    if a == 5:
         continue
    print(a)
##过滤包含7以及7的倍数的数字。
a = 0
while a < 100:
    a = a + 1
    if a % 7 == 0:
        continue
    elif a % 10 == 7:
        continue
    elif a // 10 == 7:
        continue
    print(a)


