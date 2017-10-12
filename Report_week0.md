### Software engineering  practice using C_Week0    
【Zaphod + 《软件工程（C编码实践篇）》MOOC课程作业http://mooc.study.163.com/course/USTC-1000002006 】

## How to start setting a Linux command-line environment for C coding   
**如何设置一个Linux命令行的编程环境**

First week of this course，the practice is simple: write, compile and run a "hello world" program in a Linux command-line environment.   
这是软件工程的第一周，实验要求很简单： 在Linux 命令行环境下使用C语言，编写，编译后执行输出“Hello world”。

Before having a Linux command-line environment, first we need a Linux system, we can install one in VMware-Workstation.  VMware-Workstation is a "Virtual Machine" software for Windows system, with this kind of Workstation, we can install a different system in our current system.  
Linux命令行环境环境，需要先安装一个Linux 系统，跟课程一样，我选择了在 VMware-Workstation虚拟机上安装一个Linux 系统.

Because this is a Software engineering lesson, I will skip the installation part.  
因为这是软件工程的课，所以跳过具体安装步骤。  
![Ubuntu][1]  
ubuntu is a popular and free Linux system.  
我安装的是最新版的ubuntu.

Once we have our Linux system, we need to install git. Just type "git" in the terminal window, and most Linux system will show you the installing command line. Just repeat them, git will be installed .Or you can just download it from [git-scm.com/download](http://git-scm.com/download).  
 有了Linux系统，就需要安装git， git的安装很容易，在命令窗口输入git命令，系统就会提示如何安装了。当然也可以直接去官网下安装包安装。

After installed git ,now we really have our Linux command-line environment, and ready to hit the road:  
安装好git，Linux环境就差不多可以开始使用进入编程了:

1. Configuring git;  name, email, and push mode; then, create new file folder.  
 第一次使用git要设置git,查看了一些命令和试错，设置了这3个，出一个问题就设置一个,然后创建文件夹。  
![0][2]

1. Connect and clone your web repository form github.com.  
 为了这个课程的作业，专门注册了github的账号，正在学着使用。预先创建了一个专门用于这个课程的仓库，连接这个仓库，把仓库赋值到本地。  
![1][3]

1. Create a lab, use vim to edit the "hello world" code. Then compile this source code and run it.  
在仓库里新建一个新的实验室，用vim编写hello world的源文件，然后按照命令格式 ，编译与运行。Vim有许多不同的命令，一开始用起来不是很顺手。  
![2][4]

1. Add hello.c to local buffer, commit it and push (upload) it to github repository.  
把源文件添加到缓冲区，然后提交，上传到github的仓库，至此，各步骤完成。  
![3][5]


**Test the newly uploaded code. 重现实验**  
![4][6]

### Practice summary：  实验小结  
This practice is not about a "hello world" program. It's about accessing new tools and new environment, and that requires some patience, because new problem will always come up .But if you read the documents or just google it ,most of the time you will find someone else have already met and solved it. So, my experience is: Don't get cold feet, and learn some COMMANDs!  
此次试验本身的目的还是在于，熟悉新的编程环境，去尝试使用新的工具，不论是Linux命令行，vim编辑器，还是github，甚至实验报告用的Mardown语法，这些对我来说都是全新的。通过这样一个最简单的实验，将这些工具有目的的去使用一次，是个很好的开始。


  [1]: https://github.com/zapper123/cs122/blob/master/screenshots/Linux-System.jpg
  [2]: https://github.com/zapper123/cs122/blob/master/screenshots/cs122week0-0.png
  [3]: https://github.com/zapper123/cs122/blob/master/screenshots/cs122week0-1.png
  [4]: https://github.com/zapper123/cs122/blob/master/screenshots/cs122week0-2.png
  [5]: https://github.com/zapper123/cs122/blob/master/screenshots/cs122week0-3.png
  [6]: https://github.com/zapper123/cs122/blob/master/screenshots/cs122week0-4.png
