# Lai's Homework #5 (Python Flask)

## Lecture 14: IoT Flask Web (github, vs code)

### Step 1 : Development Environment Setup
1. Please install vs code, register github, install git for windows(已安裝可省略)
2. (check-point 1) github create a new repository (aiot-hw5)
3. go to vs code clone this repository (choose new branch) 
4. vs code 安裝 python extension (已安裝可省略)
5. pip install flask, pandas, sklearn (已安裝可省略)
  * 快捷鍵 ctrl+shift+p ===> package manager 叫出 (git clone....)
  * 快捷鍵 ctrl+' ==> 叫出終端機 
6. (check-point 2) 為了要upload local file to github from local要終端機 C:> 設定下面 (不設定 branch default ='main')
   * C:> git config --global user.name "Huan Chen"
   * C:> git config --global user.email huanchen1107@gmail.com
   * C:> git commit -m "first commit"
   * C:> git remote add origin git@github.com:huanchen1107/aiot0524.git

'''text
  --- below is used to a add a new remote:

  git remote add origin git@github.com:User/UserRepo.git
  
  ---below is used to change the url of an existing remote repository:

  git remote set-url origin git@github.com:User/UserRepo.git
  
  -- below will push your code to the master branch of the remote repository defined with origin and -u let you point your current local branch to the remote master branch:

  git push -u origin master
'''
7. 開啟資料庫 (xamapp or heidsql)

8. Final Result (gif)
![gif](2022-06-17%2023-02-32.gif)