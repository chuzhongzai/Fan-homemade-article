# main.py
自己用py瞎写的一个项目，拿来看同人文
原理是读取data.txt下的命令，然后通过按钮来控制什么时候下一步命令
（每行最后不要直接换行，空格后再换行，小数点一定要是英文的，不能是逗号）

语法：1.setbody 身体数量 图片名字（三个参数之间要空格，意思是一定把数量图片放进去（其实要么放一个要么放两个））
      2.setbg 图片名字  （同理空格，设置背景）
      3.show 图片名字 名字:内容 (对话，图片的表情，名字：内容就是谁说了什么)
      4.aside 内容（旁白，此时表情清空）
