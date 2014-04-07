testWebAir
==========

測試 web 技術 (jQueryMobile, AngularJs)run 在 air 平台上

git　內容只有 FD 專案 的 bin　而已
其實　FD 並沒有針對 web+Air 的專案類型
所以 FD 一定會做 compile, 所以 src 下　預設的 main.mxml(預設的document class) 不能砍
但在打包時可以先砍掉 main.swf

直接把 html,js,css 等放在　bin　下就好
修改 application.xml 的 <content> xxxx </content>  <- main.mxml 改 myMain.html

