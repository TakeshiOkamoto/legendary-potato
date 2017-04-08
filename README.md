# TESP8266
ArduinoでESP-WROOM-02(無線LAN)を使用して「URL(GET/POST)によるデータの送受信」をするライブラリです。

## 機能
・Wifi接続  
・HTTP GET/POST (データの送受信)  
など  
  
## 使い方  
現在、作成中です。4/8中にはリンクを張ると思います。
  
## 注意事項  
・スケッチ例(examples)では日本語(UTF8)を使用していますので、Arduino IDE 1.8.2以降をお使いください。  

Arduino IDEのメニューの[ファイル][スケッチ例][TESP8266]からサンプルのスケッチを開いた場合は、[ファイル][名前を付けて保存]で別の場所に保存してからコンパイルしてください。そのままコンパイルするとIDE 1.8.2では、UTF8に対応したばかりのバグで「文字化け」が発生します。  

## Author
Editor: Takeshi Okamoto

このライブラリはqoosky氏がMITライセンスで公開している

Arduino_HttpClient_ESP8266_AT 
Copyright (c) 2016 Qoosky  
https://github.com/qoosky/Arduino_HttpClient_ESP8266_AT  
  
の機能を拡張したライブラリです。  

[変更点]  
・get(),post()メソッドでファイルの受信にも対応。  
・DHCPの有効/無効に対応。(固定IPアドレスを指定可能になる)  
・(シリアルモニター)ESP-WROOM-02との接続時にバージョン情報を表示。  
・(シリアルモニター)Wifi接続時にIPアドレス、ゲートウェイ、ネットマスクを表示。    
・SoftwareSerialの廃止。HardwareSerialのみ有効。(文字化けの解消)  
・スケッチ例の変更、加筆、追加。  
など  
