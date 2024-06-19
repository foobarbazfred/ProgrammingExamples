# code-03-01
- 機能：Node-RED からRaspberry PiのGPIOを制御するサンプルコード
  - LEDを点灯させる　（通称Lチカ）
  - SWの押下を取得する
  - IRセンサの値を取得する
  - SWを押下するとLEDが点灯する
- プログラム言語：Node-RED
- 追加デバイス：　Indoor Corgy製　RPZ-PIRS (Raspberry Pi用 人感/明るさセンサー/赤外線 拡張基板)　https://www.indoorcorgielec.com/products/rpz-pirs/
- 追加ノードモジュール：node-red-node-pi-gpio
  - module version: 2.0.6を使用しています。
    お使いのnode-red-node-pi-gpioモジュールが古いバージョンの場合、最新に上げないとピン番号が正しく設定されない可能性があります
    (Pin番号か、機能名(BCM)かの仕様が変わったように思える）
- source code: flows-03-01.json

![image](https://github.com/foobarbazfred/ProgrammingExamples/blob/main/code-03-01/code-03-01.png)
