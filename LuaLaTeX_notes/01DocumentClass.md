# documentclass
```TeX
\documentclass[option]{class}
```
## `class`部
- `{jlreq}`
  - 横書き`article`相当の文書クラスとなる．
  - エンジンは自動判別．
  - 詳しくは[こちら](https://www.tug.org/texlive//Contents/live/texmf-dist/doc/latex/jlreq/jlreq-ja.html)
---
- `{ltjsreport}`
  - **報告書クラス**
  - `\usepackage{luatexja}`読み込みは不要
  - 詳しくは[こちら](https://texwiki.texjp.org/?クラスファイル一覧)．
- `{jsarticle}`
  - **報告書クラス**
  - `\usepackage{luatexja}`読み込みが必要．
  - 詳しくは[こちら](https://ja.osdn.net/projects/luatex-ja/wiki/LuaTeX-jaの使い方)
---
- `{ltjsarticle}`
  - **論文クラス**
  - `\usepackage{luatexja}`読み込みは不要．
  - 詳しくは[こちら](https://texwiki.texjp.org/?クラスファイル一覧)．

- `{jreport}`
  - **論文クラス**
  - 詳しくは[こちら](https://ja.osdn.net/projects/luatex-ja/wiki/LuaTeX-jaの使い方)
  - `\usepackage{luatexja}`読み込みが必要．
## `option`部
- 文字サイズ
  - 10pt, 11pt, 12pt ... など．（10ptがデフォルト）
- 用紙サイズ
  - `a4paper`, `b4paper`など．

- 段組
  - 1段組：`onecolumn`（デフォルト）
  - 2段組：`twocolumn`
- 用紙向き
  - 縦：無記述（デフォルト）
  - 横：`landscape`



