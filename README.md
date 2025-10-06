cssに触れてみよう
9.[✕]タグに名前をつける
  fontプロパティには、必須のfont-size,font-family,他にfont-weight等がある
  ※ 文字の色はcolorプロパティ

レイアウトを作ろう！
12.全体のレイアウト
  昔ながらの書き方
  <div class="header">ヘッダー部分</div>
  <div class="main">メイン部分</div>
  <div class="footer">フッター部分</div>
  
  HTML5推奨の書き方
  <header>ヘッダー部分</header>
  <main>メイン部分</main>
  <footer>フッター部分</footer>
  → 見た目は同じでも、後者のほうが「構造的に意味が伝わる」のでモダンなやり方です。

  17.[✕]フッターのレイアウト

  19.[✕]コンテンツの構造
  → 適用したい範囲のタグ全体を<div></div>で囲う



  HTML & CSS 学習レッスン 中級編
  レッスン一覧部分を作ろう
  13.レイアウトを整えよう
   display: inline-block　→ ブロック要素にも適用できる  

  15.立体的なボタンを作ろう
   border-bottom(wrapperなどの外側の要素の枠線)と、box-shadow(container内のボックスに影をつける)の混同に注意

   親要素に小要素を重ねる方法 → 親はposition:relative,子にposition:absolute,



   HTML & CSS 学習レッスン 上級編
   6.タブレット向けのレイアウトを作ってみよう
    スマホ(670px以下)、タブレット(1000px以下)ごとの設定を制御しているのは、画面幅
    @media (max-width:1000px) {
    }
    
   
   

   
