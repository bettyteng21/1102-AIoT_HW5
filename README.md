# 1102-AIoT_HW5

# 5/17
1. 連接github到vscode(要用新版的vs code)

**[法1]**\
```	git clone: https://github.com/bettyteng21/1102-AIoT.git```
  

**[法2]**
```
echo "# 0517" >> README.md
	git init
	git add README.md
	git commit -m "first commit"
	git branch -M main
	git remote add origin https://github.com/huanchen1107/0517.git
	git push -u origin main
```
  
2. 在vs code安裝python extension module: ```pip install flask```
3. using google colab with github\
	[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/googlecolab/colabtools/blob/master/notebooks/colab-github-demo.ipynb)

4. run [老師寫的colab框架](https://github.com/huanchen1107/AIoT_2022)，即可用colab跑

# 作業五
**作業五的step by step的pdf，可以看pdf**
1. 開啟 xampp，啟動 sql 和 apache
2. 照老師之前的教案，新增兩個使用者(密碼皆為: test123)
3. 匯入老師給的 sensors 
4. 建一個 python 檔案，要含 templates 資料夾
5. 開始撰寫 main.py，先連接資料庫，再指定要什麼資料，最後 render 到 templates 裡的 index.html
6. 修改老師之前教案給的 index.html，直接把剛剛在資料庫拿到的資料放到 data
7. 繪製 highchart 的部分就和老師之前提供的檔案一樣，沒有改
8. 最後得出有三條線 temps、lights、humids 的 highchart

