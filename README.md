# PinyinIME
google 拼音输入法 android studio可编译

已对原生输入法修改布局和键盘切换方式

skb_qwerty.xml 字母键盘 可切换大小写

skb_sym1.xml   英文符号

skb_sym2.xml   中文符号

skb_template   键盘模板 可根据id和key设置样式

               balloon 设置是否有点击气泡
               
               repeat 是否可长按
               
               toggle_state 切换状态
              
切换背景图在SkbContainer->changeBackGround()方法中\n

切换输入法在 InputMethodSwitcher-> requestInputWithHkb(EditorInfo editorInfo)方法中