We recommend every repository include a README, LICENSE, and .gitignore.
…or create a new repository on the command line
 echo "# ai" >> README.md
 
 
 
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/liuwenye2010/ai.git
git push -u origin master



…or push an existing repository from the command line
 git remote add origin https://github.com/liuwenye2010/ai.git
git push -u origin master



--------------------------------------------
##git config --global user.name "yourname"  
##git config --global user.email myemail@qq.com
查看git设置列表信息   
git config --list 
查看用户名
git config user.name   

----------------------if you using command ---------------------------
(status)
git status -s 
git status 


(add)

git add ./ 


(commit)

git commit -m "ai tensor flow first time commit"

(push)


git push  origin master  // input your username and then password 


git revert SHA 
git commit  (推荐用gui 来回滚错误的提交)
git push   


----------------------------if you using gui ----------------------------------
