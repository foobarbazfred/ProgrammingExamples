# サンプルコード

SmartHomeSimulatorを使ってプログラミング演習を行うためのサンプルコードを紹介します。以下はNode-REDを使ったプログラムの例です。動作確認はRaspberryPi + Node.js + Node-REDの環境で行っていますが、WindowsPC上でもNode.js, Node-REDをインストールすればRPi同様に動作可能と思います。

- [code-02-01](code-02-01)
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
- code-03-02
  - 手をかざすとLEDが点灯するプログラム
- code-03-03
  - 手をかざすとシャッターが開くプログラム
- code-03-04
  - 一度手をかざすとLED On、もう一度手をかざすとLED Off
- code-03-05
  - 一度手をかざすとシャッター開、もう一度手をかざすとシャッター閉動作

上記はRaspberryPy上で動作するNode-REDを使ってSmartHomeSimulatorを制御するサンプルコードです。RaspberryPi上でPythonを走らせて同様に制御することもできます。

- code-03-01以降は、人感センサが搭載されたRPi用の拡張基板が必要です。
  - Indoor Corgy製　RPZ-PIRS (Raspberry Pi用 人感/明るさセンサー/赤外線 拡張基板)　https://www.indoorcorgielec.com/products/rpz-pirs/
- RPiのGPIOを制御できる拡張モジュールnode-red-node-pi-gpioが必要です。
  - https://github.com/node-red/node-red-nodes/tree/master/hardware/PiGpio
