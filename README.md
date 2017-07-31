準備： 1.需要翻牆 2.需要提前安裝 node.js

安裝 Google Fonts Downloader 我們通過安裝google-fonts-downloader來下載google font，在終端輸入以下命令進行全局安裝：

npm -g install google-fonts-downloader

安裝完成之後，就可以下載我們需要的自己文件了，格式：ttf,eot,woff,woff2,svg

下載字體 比如目前需要使用的：

我們可以輸入以下命名（在翻牆的狀態下進行）

gfdownloader Source+Sans+Pro:300,400,600,900
正常情況下，下載完會有如下提示：

C:\Users\Administrator>gfdownloader Source+Sans+Pro:300,400,600,900 Requesting CSS http://fonts.googleapis.com/css?family=Source+Sans+Pro:300,400,600,900 (none) Found 4 fonts: Requesting CSS http://fonts.googleapis.com/css?family=Source+Sans+Pro:300,400,600,900 Mozilla/5.0 (X11; Ubuntu; Linux x86_64; rv:27.0) Gecko/20100101 Firefox/27.0 Found 4 fonts: Requesting CSS http://fonts.googleapis.com/css?family=Source+Sans+Pro:300,400,600,900 Mozilla/4.0(compatible; MSIE 7.0b; Windows NT 6.0) Found 1 fonts: Requesting CSS http://fonts.googleapis.com/css?family=Source+Sans+Pro:300,400,600,900 Mozilla/5.0 (iPad; U; CPU OS 3_2 like Mac OS X; en-us) AppleWebKit/531.21.10 (KHTML, like Gecko) Version/4.0.4 Mobile/7B334b Safari/531.21.10 Found 1 fonts:

這樣文件就已經下載完成了，字體文件在C:\Users\Administrator（該目錄請看自己執行目錄）

這樣就可以把字體文件拷貝到項目當中或者自己服務器，做為公用字體文件，在css裏面進行引用即可。
