# code-03-05
- 機能：一度手をかざすとシャッター開、もう一度手をかざすとシャッター閉動作
- プログラム言語：Node-RED
- 追加デバイス：　Indoor Corgy製　RPZ-PIRS (Raspberry Pi用 人感/明るさセンサー/赤外線 拡張基板)　https://www.indoorcorgielec.com/products/rpz-pirs/
- 追加ノードモジュール：node-red-node-pi-gpio(version: 2.0.6)
- source code: flows-03-05.json
- 備考：前回行った機器制御（開動作、閉動作）を記憶するため、flowコンテキスト（on_off_flag）を設定、利用しています

![image](https://github.com/foobarbazfred/ProgrammingExamples/blob/main/code-03-05/code-03-05.png)

# code-03-05-kai
- 機能等：code-03-05と基本的に同じ
- 変更点：LEDの点灯、消灯の仕様を変更
  - code-03-05: 機器操作状態を表す（機器をONにした時LED点灯、機器をOFFにした時LED消灯）
  - code-03-05-kai: 操作要求受理を表す（手をかざして検知したらLED点灯、一定時間経過後消灯）
- source code: flows-03-05-kai.json

![image](https://github.com/foobarbazfred/ProgrammingExamples/blob/main/code-03-05/code-03-05-kai.png)
