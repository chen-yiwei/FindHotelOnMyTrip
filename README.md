FindHotelOnMyTrip
=================

## 介紹
FindHotelOnMyTrip 是一個方便的訂飯店利器,  
使用者選定飯店與多個指定日期, 執行後即可連續開啟多個Agoda分頁, 讓使用者比較出最便宜的飯店期間！  

Demo on ubuntu.  
![demo](https://raw.github.com/shengyu7697/FindHotelOnMyTrip/master/demo.gif)  

## 如何使用 findAgoda.py
修改 findAgoda.py 內 的hotel_name、 city、start_date_array 和 end_date_array 變數  
之後執行本程式  
```
./findAgoda.py
```
or
```
python findAgoda.py
```
就會自動連續開啟選定的飯店與選定日期的頁面！  

#### 例如：  
以下修改範例為選定 "日本福岡" 的 "東橫INN博多口站前",  
日期選定 "2017-10-20 ~ 2017-10-21",  
"2017-10-21 ~ 2017-10-22",  
"2017-10-22 ~ 2017-10-23" 這三種日期組合.  
```
hotel_name="toyoko-inn-hakata-guchi-ekimae" # 東橫INN博多口站前
city="fukuoka-jp" # 福岡
start_date_array = (
  '2017-10-20',
  '2017-10-21',
  '2017-10-22' )
end_date_array = (
  '2017-10-21',
  '2017-10-22',
  '2017-10-23' )
```
使用者可自行新增各種日期的組合來查詢, 藉此找到最便宜的飯店期間!  

## 系統需求
可以執行Python2 或 Python3 的系統  

## 開發環境
Python 2.7.x  

## License
FindHotelOnMyTrip is published under the MIT license.  
