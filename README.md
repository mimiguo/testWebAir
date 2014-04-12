testWebAir
==========

測試 web 技術 (html5, js, jQueryMobile, AngularJs 等) run 在 air 平台上

git上只有放 FD 專案 的 bin(runtime)　而已
其實　FD 並沒有針對 web+Air 的專案類型

Adobe 好像是推薦用 dreamweavr 來做這樣的開發 
我電腦上的 flashbuilder 4.5 
好像也看不到適合的專案類型

所以 FD 一定會做 compile, 所以 src 下　預設的 main.mxml(預設的document class) 不能砍
但在打包時可以先砍掉 main.swf

直接把 html,js,css 等放在　bin　下就好
修改 application.xml 的 <content> xxxx </content>  <- main.mxml 改 myMain.html

測試 csshake(http://elrumordelaluz.github.io/csshake/#6) 
結果不行 完全沒有效果 但用 browser (FireFox)開確實ok

測試 jQueryMobile 
ok
排版 Air上就如同在 FF 上 
也同樣有 responsive web design 的效果 
版型看起來都還蠻漂亮的
但仍有差異 
例如 在 FF 上看得到當focus 在btn上時 會有 微微光暈效果的地方 在Air上看不到光暈

測試 AngularJs
貼上 官網 http://angularjs.org/ 首頁上的 幾個 sample 
basic 跟 todoList 也都正常
