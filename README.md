# bucket_list_blog

## 這個blog是用來學習php的

<p>順便可以記錄自己的口袋清單</p>

### 安裝環境需要有xxamp
### 並且在xxamp的phpmyadmin管理資料庫部分設定兩個table (user和thing_to_do)
![image](https://user-images.githubusercontent.com/68729654/234463702-83820665-1bc3-436f-ac1e-b152c82a3ef0.png)

#### 裏頭的結構(thing to do)
![image](https://user-images.githubusercontent.com/68729654/234463916-740880ad-2095-49a3-b122-b1a57615fbe1.png)

#### user
![image](https://user-images.githubusercontent.com/68729654/234464003-c8fa8e06-92d6-4c65-9a7b-7c612183be23.png)
<span>密碼的部分記得要變成php加密的格式否則password verify的部分會無法成功</span>

接著開啟你的xxamp
![image](https://user-images.githubusercontent.com/68729654/234464164-fbf4260f-f9e1-4392-bbb3-4b7adc1d660f.png)

打開
![image](https://user-images.githubusercontent.com/68729654/234464206-bf4051d5-29b2-4cb9-b3c9-e8c149abeaba.png)

設定資料家的路徑
![image](https://user-images.githubusercontent.com/68729654/234464284-23133e47-9849-4eca-ac65-16b11a097110.png)

接著在瀏覽器輸入localhost就可以了
![image](https://user-images.githubusercontent.com/68729654/234464408-2512e09d-fc7f-4506-84fc-6b0293386ad5.png)

如果想要編輯頁面需要先登入，因為我們沒有設計註冊頁面，直接在user裡面新增就好，接著在瀏覽器的網址欄後面打上/login.php
![image](https://user-images.githubusercontent.com/68729654/234464671-b78c35a9-53b6-4b4e-be32-d44c53ca52b4.png)

想新增頁面在瀏覽器後方輸入 /add_thing.php
![image](https://user-images.githubusercontent.com/68729654/234464967-ef4e7d21-fb9b-4107-94a4-d7d7d4ebcec2.png)
上方的title就是標題
introduction是簡單的描述
圖片可以一次多新增幾張
在下方的圖片描述可以對每張圖下方新增描述不過每張圖之間要用;做間隔
![image](https://user-images.githubusercontent.com/68729654/234466576-3ecbdd0a-4449-408d-8be9-0b0cfe4bf23c.png)
點選submit後，主頁面就新增新的post了

若要對post進行編輯只需在網址欄後 /choose_edit.php選擇要編輯得頁面
![image](https://user-images.githubusercontent.com/68729654/234467442-1e9fac5b-3c08-47e8-a8d6-cc06aa2a82bc.png)



