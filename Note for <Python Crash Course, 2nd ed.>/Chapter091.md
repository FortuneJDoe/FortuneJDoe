# 9.1 创建和使用类
## 9.1.1 创建Dog类
&emsp;&emsp;根据Dog 类创建的每个实例都将存储名字和年龄， 我们赋予了每条小狗蹲下(sit( )) 和打滚(roll_over( ))的能力：
````py
class Dog:
  """一次模拟小狗的简单尝试"""
  def __init__(self, name, age):
    """初始化属性name和age"""
    self.name = name
    self.age = age
    
  def sit(self):
    """模拟小狗收到命令蹲下"""
    print(f'{self.name} is now sitting.')
    
  def roll_over(self):
    """模拟小狗收到命令时打滚"""
    print(f"{self.name} roll over!")
````

#### &emsp;&emsp;**方法__init__()**
<font face="黑体" color=red size=5>这是红色黑体5号字</font>
<span style="color:red;"><p align="right">**[concept-091-001]**</p></span>
