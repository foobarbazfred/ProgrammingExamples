# code-03-02
- 機能：手をかざすとLEDが点灯するプログラム
- プログラム言語：Node-RED
- 追加デバイス：　Indoor Corgy製　RPZ-PIRS (Raspberry Pi用 人感/明るさセンサー/赤外線 拡張基板)　https://www.indoorcorgielec.com/products/rpz-pirs/
- 追加ノードモジュール：node-red-node-pi-gpio(version: 2.0.6)
- source code: flows-03-02.json
- 備考：自動消灯機能付き（５秒周期で消灯操作）

![image](https://github.com/foobarbazfred/ProgrammingExamples/blob/main/code-03-02/code-03-02.png)

# code-03-02-kai
- 機能：手をかざすとLEDが点灯するプログラム(改良版)
- プログラム言語：Node-RED
- source code: flows-03-02-kai.json
- 改良点：人感センサによる検知を起点に５秒後に消灯(code-03-02では周期的に消灯している) 

![image](https://github.com/foobarbazfred/ProgrammingExamples/blob/main/code-03-02/code-03-02-kai.png)

