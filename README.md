# ergo_cursor
ergo cursor 手順書

自作キーボードキット「ergo cursor」の組み立て方とファームウェア等を置いてます。

【仕様】
メインPCB (ダイオード1N4148W実装済み)
TOPケース用PCB
サンドイッチ用ボトムPCB
ボトム用PCB
各2枚

M2ネジ

ロータリーエンコーダースイッチ (E11) ×2
本キットではロータリーエンコーダースイッチをご使用いただけます。
音量ボリュームやLEDの切替など使用の幅が広がります。
スイッチとの間隔をある程度空けてありますので 3㎝キャップまでは対応。お好みのサイズのキャップを探してみてください。

【ご自分で用意するもの】
raspberry pi pico ×2
20ピンコネクタ × 4

【オプション】
※キースイッチ　36キー(片手分) 両手合計72キー
・GATERON low profile switches 2.0 、nuphy low profile switches
　専用ソケットになる為、Cherry MXやKailh Chocはご使用になれません。

※LED
アンダーグローLED ×8
バックライトLED 37
SK6812MINI-E × 90 (片手分) 両手合計180個
ファームウェアにPRK Firmwareを使用している関係上(作成時の仕様ではLEDが共通1回路の為)、アンダーグローのみ・もしくはアンダーグロー＆バックライトのどちらかとなります。
オプションとなりますのでもちろんLEDなしでもお使いいただけます。
フルカラーバックライトが楽しめるので使用を強く推奨。
