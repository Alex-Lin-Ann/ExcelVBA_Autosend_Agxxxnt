# 自動發信並夾帶附件給客戶
該客戶針對發信格式有特別需求
1. 標題要指定固定格式
2. 附檔要指定提單號碼的格式
3. 每個月固定要記錄進口的提單號碼在固定form，月底時寄送該月份的表單給客戶
![image](https://user-images.githubusercontent.com/37874182/204073616-8fe0d4d3-7f62-43ce-a922-0319b04d635b.png)

# 使用步驟 
1. 貼上該客戶的整欄提單號碼在該月份的worksheet
2. 程式會自動啟動整欄選取->複製->貼上SendMail的worksheet (無須理會及操作)
3. 需要再C槽(C:\file\)建立一個名為file的資料夾，並把下載好的pdf檔案存放於此 (只需操作一次，之後則免)
4. 點選按鈕[Find Data]搜尋檔案是否存在
5. 點選按鈕[Send Mail]寄出郵件

# 功能介紹
* 工作表SendMail
1. 按鈕[Send Mail] - 寄出信件
2. 按鈕[Find Data] - 搜尋檔案是否存在
3. 按鈕[一年按一次，工作表製作] - 製作一整年的工作表
4. 儲存格G3 - 寄送主要收件人
5. 儲存格G4 - 寄送次要關係人
6. 儲存格G5 - 寄件人簽名檔出現的名稱
  
* 工作表AT 1~12月
* 將完整提單號碼依整欄貼上(系統會在貼上後立即啟動程式，並貼在SendMail的B2整欄貼上)
  ![image](https://user-images.githubusercontent.com/37874182/204074082-87e5e707-2b5a-443f-abab-33ab26302969.png)

