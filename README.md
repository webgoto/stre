#STRE（スとレ）
Style & Responsive
UIデザイン用CSS(st.css)とレスポンシブ用CS(re.css)のセットです。  
プロジェクトに合わせて、どちらか一方だけでも利用可能です。

##st.cssについて
UIデザイン用のCSSです。
ボタンやフォーム用のスタイルが定義されています。
st.sassファイルのミックスインを使用することで、簡単にカラーバリエーションを作ることが出来ます。
コンパイルしたst.cssを読み込みます。

##re.cssについて
レスポンシブ用のCSSです。
グリッドやマージン用のスタイルが定義されています。
re.cssを読み込みます。

##おすすめの読み込み順
```html
<html>
<head>
<link rel="stylesheet" href="normarize.css">
<link rel="stylesheet" href="st.css">
<link rel="stylesheet" href="original.css">
<link rel="stylesheet" href="re.css">
</head>
<body>
</body>
</html>
```