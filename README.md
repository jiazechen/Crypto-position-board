# Crypto-position-board
A pannel with display the scale of your crypto assets, building by cursor pro AI.

Add assets and quantities and then they will be shown on the pie chart.

Price source:  binance & mexc.

Data will auto update pre 1min.

Support CN/EN multiple lagunage.

Embrace AI && Chaning Life. 


![image](https://github.com/user-attachments/assets/0e9de787-b932-4559-be69-13494b6a4220)

# 猪兔资金过山车图

一个简单的资金曲线追踪工具。

## 数据存储

数据以两种方式存储：
1. 浏览器的 localStorage 中
2. 本地的 data/chart_data.json 文件中

数据文件不会被提交到版本控制系统中，以保护隐私。

## 使用方法

1. 打开 chart.html 文件
2. 输入日期和金额数据
3. 数据会自动保存在浏览器中
4. 点击"添加数据"后会自动下载数据文件备份
5. 需要恢复数据时，点击"加载数据文件"并选择之前的备份文件

## 数据备份

- 每次添加或删除数据时都会自动下载数据文件
- 数据文件格式为 JSON
- 建议定期备份数据文件

## 开发说明

- 请不要提交 data 目录中的文件
- 保持 data/.gitkeep 文件以维持目录结构
