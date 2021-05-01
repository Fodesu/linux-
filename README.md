# linux-
note for linux basic instructions

 基础指令 
 
# 1.ls 指令
用法：
1.#ls       作用：列出当前目录下的所有文件名和文件夹名。
    
2.#ls 路径   作用：列出目标路径下的所有文件名和文件夹名。
（路径可以是绝对路径也可以是相对路径）
（相对路径中 ./表示当前路径 ，../表示上一级路径）

3.#ls 选项 路径   作用：以选项的格式列出指定路径下文件和文件夹的名字。
 常见的有 #ls -l 路径  #ls -la 路径   -l 表示list ,以详细的列表形式列出， -a 表示显示所有文件和文件夹（包括隐藏的）。
 列表中开头字符为d 的是文件夹，为-的是文件。  .开头文件时隐藏文件。
 
4.#ls -lh 路径    作用：列出指定路径下的所有文件名和文件夹名，其中文件大小以最合适的单位显示。

ls 列出的文件颜色 ：  蓝色表示文件夹，黑色表示文件，绿色表示拥有所有权限 。

# 2.pwd 指令  （print  working directory) 

   用法： #pwd  打印当前工作目录 （绝对路径）
   
# 3. cd 指令  （change directory)
   用法: #cd  路径  
   作用：切换到指定路径。
   cd ~ 切换到家目录。
 
 
# 4.mkdir 指令（make directory ）
   用法 
   1.#mkdir  路径
   作用 在指定路径下创建文件。
   
   2.#mkdir -p 路径
   作用 实现一次性创建多层不存在的文件夹。
   
   3.#mkdir 路径1 路径2 路径3
   作用  一次性创建多个。
 
# 5. touch 指令 （创建文件） 
   用法
   #touch 文件路径 （可创建多个）
   作用：创建文件在指定目录下
   
# 6.cp 指令  （复制并粘贴）
   用法
   #cp  被复制的路径  粘贴的路径 （复制文件夹要加上 -r)
   作用：复制文件到目标路径
   
# 7.mv 指令 （move）
  用法 类似cp指令
  #mv 需要移动的文件的路径   移动到的路径  （如果路径不变可以改变文件的名字）
  
# 8. rm 指令 （remove）
   用法
   #rm  选项  需要移除的文件路径
   1. #re -f  (强制删除，无需确认）
   2. #re -r  (删除目录）  
   rf  可以一起用 
   * 通配符 
  
# 9. vim 指令
   用法
   #vim 文件路径 
   作用 用vim打开一个文件
   退出vim 文件： 在没有按下其他按钮时 按下shift + ：再输入q键退出。
   
# 10. 输出重定向 
 一般的指令的结果输出在终端上，使用输出重定向可以把结果保存在文件里。
 “>”覆盖输出
 “>>”追加输出
 如果目标文件不存在，也会创建文件并输出结果。
  
   

   
   
        
           
