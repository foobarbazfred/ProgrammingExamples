# code-03-04
- 機能：一度手をかざすとLED On、もう一度手をかざすとLED Off
- プログラム言語：Node-RED
- 追加デバイス：　Indoor Corgy製　RPZ-PIRS (Raspberry Pi用 人感/明るさセンサー/赤外線 拡張基板)　https://www.indoorcorgielec.com/products/rpz-pirs/
- 追加ノードモジュール：node-red-node-pi-gpio
- source code: flows-03-04.json
- 備考：前回行ったLED制御（On, Off）を記憶するため、flowコンテキスト（on_off_flag）を設定、利用しています

![image](https://github.com/foobarbazfred/ProgrammingExamples/blob/main/code-03-04/code-03-04.png)
