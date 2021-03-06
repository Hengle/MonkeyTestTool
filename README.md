# MonkeyTestTool

![2017-09-17_163505](https://user-images.githubusercontent.com/6134875/30518961-5f8624c8-9bc6-11e7-8164-4d54699a594a.png)

モンキーテスト用の簡易ツールです。  
指定された範囲内を高速かつランダムにクリックし続けます。  

# 使い方

|設定項目|内容|
|:--|:--|
|座標|クリックする範囲|
|押下間隔|次のクリックを行うまでの時間|
|押下時間|マウスボタンを押してから離すまでの時間|

- 「開始」ボタンを押すと入力された設定をもとにモンキーテストを開始します。  
- Shift + Esc キーでモンキーテストを終了します。  

# コマンドライン引数

```
--xMin <X 座標の最小値> --xMax <X 座標の最大値> --yMin <Y 座標の最小値> --yMax <Y 座標の最大値> --interval <押下間隔（ミリ秒）> --downTime <押下時間（ミリ秒）>
```

# 注意

- このツールはマウスカーソルの座標を強制的に移動させてクリックさせるツールなので、  
誤った設定でモンキーテストを開始すると意図しないボタンを押してしまう可能性があるのでご注意ください。  

# ブログ

http://baba-s.hatenablog.com/
