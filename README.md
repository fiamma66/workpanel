# Workpanel

Base On [ebisuke/TosAddons](https://github.com/ebisuke/TosAddons)

Fix and Translate

--------------

各種レイド・チャレンジに入るためのパネルを表示します
## 概要
画面右上に＜＜ボタンが表示されていますのでそれをクリックすると各種インスタンスダンジョンに入るためのボタンが表示されます。
- Singularity : 分裂特異点自動マッチ(チャレンジモードハード)
- Challenge : チャレンジモード自動マッチ
- Moring : モリングフォニア自動レイド
- Witch : グレイシア自動レイド
- Giltine : ギルティネ自動レイド
- Vasillisa : ヴァシリーサ自動レイド
- Relic : レリックノーマル自動レイド
- Assister : アシスターダンジョン(ボタンの数字はステージ数です)
- Velnice : ヴェルニケの破片ダンジョン(ボタンの数字は入場回数です)
- Heroic : ヒロイックダンジョン
- Refresh : 表示を更新します。表示回数がおかしいときに押してください。
このとき、入場回数が不足している場合は傭兵団コインを使って入場券を購入し自動使用します。


再度＞＞を押すと小さくなります
# リリースノート

=======

## v0.2.11.1
* Translate & fix
  * Fix infinity repeat when Mercenary Badge is depleted

* Solo Vasilissa Will Not Buy Entry Voucher
* Add White Witch Entry Button
  * Will Not Buy Entry Voucher too!
* Solo Moring & Solo Vasilissa Add Auto Enter Dugeon

## v0.2.11
* レリックハードの回数がおかしいのを修正

## v0.2.10
* 先の修正で分裂券のバグが復活したので修正
## v0.2.9
* 要望によりモリングを復活
* レイヤレベルを下げた（ステータスより奥）
## v0.2.8
* モリングを削除
* ヒロイックの自動購入＆入場が効かないのを修正
## v0.2.7
* ソロレリック・ソロヴァシリーサに対応

## v0.2.6
* ルチャドールパッチの対応
* Refreshボタンの実装

## v0.2.5.1
* Fix & Translate
  * *Giltine* and *Res Sacrae Raid* entry now will auto buy Entry Voucher if no entry count left
  * Fix infinity repeat when Mercenary Badge is depleted

* Test/Add Function
  * Solo Vasilissa Entry
  * Solo Res Sacrae Raid Entry

## v0.2.5
* session.ResetItemList()を仕込んでみるテスト
## v0.2.4
* チケットがないときの無限再試行を抑止
## v0.2.3
* 相変わらずデイリー分裂県の交換回数がおかしいのを再度修正
## v0.2.2
* ITOSむけ小修正 新規ダンジョンにはまだ対応しません
## v0.2.1
* 導入されているアドオンが二重で読み込まれる問題の修正（ObjectDetectorなど他のアドオンに影響する問題です）
## v0.2.0
* EP13-2に対応
## v0.1.5
* レリックダンジョンに入場できないのを修正
## v0.1.4
* フリーズ対策としてヴェルニケのランキング表問い合わせ処理を削除。その代わりステージ数を表示できなくなるので代わりに入場回数を表示
* たまに交換回数が残っているのにないと表示される問題を修正したつもり
* 特定のレリックダンジョンを認識しないのを修正
## v0.1.2
* 町の外でも表示できるようにした（券の購入機能のみ使用可能）
* 各種券の自動購入使用機能追加
* レリックダンジョンの券購入機能を実装
* ウィークリーから先に使われてしまう問題を修正したつもり
* レイヤーレベルの調整
## v0.0.4
* モリング・魔女・ギルティネの回数が反映されないのを修正したつもり
## v0.0.3
* ヴェルニケの破片ダンジョンのステージ数を表示するよう変更
* 町以外では非表示に
* 一部表記変更
## v0.0.2
* デイリー入場券を購入しない問題を修正
* レリックダンジョンの入場回数がおかしいのを修正したつもり
## v0.0.1
初回
