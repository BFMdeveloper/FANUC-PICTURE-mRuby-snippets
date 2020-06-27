# FANUC-PICTURE-mRuby-snippets
包含FANUC-PICTURE 8.0以后版本的mRuby的函数片段
## 代码片段
    脚本分段
    if AGR[] == x then
    画面切换
    :symbol: = "画面号"
    swscreen(0, 100 + :symbol(1):, :symbol(2):, 0, 99, 0)   
## FANUC PICTURE 函数