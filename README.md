# VT_translation
Vector Thrustの日本語化  
多分多々間違ってる箇所があるので指摘あれば直します
https://blog.sky-net.pw/article/44

# 導入
1. 適当なttfフォントを用意する  
テストは[IPA明朝フォント](http://mojikiban.ipa.go.jp/1300.html)で行ってます
2. ファイルを配置する  
/がゲームインストールディレクトリです
  - Lang_JP.ini  
  /Language/Lang_JP.ini
  - Font_Lang_JP.ini  
  /Language/Font_Lang_JP.ini
  - core_font_jp.xml  
  /media/MyGUI_Media/core_font_jp.xml
  - core_language.xml  
  上書きまたは差分を自分で編集する  
  /media/MyGUI_Media/core_language.xml  
  - core_language_japanese.txt  
  /media/MyGUI_Media/core_language_japanese.txt
  - 用意したフォント  
  jp.ttfにリネームして配置  
  /media/MyGUI_Media/jp.ttf
3. 設定の変更  
ゲームを起動してOption -> Display Optionから言語をJapaneseに変更して保存する
4. 再起動
ゲームを再起動いてメニューなどが日本語化されてたら終わり

# 訳文の修正
Lang_JP.iniに訳文が格納されているのでこれを適宜編集してゲームを再起動すると反映されます
