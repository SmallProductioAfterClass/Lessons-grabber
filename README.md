#Lessons-grabber :
---
: a php function which can help you grab the P.E. class in most china's university zfsoft website,which include a student's id identification function . In order to avoid some matters ,I haven't upload the code on github , while i put some screenshots there. 	
#正方教务系统抢课助手
---
: 一个php小程序，可以用来代理登录大部分中国大学的正方教务系统，用于抢体育课，其中还包括了一个学生身份的认证的程序，担心放出源码会带来不必要的麻烦，这里只放出截图。

---
![login][1]
代理登录，已经可以切换学校的内网接口和电信接口了，如果需要的话也可以接入其他正方教务系统的地址。可以获得学生姓名及教务系统存储的其他信息

![check-score][2]
查询成绩，并且支持排序

主要功能：
![get-PE][3]
保存身份验证信息，来实现绕过学校的刷新限制，快速发送大量课程请求到队列中，实现抢课

  [1]: login.gif
  [2]: checkscore.gif
  [3]: getPE.gif