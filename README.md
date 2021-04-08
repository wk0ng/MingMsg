# MingMsg - 小茗同学
Windows系统消息

python在Windows上显示系统提示消息比较麻烦，就搞了个简单的工具

用法很简单

```python
MingMsg.exe 消息内容 [标题]
```

![1.png](https://github.com/wk0ng/MingMsg/blob/main/image/1.png)

![2.png](https://github.com/wk0ng/MingMsg/blob/main/image/2.png)

![3.png](https://github.com/wk0ng/MingMsg/blob/main/image/3.png)

直接加到环境变量里面，python调用到时候很方便

```python
import os
os.system('MingMsg.exe biu')
```

![4.png](https://github.com/wk0ng/MingMsg/blob/main/image/4.png)
