---
title: "脱 KPT 法で楽しく有意義に振り返り! Sailboat Retrospective"
emoji: "⛵"
type: "idea" # tech: 技術記事 / idea: アイデア
topics: ["スクラム", "scrum", "振り返り", "retrospective", "アジャイル"]
published: false
publication_name: "hacobell_dev"
---

ハコベルシステム開発部の大石貴則です。普段はフロントエンドエンジニアとして物流 DX SaaS プロダクトの開発を行なっています。

最近、個人的に認定スクラムマスター (CSM®) を取得し、スクラムチームの改善に取り組んでいます。

この記事では私たちのスクラムチームでも導入した、スクラムのレトロスペクティブ (振り返り) 手法として海外で著名なフレームワーク Sailboat Retrospective (帆船の振り返り、帆船アジャイル手法) を紹介します。

## 背景

皆さんのスクラムチームでは、振り返りでどのフレームワークを使用していますか？

以前私たちは、KPT 法を使用していました。付箋を「Keep」「Problem」「Try」のカテゴリに分けて貼っていく手法です。

この手法では、ドキュメント化して報告しやすいという利点がありますが、次のデメリットがありました。

- 何を書けばいいのかわからない
- 短期的・長期的な事柄が混ざってしまう
- プロダクトゴール、スプリントゴール以外のことに話が発散してしまう
- 反省会になりがち

そこで、私たちのチームでは Sailboat Retrospective というフレームワークに切り替えました。

## Sailboat Retrospective とは

ゴールに向かっていく、海に浮かんだヨットをイメージしたイラストに付箋を貼っていきます。

ホワイトボードに下記の 6 つを絵で書き込みます。チームの特性に応じてカスタマイズできますが、チーム内で要素の意味に対して共通認識を持つようにしましょう。

| 要素              | 意味                                                          |
| ----------------- | ------------------------------------------------------------- |
| Sailboat (ヨット) | 進捗 (スプリント)                                             |
| Island (島)       | チームが達成したいゴール (プロダクトゴール・スプリントゴール) |
| Sun (太陽)        | 嬉しかったこと (ゴールと関係なくても OK)                      |
| Wind (追い風)     | ヨットを進める追い風、チャンス                                |
| Anchor (錨)       | ヨットを遅らせるブロッカー                                    |
| Reef (暗礁)       | ヨットを座礁させる将来的なリスク                              |

![Sailboat Retrospective のイラスト例。海の上にヨットのイラストが浮かんでおり、右の島のイラストに向かって進んでいる。空に太陽と追い風のイラストがある。海の下にはヨットに繋がれた錨のイラストがある。ヨットと島との間には暗礁のイラストがある。](/sailboat-retrospective/image01.png)

[Sailboat Retro](https://www.figma.com/community/file/967321073661280669) Created by [Brody](https://www.figma.com/@brody) (CC BY 4.0)

ホワイトボートツールであれば、テンプレートが用意されているのでまずはそのまま使えば OK です。

https://www.figma.com/community/file/967321073661280669

https://miro.com/ja/templates/sailboat-retrospective/

オフラインであれば、みんなでワイワイお絵描きするのがおすすめです。チームのムードが絵に現れます。

## アジェンダの例

私たちは下記のようなアジェンダで進行しています。進行はスクラムマスターが行っています。

1. 前の Sprint で設定したアクションを振り返る
   - アクションを取れた場合、付箋を剥がす
   - アクションを取れなかった場合は原因を議論して、キープするか別のアクションを取るか決定する
2. 4 分測り、各自で今の Sprint での出来事や感想などを付箋に書いて各要素に貼る
   - 時間足りなければ 1 分追加する
   - ホワイトボードツールで BGM を流して静まり返らないようにする
3. 各メンバーから順番に、貼った付箋について発表する
   - 他のメンバーは褒めたり、リアクションスタンプを押したりして盛り上げる
4. 1 分測り、各自で次の Sprint でのアクションを決めたい付箋にドット投票する
   - 投票数の制限は設けず、1 つの付箋に何票投票してもよいが、投票者は明確にする
5. 投票が多い順番で付箋をアクション欄に移し、次の Sprint でのアクションを議論する
   - スクラムマスターは議論の内容やアクションを別の付箋に書いて貼る
   - 次回は気をつけるなどの暗黙なアクションにはしない。Working Agreement (チームのルール) 化やユーザーストーリーの追加、修正など、残る形でのアクションにする

下記は、私たちのスクラムチームのホワイトボードです。FigJam を使用しています。

![Sailboat Retrospective のボードに付箋を貼った例。付箋にはいいね！などのスタンプを貼り付けている。島のイラスト付近には、スプリントゴールとプロダクトゴールを貼り付けている。太陽の右側に雲を新たに追加している。](/sailboat-retrospective/image02.png)

最初はテンプレートを活用していましたが、メンバーを意見から少しカスタマイズしています。

具体的には、島を 2 つに増やしスプリントゴール (短期的) とプロダクトゴール (長期的) に時間軸を広げました。

また、モヤモヤや気にかかることの共有を目的に `Cloud` (雲) という要素を追加しました。

## まとめ

振り返りのフレームワークを KPT 法から Sailboat Retrospective に変更したことで、殺伐とした反省会を一転させ、より楽しく、有意義な振り返りにできました。

海外では著名なフレームワークであることからテンプレートも多数存在しており、簡単に始められるのでぜひ試してみてください。

オススメの振り返り手法があれば、ぜひコメントで教えてください！

## 最後に

ハコベルでは運輸大手セイノーホールディングスとのジョイントベンチャー化に伴い、2022 年 8 月に第二創業期を迎えました。

そのため、エンジニア、デザイナーや PdM を始めとして、全方向で一緒に働くメンバーを募集しています。面白いフェーズなので、興味がある方はお気軽にご応募ください！

<!-- textlint-disable ja-technical-writing/ja-no-redundant-expression -->いきなりの応募はちょっと...という方は大石個人へ DM やメールして頂ければざっくばらんにお話することも可能です！<!-- textlint-enable ja-technical-writing/ja-no-redundant-expression -->

ぜひお気軽にご連絡ください！

https://hrmos.co/pages/hacobell
