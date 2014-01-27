# foot-mouse
## sfc2013-design-strategy
This document is made by [gitfab](http://gitfab.org)
---
#概要
足で操作できるマウス．キーボードを使いながらのマウス操作が可能．

- こんな時に便利！
 - Officeを使うとき
 - ネットサーフィン

<a href="http://creativecommons.org/licenses/by/4.0/deed.ja"></a><a href="http://creativecommons.org/licenses/by/4.0/deed.ja"><img alt="クリエイティブ・コモンズ・ライセンス" style="width:88px;border-width:0;" src="http://i.creativecommons.org/l/by/4.0/88x31.png"></a>

![image.jpg](https://raw.github.com/malt03/foot-mouse/master/gitfab/resources/image.jpg)

---
# 材料

- ここからダウンロードするもの
 - stl_files.zip
 - 3dm_files.zip (Rhinocerosを使ってアレンジする人)

- 用意するもの
 - どこの家庭にでもあるようなビニールテープ
 - どこの家庭にでもある[PC-KM5435](https://www.google.co.jp/search?q=pc-km5435)を2個
 - どこの家庭にでもあるような3Dプリンター
 - 100円ショップの写真のようなスリッパ．
 - スリッパの厚みより長い2mmぐらいのドリル付きタッピングビス4本

- あると良いもの
 - [Rhinoceros](http://www.rhino3d.co.jp/)
---
#作り方
- 準備
 - ダウンロードしたstl_files.zipの中にあるmouse.stlとclick.stlを3Dプリンターで印刷する．
 - PC-KM5435を分解して，1つは基板を取り出し，1つは上の蓋だけ外しておく．

- click.stl
 1. click.stlから出来た方に基板を入れ，ビニールテープで写真のように固定する．
 2. 左クリックのボタンに突起があたって，クリック出来ることを確認して完成．

- mouse.stl
 1. 外した蓋の代わりに印刷したmouse.stlをはめ，ネジ止めする．
 2. 上部をビニールテープで止める．
 3. スリッパに3ヶ所ネジ止めする． 
 4. ちゃんとスクロール出来ることを確認して完成．
---
#デモ
日常的に使っていたら，体重をかけた時に壊れてしまいました…，疲労かと思います…．  
5. 課題に書きましたが，さすがに薄くしすぎたようです．  
そのためデモはありません…．
---
#課題
実際に作って課題が多数見つかりました．Rhinocerosを使える人に改善してもらえることを期待します．括弧内は実際に使っていた時の対処法です．

- mouse.stl
 - 床だとマウスが動きづらい → レーザー式に換える(下に大きいマウスパッドを敷く)
 - 角度が悪くて足が攣りそうになる → 角度をもう少し急にする
 - 基板が固定されていないのでずれて使えなくなる → 固定するための突起を作る(優しく扱う/ボールの穴から指を突っ込めば直せる)
 - 印刷を早くするためとはいえさすがに薄すぎる → 厚くする

- click.stl
 - 本体が軽くて固定されない → 重い物を下側に取り付ける(ビニールテープで床に固定)
 - クリックしっぱなしになることがある → バネを取り付ける機構を作る(軽く押すよう心がける)
 - 蓋がずれる → 蝶番を取り付ける機構を作る(上同)
---
#ダウンロード

[stl_files.zip](https://raw.github.com/malt03/foot-mouse/master/gitfab/resources/stl_files.zip)

[3dm_files.zip](https://raw.github.com/malt03/foot-mouse/master/gitfab/resources/3dm_files.zip)

[mouse.stl](https://raw.github.com/malt03/foot-mouse/master/gitfab/resources/mouse.stl)

[click.stl](https://raw.github.com/malt03/foot-mouse/master/gitfab/resources/click.stl)
---
