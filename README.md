# note

振り返りーーーー
文字に起こさなくていい説出てきた
<br>
理由１ー毎回覚えておけるわけないから、細かいところは省く


順序ー
①index.htmlで肩を作る。今回はnoteを追加したり消したりするので、まずはnoteがある状態のindex.htmlmを作ってtoggleしたいところをscript.jsに移行すればいい。

②const でindex.htmlのdomを取得する＝＞jsで扱えるようなる。

③btnとか操作するdomにaddEventListerをつけて。

④その中に実行したい処理=> something();みたいな感じでかく

⑤処理の中身を別の場所に書く

それで今回はlocalstorageに値を保存したので、jsの最初の方にlocalに保存されている値（JSon形式）を読み込む必要があった。

後今回使ったやつ。
markupを実装するAPI

https://cdnjs.com/libraries/marked
