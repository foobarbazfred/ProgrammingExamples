# サンプルプログラム

SmartHomeSimulatorを使ってプログラミング演習を行うためのサンプルコードを紹介します。以下はNode-REDを使ったプログラムの例です。動作確認はRaspberryPi + Node.js + Node-REDの環境で行っていますが、WindowsPC上でもNode.js, Node-REDをインストールすれば同様に動作可能と思います。

- code-02-01
  - Node-REDによるシンプルなサンプルコード (Hello world!)
- code-02-02
  - ECHONET Lite Web API を使うサンプルコード
- code-02-03
  - 電気錠が解錠されるとシャッターが開くサンプル
- code-02-04
  - 電気錠が解錠されるとシャッターが開くサンプル(一定時間経過後、電気錠が施錠されていない場合、自動施錠する)
- code-02-05
  - MQTTを使って遠隔から自宅のエアコンを制御する
- code-02-06
  - MQTTを使って遠隔から自宅のシャッタを制御する
- code-03-01
  - Node-RED からRaspberry PiのGPIOを制御するサンプルコード
  - 注：プログラム実行にはRPi用の拡張基板が必要です

上記はNode-REDによるサンプルですが、Pythonを使ってSmartHomeSimulatorを制御することもできます。
