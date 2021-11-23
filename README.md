## print
```
print(12138)    #数字直接写
print('obsidian')    #字母
print(1+3)    #输出结果
```
## 输出汉字
```
print(chr(0b+二进制))   #0b--->二进制，0o--->八进制，0x--->十六进制
print(ord('汉字'))
```
## 转义字符
```
print('hello\nworld')    #\n--->换行
print('hello\tworld')     #\t--->空出一个制表位，一个制表位是4个字符
print('hello\bworld')    #\b--->向前覆盖一个字符
print('hello\rworld')     #\r--->向前覆盖到行首
print(r'hello\nworld')   #r或R--->表达式不表达，原样输出
print('fuck','your','mother')   #中间逗号连接，输出结果在一行显示
```
## 变量定义
- 定义的变量包括三部分：标识（id）、类型（type）、值
```
name='不知道'
print('标识',id(name))
print('类型',type(name))
print('值',name)
```
### 数据类型
- int--->整数类型（正数，负数，0）
- float--->浮点数类型（小数）
>浮点数运行时会不准确，使用decimal模块进行运算
```
```