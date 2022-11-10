# 余白に関する記事
## `geometry`での設定
```TeX
\usepackage[margin=20truemm]{geometry}
```
- `margin`
  - 上下左右の余白を一括設定．`truemm`はより正確な`mm`．
- 個別に設定
  - `top`：上．
  - `bottom`：下．
  - `left`, `right`：左右．
## `jlreq`クラスでは，ドキュメントクラスでの設定も可能
```TeX
\documentclass[head_space=20mm,number_of_lines=40,gutter=10mm,line_length=45zw]{jlreq}
```
- `head_space`：上の余白．
- `foot_space`：下の余白．`head_space`かどちらか片方を指定．
- `number_of_lines`：行数．
- `gutter`：左余白．
- `line_length`：行長．
