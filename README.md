# Career
I want to learn some skills that can use it in my all life.
## Program
### Python
### Git and GitHub
20201120 11:45

昨晚学习了git的一些知识，然后今天早上继续复习了下，接着下载了git，学习了如何用命令行运行git，设置git账户
git config --global user.name “username” 用户名
git config --global user.email “XXX@XXX.com" 登录邮箱
git init 初始化仓库 git status 查询状态  git add . 添加文件到仓库 
git commit -m ”XX“ 拍摄项目快照   git commit -am ”XXXX“ 提交文件并记录提交
git log 查看提交历史  git log --pretty=oneline 简短历史记录 
git checkout . 撤销修改
git  rmdir /s .git  （慎用删除仓库，如果在其他系统版本的话，rm -rf .git）
### Markdown
以下内容为学习要点：

标题的表示 

：#多少表示
#一级标题
##二级标题
###三级标题
####四级标题
#####五级标题
######六级标题

无序列表的表示：*+空格
 
* 1
* 8
* 3
* 6

有序列表的表示：1. 2. 3. + 空格
1. 家
2. 和
3. 万
4. 事
5. 兴

引用的表示：>
>这句话就是用引用格式表示的

图片与超链接的表示：网页图片表示为！【】（）真正表示时为英文状态下输入，超链接表示为【】（）真正表示时为英文状态下表示
![下雪了](http://p1.itc.cn/q_70/images03/20201120/a87faa42ef5f4ecc8eca58c56e7913f0.jpeg)
[下雪了](https://www.sohu.com/a/433064505_260616?spm=smpc.home.fspic.1.1605856056073gC2g9CQ&_f=index_focus_0)

粗体和斜体以及删除线还有下划线的表示：

两对※※包围为粗体 cuti  **cuti**   

一对※※包围为斜体 xieti  *xieti*  

前后两个波浪线是删除线 ~~这是删除线~~

文字颜色改变的表示：(等待补充)
字体高亮：用一对==表示

  =高亮=

分割线的表示：三个*
***

代码框和脚注的表示：

三个`上下包裹代码就行是代码框  

```
class Dog:
    """一次模拟小狗的简单尝试"""
    def __init__(self,name,age):
        """初始化属性name和age。"""
        self.name = name
        self.age = age

    def sit(self):
        """模拟小狗收到命令时蹲下"""
        print(f"{self.name} is now sitting.")

    def roll_over(self):
        """模拟小狗收到命令时打滚"""
        print(f"{self.name} rolled over!")
my_dog = Dog('Willie',6)
your_dog = Dog('lucy',3)

print(f"My dog's name is {my_dog.name}.")
print(f"My dog is {my_dog.age} years old.")
my_dog.sit()

print(f"Your dog's name is {your_dog.name}.")
print(f"Your dog is {your_dog.age} years old.")
your_dog.roll_over()
```
 
三个`前后包裹是脚注  ```这是脚注```

顺序图的表示：（等待补充）```这个感觉有点难```

流程图的表示：（等待补充）


### Scratch