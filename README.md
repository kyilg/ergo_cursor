# ergo_cursor
ergo cursor 手順書

自作キーボードキット「ergo cursor」の組み立て方とファームウェア等を置いてます。<br>
<br>
【仕様】<br>
メインPCB (ダイオード1N4148W実装済み)<br>
TOPケース用PCB<br>
サンドイッチ用ボトムPCB<br>
ボトム用PCB<br>
各2枚<br>
![1 TOP_R](https://github.com/kyilg/ergo_cursor/assets/46878795/1fba9af6-dfbb-4e50-8395-0aca81d80610)
![1 TOP_L](https://github.com/kyilg/ergo_cursor/assets/46878795/acb8ccdc-7fc9-4db9-8924-9ac981cc3336)<br>
![2 MAIN_R](https://github.com/kyilg/ergo_cursor/assets/46878795/25c9c883-b0da-43d4-80bc-1ab463349c55)
![2 MAIN_L](https://github.com/kyilg/ergo_cursor/assets/46878795/80c15997-34ce-42b7-ab6f-48d2a1af87c6)<br>
<br>
M2ネジ<br>
<br>
ロータリーエンコーダースイッチ (E11) ×2<br>
本キットではロータリーエンコーダースイッチをご使用いただけます。<br>
音量ボリュームやLEDの切替など使用の幅が広がります。<br>
スイッチとの間隔をある程度空けてありますので 3㎝キャップまでは対応。お好みのサイズのキャップを探してみてください。<br>
<br>
【ご自分で用意するもの】<br>
raspberry pi pico ×2<br>
20ピンコネクタ × 4<br>
<br>
【オプション】<br>
※キースイッチ　36キー(片手分) 両手合計72キー<br>
・GATERON low profile switches 2.0 、nuphy low profile switches<br>
　専用ソケットになる為、Cherry MXやKailh Chocはご使用になれません。<br>
<br>
※LED<br>
アンダーグローLED ×8<br>
バックライトLED 37<br>
SK6812MINI-E × 90 (片手分) 両手合計180個<br>
ファームウェアにPRK Firmwareを使用している関係上(作成時の仕様ではLEDが共通1回路の為)、アンダーグローのみ・もしくはアンダーグロー＆バックライトのどちらかとなります。<br>
オプションとなりますのでもちろんLEDなしでもお使いいただけます。<br>
フルカラーバックライトが楽しめるので使用を強く推奨。<br>
<br>
