# IH31/IW32 Markdown1

## <font color="red">*Markdown*</font>とは

文書を記述するための軽量マークアップ言語のひとつ。<br>
本来はプレーンテキスト形式で手軽に書いた文書からHTMLを生成するために開発されたもの。

## <font color="yellow">Markdown</font>の特徴
- 簡単で覚えやすい記述
  - ああああ
- 文章の構造を明示できる
  - いいいい
- Markdownそのままでも理解できる
  - うううう
- 対応アプリを使うことでより快適に読み書きできる
- 拡張子は「.md」

<br>

## VSCodeの<font color="orange">**Markdown**</font>プラグイン

*  **Markdown All in One**  
ショートカットキーで Markdown を入力
    *画像の挿入時にパスの入力を補完*  
ソースのインデント調整及び入力補完
mdファイルを開くと自動でプレビューを表示
![プレビューボタン](img/image01.png)

* **Markdown PDF**  
コマンドパレットで「export」などと入力し、[Markdown PDF: Export (html)
  Ctrl+Shift+P

---

## <font color="orange">＜＜見出し＞＞</font>

# 見出し1
## 見出し2
### 見出し3
#### 見出し3
##### 見出し3
###### 見出し3
<br>

## <font color="orange">＜＜文字の装飾＞＞</font>

**太字**  
*斜字*  
~~削除します~~

## ＜＜水平線＞＞  
***
***   
   

## <font color="orange">＜＜改行＞＞</font>  
文章1  
文章2  
※改行するときはスペース2つ入れる  
  
## <font color="red">＜＜文字色＞＞</font>  
<font color="orange">**Markdown</font>とは**  
  
<font color="orange">色を変えたいテキスト</font>  
<font color="">####</font><font color="orange"> **Markdown**</font>とは  

## ＜＜箇条書き＞＞  
- 箇条書き1  
  1の本文  
  1の次の行
- 箇条書き2  
  - 箇条書き3
  - 箇条書き4  
    - 箇条書き5  
      箇条書き5の本文  
      箇条書き5の本文2  
    - 箇条書き6
- 箇条書き7  
  - 箇条書き8
  
## ＜＜リスト＞＞
1. 数字付き1  
2. 追加  
3. 数字付き2
   1. 数字付きA  
       Aの本文
   2. 数字付きB
4. 数字付き3

## ＜＜引用＞＞  
> 引用
>> 二重引用
>>> 三重引用  
>>>テスト  
>>>本文  
>
> 二重引用あと一つ行開ける

## ＜＜コードブロック＞＞
ハイライト機能について様々な言語に対応
> 主要言語  
> C,C++,C#,CSS,Go,HTML,HTML+PHP,JSON,Java,Java Server Pages,JavaScript,Nginx,PHP,Python,Sass,Vue

【JavaScript】
```JavaScript
// 変数宣言
let height, weight, bmi, value;
// 入力
height = Number(prompt("身長をcmで入力してください。"));
weight = Number(prompt("体重をkgで入力してください。"));
// bmi
bmi = 10000 * weight / (height * height);
bmi = Math.rount(bmi * 100)/100;
if(bmi<18.5){
  value = "低体重";
}else if(bmi<25){
  value = "標準体重";
}
document.getElementByID('Judge').innerHTML=value;
```

【HTML】
```HTML
<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
</head>
<body>
<div id="height"></div>
<hr>
<div id="bmi"></div>
<div id="judge"></div>
</body>
</html>
```

【Markdown】
```Markdown
# 見出し1
## 見出し2
### 見出し3
**太字**
*斜字*
~~削除します~~
***
線を引く
---
本文をそのまま
改行も意識しない
```

## ＜＜リンク＞＞
[リンク⇒拡張機能：HTMLやPDFに変換]

## ＜＜画像表示＞＞
![プレビューボタン](img/image1.png)

## ＜＜テーブル＞＞
|TH|TH|項目3|
|---|---|---|
|TD1AAAAA|TD2AAAAA|値3AAAAA|
|TD3|TD4|値B|
|TD5|TD6|値C|