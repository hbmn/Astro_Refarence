##Astro_Refarence

静的テンプレート Astro の練習を兼ねて、公式リファレンスのブログサイトを作成。<br>

※パッケージマネージャーは yarn、node_module は除いてあるので<em>yarn</em>を実行、<br>
<em>yarn dev</em>でローカルサーバーの立ち上げ。

---

・ページコンポーネントはディレクトリ pages の中にファイル xxx.astro を作成。<br>
・コンポーネントは components フォルダにまとめる<br>
・ビルドしない画像などは public フォルダへ<br>

・script タグに書いたスクリプトは、ブラウザ上で実行される script タグとして出力される。<br>

vue のような書き方、これは NG<br>
<button onClick={handleClick}>Nothing will happen when you click me!</button>

・md ファイルも使用可能。blog ページの blog 記事 post は md ファイルで記述<br>
・about ページは条件分岐で表示をコントロール<br>
・blog ページで Card コンポーネントを props で内容をそれぞれ変更
