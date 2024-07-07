# Games101

> The Lecture website:
> 
> https://games-cn.org/intro-graphics/
> 

## Finished:

### Assignment0:
虽然推荐是在Linux上进行环境配置，但由于我的主力机是macos，问题不大，我直接在macos上进行配置和实验了
两个命令记得：
- `brew install opencv`
- `brew install eigen`
可以通过 `brew info xxx`来查看安装的情况
- 这里尤其要注意的是 在安装完 `eigen`之后，要更改`eigen` 库的位置 具体看你平时C++中那些库的位置 放一起就好啦

#### Goal:
这个实验主要是让我们熟悉`eigen`库 这个库的作用是提供了一些向量的运算 Matrices Arithmetic的函数
需要我们做的是：
给定一个点 $P=(2,1)$, 将该点绕原点先逆时针旋转 $45◦$，再平移 $(1,2)$, 计算出变换后点的坐标（要求用齐次坐标进行计算）。
