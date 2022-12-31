# 家教後台管理系統
#### 幫助需要任何尋找家教的人們進行媒合的後臺管理系統，裏面詳細的記錄了科目分類以及時數價格，統整教老信息，内容都是公開透明。

# 功能介紹
#### 1. 有新建，增加，刪除，修改（CRUD）
#### 2. 使用到擴充方法，叫用 ISPan.Utility
#### 3. 加入了 ErrorPrvider 在沒填入個人資訊時就會跳出警示提醒未填密碼或者賬號
#### 4. 增加老師個人咨詢時設計了可以上傳個人圖片裏面有5種（Jpg,Jpegs,Png,GIF,Bitmaps）類型的圖片可以做讀取。

# 維護商品記錄功能簡述
#### 在新增及編輯功能裡,都先將表單資訊建立成ViewModel,再進行欄位驗證.
#### 在EditForm一開始,先載入一筆記錄, 轉換成ViewModel,再繫結到各控制項裡


## 以下每一頁都有，新建，增加，刪除，修改的功能。

![image](https://github.com/cindy5hsu/WinForms-CRUD/blob/master/Project_Store/Resources/1-2.png?raw=true)

#### 登入圖，當賬號和密碼沒有輸入時，出現 ErrorPrvider 的警示圖，同樣賬號密碼錯誤時也會跳出視窗顯示錯誤。  
#### 按下 Clear Fields 時會清除上方所填入的訊息。  
#### 按下 Exit 則會跳出程式碼。

![image](https://github.com/cindy5hsu/WinForms-CRUD/blob/master/Project_Store/Resources/0-1.jpg?raw=true)

#### 登入成功後，會跳出此主頁可以選擇釋放需要編輯的内容。

![image](https://github.com/cindy5hsu/WinForms-CRUD/blob/master/Project_Store/Resources/2-5.jpg?raw=true)

#### 此為使用者建立賬號處，因爲是後台管理系統因此，在login處無法注冊。得進入後台系統後進行注冊。

![image](https://github.com/cindy5hsu/WinForms-CRUD/blob/master/Project_Store/Resources/3-2.jpg?raw=true)

#### 科目分類的排序頁，可以幫助科目分類選單更好的分類。

![image](https://github.com/cindy5hsu/WinForms-CRUD/blob/master/Project_Store/Resources/2-2.png?raw=true)

#### 到科目類別選單，可以利用下拉選單來選擇科目分類，能夠快速的找到課程分類。

![image](https://github.com/cindy5hsu/WinForms-CRUD/blob/master/Project_Store/Resources/3-1.jpg?raw=true)
#### 教師的個人資訊填報頁，内含有日期下拉選單和科目分類下拉選單，可以上傳個人圖片，圖片下方顯示照片的檔案名稱。

![image](https://github.com/cindy5hsu/WinForms-CRUD/blob/master/Project_Store/Resources/3-3.jpg?raw=true)

#### 最後為點上方登出時，跳出登出視窗。

# 困難之處
#### 在加入圖片時花了一段時間研究如何把圖片加入到資料庫，最後選擇在SQL-server中記錄圖片名稱，
#### 另外有用到擴充方法，所以有時沒有參考到擴充方法所以也花了一段時間Debugger，
#### 遇到困難無法自己解決時，除了上網查資料以外，還會和同學互相討論出解決方法。





