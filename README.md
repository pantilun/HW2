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

接下來需要去新增一個token(只能用一次的授權)，路徑為settings/Developer settings/Personal access tokens/Fine-grained tokens(Beta)/Generate new token

在其中的Repository access，要點選Only select repositories，載選擇該Repositories

同時其中的Permissions，將裏頭能read and write的選項全部勾選

最後在第9步中需要打token name(在Generate new token時設定的token name)，以及密碼為Generate new token最後出來的URL

即可成功push資料上來
