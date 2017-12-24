# ChristmasKanojo
![sample](https://camo.qiitausercontent.com/ec932dd311da1d3b1a0436b3457503d1f7715576/68747470733a2f2f71696974612d696d6167652d73746f72652e73332e616d617a6f6e6177732e636f6d2f302f3130343337372f66643430313737622d363565312d383431302d623933312d6561643937343730333937372e706e67)

こちらは[UE4でVR空間にカノジョを錬金する Advent Calendar 2017](https://qiita.com/advent-calendar/2017/ue4vrgame-create)の期間内で作成したVRサンプルプロジェクトになります。

このプロジェクトはXR GameJam in Japan 2017 Autumn東京会場にて２日間で作成したコンテンツ「クリスマスカノジョ」に、呼吸アニメーションとリップシンクの実装を加えています。

# 実装詳細
実装内容の詳細はUE4でVR空間にカノジョを錬金する Advent Calendar 2017に全て記述しています。<br />
詳しくは[カレンダー](https://qiita.com/advent-calendar/2017/ue4vrgame-create)をご覧ください。

# 開発環境
Windwos10<br />
UnrealEngine4.18<br />
Oculus Rift + Oculus Touch<br />

※ソースを見るためには**UnrealEngine4**が必要です。バージョンは18になります。<br />
※動作を確認するには、**Oculus Rift**が必要です。

# 諸注意

このプロジェクトデータにはいくつか注意していただきたい点があります。

## **FPSの最適化は行われていません**

※極めて重要

こちらのプロジェクトは30時間という極めて短い開発時間で欲しい機能を実装するために、重いとわかっていても簡単に実装できるのであれば仕方ないと割り切ってプログラムを組んでいます。<br />
その後もゲームジャムで実装したかった機能の検証しか行っていないため、12/25時点で最適化は一切行っていません。

※Tickイベントに色々重い処理を繋げているため、45fpsぐらいしかでません。<br />
※負荷の解析も行っていないので、他にもボトルネックになっている部分はあると思います。

このサンプルをそのまま利用してもストアにはリリースできないので、あくまでの実装の参考にしてください。

## 使用する場合、ユニティちゃんライセンスとグレイちゃんの利用規約を守ってください

このプロジェクトにはユニティちゃんのデータとグレイちゃんのデータが入っています。<br />
[ユニティちゃんライセンス](http://unity-chan.com/contents/license_jp/)と[グレイちゃんの利用規約](http://rarihoma.xvs.jp/products/graychan)を継承していますので、使用する場合は必ず守ってください。

## マテリアルについて
一部マテリアルに以下のを使用しています。　※プロジェクトに入っています。

[NPR_Materials_20161207.CelAnim.ver0.5.zip](https://epicgames.app.box.com/s/2ldnpzuwomyiu19vmjl2fzfp2f100rl0)

## 有料アセットについて
以下の有料アセットを使用しています。（このプロジェクトでは含まれていません）

[Christmas Holiday](https://qiita.com/advent-calendar/2017/ue4vrgame-create)

© Unity Technologies Japan/UCL
