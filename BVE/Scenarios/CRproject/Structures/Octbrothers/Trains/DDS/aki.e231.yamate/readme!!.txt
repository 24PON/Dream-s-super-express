この度はダウンロードして頂き有難うございます．

★ストラクチャファイルについて
aki.e231.yamateの中には8のストラクチャファイルがあります．
yamate.tcF.x		//先頭車(前照灯点灯)
yamate.tcFB.x		//先頭車(標識灯点灯)
yamate.tcR.x		//最後尾(前照灯点灯)
yamate.tcRB.x		//最後尾(標識灯点灯)
yamate.midA.x		//中間車
yamatex.midB.x		//中間車
yamate.midMA.x		//パンタ付中間車
yamate.midMB.x		//パンタ付中間車

またmidA，midBなどの最後のアルファベットは向きを表します．
midA，midMAが大崎基準、手前が渋谷方
midB，midMBが大崎基準、手前が品川方
となっています．

★他列車ファイルについて
以下の他列車ファイルを同梱しています．
yamate.e231.A.txt		//東京総合車両センター11両・大崎基準、手前が渋谷方
yamate.e231.B.txt		//東京総合車両センター11両・大崎基準、手前が品川方

いずれも、手前側が前照灯点灯としています。
並走する場合（標識灯をつける場合）は他列車ファイルの先頭車を
yamate.tcFからyamate.tcFBに書き換えてください。以下に例を示します。

[Structure]
Key = yamate.tcF　⇒　yamate.tcFB　に書き換えると標識灯点灯になります
Distance = 2.85
Span = 13.8
Z = -2.85


これらの他列車ファイルを使用するためにはストラクチャリストに以下を追加してください．

yamate.A.midA,aki.e231.yamate\yamate.midA.x
yamate.A.midB,aki.e231.yamate\yamate.midB.x
yamate.A.midMA,aki.e231.yamate\yamate.midMA.x
yamate.A.midMB,aki.e231.yamate\yamate.midMB.x
yamate.A.tcF,aki.e231.yamate\yamate.tcF.x
yamate.A.tcFB,aki.e231.yamate\yamate.tcFB.x
yamate.A.tcR,aki.e231.yamate\yamate.tcR.x
yamate.A.tcRB,aki.e231.yamate\yamate.tcRB.x

★前面行先表示について
標準では行先、列車番号は無表示です。
前面テクスチャを差し替えることで以下の2種類の行先に変更できます。
【品川渋谷方面】【東京上野方面】
なおいずれも列車番号を【0000G】としています。
例えば、
【渋谷品川方面】e231.yamate.head.A.pngをe231.yamate.head.A.pngとファイル名を変更すれば、前照灯点灯の渋谷品川方面行きとすることができます。

なお、行先や列番表示についてのリクエスト等は受けかねます。

★その他
床下は再現されていません．

また，その他にも現実と異なる点も多々ありますがそれを許容できる方のみ使用してください．

BVE5での使用を想定しています．それ以外はサポートしません．

このファイルの再配布は禁止とします．
もし路線などに組み込んで公開する際はご連絡ください．
連絡はブログ（readme最下部のリンク参照）のコメントにお願いします．
使用して下さった感想なども下さると喜びます＾＾
ご遠慮なくお書き込みください＾＾

・・・・・・・・・・・・・・・・・・・・
製作：aki
URL：http://akipokorin777.blog76.fc2.com/
・・・・・・・・・・・・・・・・・・・・
