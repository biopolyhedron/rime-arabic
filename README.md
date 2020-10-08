# rime-arabic
arabic.schema.yaml和arabic.dict.yaml爲rime阿拉伯字母國際鍵盤  
形碼原則，qwerty鍵盤。  
字母性上標（或取消上標）以'/'先導；  
字母性下標（或取消下標）以'\\'先導；  
雙橫點上標直接寫'"'；  
hamza上標直接寫'\''；  
三點上標直接寫'^'；  
alif madda直接寫'a~'；  
少量變形字母以'C'後綴；  
向下三點上下標寫/c或\c；  
hamza及阿拉伯系一些符号（如分号؛）以'v'先導；  
阿拉伯數字以'v'先導再加相應數字的上檔鍵；  
獨立unicode附屬上標以'x'爲先導；獨立unicode附屬下標以'X'先導；  
unicode獨立上標以'v/'爲先導；  
unicode獨立下標以'v\'爲先導；  
部分鍵位有衝突的ascii字符本體（拉丁系）用';'先導，如【^ ' " ` , ; / : \ ~】。  
先導：x X v ; \ /；  
後標：C ^ ' " ~。  

arabic_zhihu.schema.yaml和arabic_zhihu.dict.yaml爲知乎用的防過濾的輸入法，
目前僅包含阿拉伯、波斯和維吾爾文字母。
通過避免普通的阿拉伯字母而使用變形後的Unicode碼區來避免被過濾。
字符前後加 '\`' 以切斷前連和後連。
具體說明見 https://zhuanlan.zhihu.com/p/263076011 。

#例子
（阿拉伯字母國際）
السلام عليكم.  
alslam Elykm.  
اَلسَّلَامُ عَلَيْكُمْ.   
aAlsWAlAamU EAlAyOkUmO.  
ياخشمۇسىز.  
yaH/.s^imusiz.  

（阿拉伯字母知乎）
ﺍﻟﺴﻼﻡ ﻋﻠﻴﻜﻢ.
\`a\`lsla\`m\` \`Elykm\`.
