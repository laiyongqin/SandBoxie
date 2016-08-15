### ひな形 コピー＆ペースとして, 使用して下さい。
## ↓
***
* 追加内容
	- 

* bugfix
	- 

* 参考サイト
	- [Markdown 記法 サンプル集](http://qiita.com/tbpgr/items/989c6badefff69377da7)

#### 記述者 : 氏名, 記述日 : 年月日 日時
***
***
### 過去のChangelog.mdファイルは, Archive01_Changelog.md
### として, ルート直下に置いてありますので, 併せて確認下さい。
### ファイル容量が20KBに達したら, 連番でArchiveしていきます。
### 最新のログは, Changelog.mdとします。
***
***
***
***
* 追加内容
	- ブロック　白_改 キューブをレベル上に置いて, ビルドすると, 
        黒く焼けてしまう事象を, DirectionalLight の詳細タブにある
        Light→シャドウを落とすのチェックを外し解決した。
    - ThirdPersonブループリント→Tutorial02_2DMapの読み込みとunload処理
        →処理内容コメントの追加＆Tutorial02_2DMapのロード・アンロード処理に変更した。
        ロード・アンロード処理の境界線を調整した。
    - ThirdPersonブループリント→Tutorial03_2DMapの読み込みとunload処理
        →Tutorial03_2DMapのロード・アンロード処理に追加した。

* bugfix
	- とくになし。

* 参考サイト
	- [Markdown 記法 サンプル集](http://qiita.com/tbpgr/items/989c6badefff69377da7)
    - [アンリアル エディタでファイルをチェックアウトする(GIT HUB)](https://docs.unrealengine.com/latest/JPN/Engine/Basics/SourceControl/InEditor/index.html)
    - [warning: refname 'HEAD' is ambiguous(GIT HUB)](https://gotohayato.com/content/11)

#### 記述者 : 牛山 拓成, 記述日 : 2016年08月01日(月) 午前2時04分
***
* 追加内容
	- TestStage系統マップで制作したマップを間違って編集し, 壊さないために, 編集できないようにロックを掛けました。
    - 平田が制作した, チュートリアル 3DMAP を基に, Tutorial01_3DMap, Tutorial02_3DMap, Tutorial03_3DMap
        に牛山がそれぞれ分けて格納しました。制作したマップに不備があったので一部, 修正を行いました。
    - ThirdPersonブループリント→レベル起動時に, 2Dから3Dに切り替えたときに, 2DMAPが消え, Yを真ん中の座標にし, 落ちるのを防いでいる処理
        を追加しました。
    - ThirdPersonブループリント→レベル入れ替え&3D座標位置維持
        に Tutorial01 ～ 03 までの 2DMAP のアンロード処理を追加しました。
    - ThirdPersonブループリント→2DMAP時のレベル変更処理
        で Tutorial01_2DMap をロード, Tutorial01_3DMap をアンロードする処理を追加しました。
    - チュートリアルマップの 3D の 1 ～ 3 マップで, レベルのロード・アンロード処理を追加しました。
        ここまでの, 作業により, チュートリアルマップ 2D, 3D 全体で, 動作するようになりました。
    - パーシスタントレベルに, ブロックの表示・非表示処理を追加しました。
    - Mesh フォルダにやすさんから, maya で作成した, Materialを多数追加しました。
        Mesh などに色を適用したい場合は, このフォルダを使うと良いかもしれません。
    - __今回, 追加した機能が多いので, 書き切れてない部分があります。
        競合が発生した場合は, Unreal Engine の DIFF の機能を試して見て下さい。__
        

* bugfix
	- _Tutorial03_3DMap の特定箇所で, カメラ切り替えすると, Player が, アクターにハマってしまう
        事象が確認されたため, BoxTrigger を 2 カ所に配置しました。
        まだ, Trigger 処理 を書いていないので, 次回は, ここから対処していく。_

* 参考サイト
	- [Statick Mesh の表示・非表示処理の仕方参考サイト](https://answers.unrealengine.com/questions/262267/set-visibility-set-actor-hidden-in-game-switches-f.html)

#### 記述者 : 牛山 拓成, 記述日 : 2016年08月02日(火) 午後4時56分
***
* 追加内容
	- 「Tutorial03_2DMap, Tutorial02_3DMap, Tutorial03_3DMap」のレベルブループリントに,
        カメラの切り替えが出来る地点, カメラの切り替えが出来ない地点 を追加した。また, これらのレベル
        に, トリガーボックスを幾つかの地点に配置しました。
    - 現時点でのマップ構成での, Characterが, Map上で, カメラの切り替えをすると, 不整合を起こす事象を全て改善しました。

* bugfix
	- _「Tutorial03_3DMap の特定箇所で, カメラ切り替えすると, Player が, アクターにハマってしまう
        事象が確認されたため, BoxTrigger を 2 カ所に配置しました。
        まだ, Trigger 処理 を書いていないので, 次回は, ここから対処していく。」_ __解決しました。___

* 参考サイト
	- とくになし。

#### 記述者 : 牛山 拓成, 記述日 : 2016年08月11日(木) 午後6時16分
***
* 追加内容
	- __Changelog.md__ と __README.md__ の誤字＆脱字を修正しました。詳しい修正箇所は
		, 変更履歴を見てください。

* bugfix
	- とくになし。

* 参考サイト
	- とくになし。

#### 記述者 : 牛山 拓成, 記述日 : 2016年08月16日(火) 午前0時55分