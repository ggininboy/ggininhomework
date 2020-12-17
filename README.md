# ggininhomework
---
## 基本操作說明
```
$ ls
```
可以利用ls來確認目前資料夾中有那些檔案。
```
$ cd [欲進入之資料夾]
```
確認好欲進入之檔案，可利用cd進入資料夾。
```
$ vim [欲進入之檔案]
```
利用vim可進到.sh檔或者.py檔裡面看程式碼，欲修改程式碼可以按"i"來對程式碼進行修改，修改完要記得輸入":wq"來進行儲存並退出。
```
$ sh [欲執行之.sh檔]
```
當我們想要執行.sh檔時，我們可以利用sh後面加欲執行之.sh檔來執行。
## 修改.sh檔並執行(門檻值1)
利用cd選到用來畫圖的.py檔，然後用vim進去對其進行修改，我們將關聯門檻值調成1試試看，接著我們用:wq儲存並退出，然後用sh執行可以跑出圖檔的.sh檔。

![](https://github.com/ggininboy/ggininhomework/blob/main/%E9%96%80%E6%AA%BB1.jpg?raw=true)
## 修改.sh檔並執行(門檻值0.3)
我們同上步驟，只是這次將門檻值調到0.3，試試看跑出來的圖檔會是甚麼樣子。
![](https://github.com/ggininboy/ggininhomework/blob/main/%E9%96%80%E6%AA%BB0.3.jpg?raw=true)
## 結論
我們可以從上面兩張圖片輕易的看出來，當門檻值越高的時候，圖片畫出來的關聯性就會越低，沒什麼線相連；當門檻值越低的時候，圖片畫出來的關聯性就會越高，一大堆線密密麻麻的交織在一起，這其實是因為門檻值就是指程式判斷兩兩有無相關的門檻，當門檻值越低時，程式就會很容易將兩者判斷為有相關的，然後將兩著連起來；當門檻值越高時，程式自然就不容易將兩者判斷唯有相關的，所以圖就會沒什麼線相連。
