# someTest

My learning  
在工作中遇到一些问题，然后进行的一些测试  
1.从远程库clone到本地，本地会新建一个git库，主分为master。   
2.主分支是master,要稳定，安全。所以平时都去dev开发？  
        创建了dev之后，开发，提交。但是master忘记合并了。
        然后，用户1:checkout master, merge dev, and then  push. thus, master is 2.0   
               用户2： first pull dev，then push dev, then  checkout master,pull,push, thus,master is 3.0   
         实验了几次，当冲突的时候不知所措，稀里糊涂的弄好。最后，反正主代码没问题。大概也搞清楚了用法。    
         注意几点：  
                    *先pull,保证你的版本不会落后    
                    *pull之后有冲突修改好      
                    *add  -> commit ->push       
3.刚开接触遇到的最大问题：master比dev先进    
        是说，经常不知不觉在master分支下修改东西。然后提交，反而dev进度落后了。这个问题肯定要改，但是问题怎么办？     
        好吧，解决。checkout dev -> pull -> merge master -> resolve conflict -> push   
        这次问题解决后养成如下习惯：在dev下开发，dev提交后，转master，先pull，再解决冲突，再merge dev,解决冲突，再push    
 ---
 ##git中的read.md文件编辑语言：Markdown
 
        
        
        
        
           
           
        


