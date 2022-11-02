# HW2
高等資料探勘HW2(Follw_behavior)，結果上傳處。
操作步驟 :
首先create一個要放入的repositories
  #以下為cmd步驟
  1. git config --global user.name "pantilun"
  2. git config --global user.email "my_mail"
  3. git config --list  //查看資料是否正確
  4. git init
  5. git add want_to_updata_data 
  6. git commit -m "此次想要commit的名稱"
  7. git branch -M main
  8. git remote add origin URL  //URL = 要放的那個repositories的路徑
  9. git push -u origin main
接下來需要去新增一個token(只能用一次的授權)，路徑為setting/
