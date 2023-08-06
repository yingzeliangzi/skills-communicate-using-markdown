# This is `h1` title
## This is `h2` title
###### This is `h6` title
![image of avatar](https://avatars.githubusercontent.com/u/92672842)
```Python
import random

print('请输入生成随机验证码的位数:', end='')
num = int(input())
code_list = []
for i in range(10):
    code_list.append(str(i))
for i in range(65, 91):
    code_list.append(chr(i))
for i in range(97, 123):
    code_list.append(chr(i))
r = random.sample(code_list, num)
m = ''.join(r)
print(m)

```
