# npdata
Number Place Data 9x9 and 6x6

プログラムで自動生成して、解法によって分類したナンプレの問題データ。

6x6 のデータは同値なものを一つにまとめるという気持ちがあった。
9x9 のデータは問題図形の対称性を損なうとかいう理由をつけて、同値のものをまとめていない。

データは36文字とか81文字の文字列なので、6文字とか9文字で区切って
次の行に行くようにして使ってくれ。
6x6 のブロックは 3カラム2行の横長のブロックだと思ってくれ。

* hidden	hidden single
* locked  locked candidate
* tuple	naked pair, triple; hidden pair, triple
* xwing	X-wing
