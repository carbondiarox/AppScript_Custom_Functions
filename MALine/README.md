 # MALine  
---
## 功能 / Function

 >  MALine 是 用在 google Sheet 的 擴充功能，當你給出一組股票數據例如:一段時間的 high / low / open /close(column)，會傳回MA線(Moving Average line)數據(column)  
 >  
 >  MALine is an extension used in google sheet, when you give a group of stock data such as: high / low / open / close for a period of time (column), it will send back MA line (Moving Average line) data (column)

---
## 注意 / Attention :

> Interval = MA20 , MA30, MA40 , 预设20 
> * 这里的20是指20个项目，而不是传统意义上的MA20的20天。
> * 如果输入项目是 "每日收盘价"，就是传统意义上的MA20。
> * 如果输入项目是 "每周收盘价"，MA(column_week, 20)意味着每20周的平均价格。


> nterval = MA20 , MA30, MA40 , Preset 20 
> * This 20 here means 20 items, not 20 days in the traditional sense of MA20.
> * If the input item is "Daily Closing Price", it is MA20 in the traditional sense.
> * If the input item is "weekly closing price", MA(column_week, 20) means the average price of every 20 weeks.  

---
## 安裝方法 / Installation method : 

 > 擴充功能 → Google Appscript → 新增檔案  
 > 
 > 1. 請把代碼自行複製到google appscript 並 save.  
 > 2. 部署  
 > 3. 在google sheet 任一行輸入: =MALine(數據,間隔)  
 > 4. enjoy  
 
 > Extensions → Google Appscript → Add file 
 > 
 > 1. Please copy the code to google appscript and save it by yourself.
 > 2. Deploy
 > 3. Type in any line of google sheet: =MALine(data, interval)
 > 4. enjoy

![image](https://user-images.githubusercontent.com/43199731/142760244-983d4cf2-ce05-4953-b386-e5acb7f91a89.png)
![image](https://user-images.githubusercontent.com/43199731/142760266-d5ce02dd-7279-4af2-9b5e-93ee925bc7be.png)
![image](https://user-images.githubusercontent.com/43199731/142759696-3dbbd1df-cf9a-4ef6-accc-dd8946c087a9.png)

---
## 捐贈 / Donate

