# #見出し 1

## ##見出し 2

### ###見出し 3

#### ####見出し 4

##### #####見出し 5

###### ######見出し 6

通常の文章

通常の文章中で強制改行したいときは文章末尾にスペースを 2 つ入れる (br)  
(Tab キーなどを使うと楽に改行できる)  
※ 基本的に強制改行は使わず,文章の意味を区切るべきではないか考慮すること

- リスト
  - リストのネスト (スペース 2 つか 4 つ)
  - リストのネスト (リスト内のリストのことをネストと言う)(らしい)
    - リストのネストのネスト
  - リストのネスト
- リスト
- リストはハイフンではなくアスタリスクでも書ける(非推奨)

リストと順序付きリストを連続して表記する場合,2 行以上の空行を間に入力する。

1. 順序付きリスト
2. 順序付きリスト
   1. 順序付きリストのネスト(スペース 4 つ)  
      2. 順序付きリストのネストのネスト
3. 順序付きリスト

---

水平線はハイフン(-)三つ

```
コードブロックはバックフォート(`)３つでコードを挟む
```

````cpp
#include <stdio.h>
int main{

printf ("コードブロック開始のバッククォート3つの直後に");
printf ("言語名を書くとシンタックスハイライトできる");
printf ("例 : ```cpp ```")

return 0;
}
````

> 引用ブロック
>
> - 引用ブロック内にリストなどもかける

---

文章の*強調*  
文章を**さらに強調**

```
文章の*強調*
文章を**さらに強調**
```

```
[web サイトなどリンクする場合](http://github.com)
```

[web サイトなどリンクする場合](http://github.com)

```
![画像投稿. これは代替テキスト](https://twitter.com/Mibuchi_Yuta/header_photo)
```

![画像投稿. これは代替テキスト](https://twitter.com/Mibuchi_Yuta/header_photo)

グラフ

```
| 左寄せ | 右寄せ | 中央揃え |
| :----- | -----: | :------: |
| 猫     |     猫 |    猫    |
```

| 左寄せ | 右寄せ | 中央揃え |
| :----- | -----: | :------: |
| 猫     |     猫 |    猫    |

twitter 埋め込み
