## 自動販売機（オブジェクト、DOM、イベント処理）のミニレポート
### Q4-1. Itemクラスのメソッドについて説明せよ。
* showItemListがクラスメソッドである理由を考察せよ。
  * 商品情報が入っている配列を表示する機能であり、一つ一つの商品などを呼び出す必要がないから。
* buyItemがインスタンスメソッドである理由を考察せよ。
  * 購入処理は個々の商品の在庫を減らしたりする必要があるから。
### Q4-2. 商品の購入ボタンをクリックすると、どのような処理でセルの値が減少するか説明せよ。
* 購入された商品の在庫数のセルをどのようにして特定するのか説明せよ。
  * それぞれの商品につけたidによって特定する
* 特定したセルの値をどのように変更するのか説明せよ。
  * textContentを使うことによって、セルの中の文字を在庫数に更新している。
### Q4-3. 感想
* 今回の課題で苦労したこと
  * DOMの操作、クラスやインスタンスなど教科書を見ても全然わからなかったこと。
* 演習を通して理解できたこと
  * HTMLの表のtdをバッククォートで囲うと変数を呼び出せること
* この自動販売機プログラムの追加機能や課題など
