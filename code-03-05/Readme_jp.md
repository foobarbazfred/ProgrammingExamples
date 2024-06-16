# code-03-05
- 機能：一度手をかざすとシャッター開、もう一度手をかざすとシャッター閉動作
- プログラム言語：Node-RED
- 追加デバイス：　Indoor Corgy製　RPZ-PIRS (Raspberry Pi用 人感/明るさセンサー/赤外線 拡張基板)　https://www.indoorcorgielec.com/products/rpz-pirs/
- 追加ノードモジュール：node-red-node-pi-gpio
- source code: flows-03-05.json
- 備考：前回行った機器制御（開動作、閉動作）を記憶するため、flowコンテキスト（on_off_flag）を設定、利用しています

![image](https://github.com/foobarbazfred/ProgrammingExamples/blob/main/code-03-05/code-03-05.png)
