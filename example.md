% タイトル
% 著者
% 日付

# 題名
"#"で題名になる

# 改行の仕方
末尾に改行を

2つ入れると改行される  

明示的に改行するなら<br>
\<br>を末尾に記入する。

# スライド区切り
"#"でスライドを区切れる

題の階層を指定すれば"##"でもスライドを区切れる

---

ハイフンを3つでスライドを区切れる

ハイフン行の下に空行を一行入れる

---

# リスト
- "-"でリストになる
- あああ
- ううう

# 番号付きリスト
1. "1."で番号付きリストになる
1. あああ
1. ううう

# 画像
相対パスで指定する

![image](./image/nico.png)

# コード
コードを明示する場合"\```[hoge]", "\```"で囲む

[hoge]に任意の言語を指定すると

シタックスハイライト可能

```cs
public class Hoge
{
	public static main(string[] args)
	{
		Console.WriteLine("Hellow World");
	}
}
```

---

### シンプルテーブル1
Table:テーブル名

 right  left    center   default
------  -----  --------  -------
1       1       1         1
2       2       2         2
3       3       3         3

---

### シンプルテーブル2

-------     ------ ----------   -------
     12     12        12             12
    123     123       123           123
      1     1          1              1
-------     ------ ----------   -------

---

### パイプテーブル

|右寄せ | 左寄せ|デフォルト|中央寄せ|
|------:|:-----|---------|:------:|
|   12  |  12  |    12   |    12  |
|  123  |  123 |   123   |   123  |
|    1  |    1 |     1   |     1  |

: パイプテーブルのデモ


---


# 変換
このmdファイルを変換するにはbash上で下記コードを実行する

```bash
pandoc -t revealjs -s -o example.html example.md
```


# 参照
- [Pandocユーザーズガイド](http://sky-y.github.io/site-pandoc-jp/users-guide/)
- [Pandocでrevel.jsを使う](https://qiita.com/sukakako/items/a78478f94e934c47b993)
- [github reveal.js](https://github.com/jgm/pandoc/wiki/Using-pandoc-to-produce-reveal.js-slides)
