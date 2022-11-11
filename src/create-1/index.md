---
marp: true
theme: "mtg"
header: "TITLE DATE"
footer: "NAME"
headingDivider: 1
paginate: true
size: 16:9
math: katex
---

# 見出し

`# 見出し`で見出しになります。

## head2

### head3

#### head4

# 箇条書き

順序ありと順序なしの箇条書きを用います。

# 順序あり

html で言うところの`ol`タグです。

1. a
   1. b
2. c
   1. d
      1. e

# 順序なし

html で言うところの`ul`タグです。

- a
  - b
  - c
    - d

# 画像

```md
![h:300](./images/2022-11-10-20-10-23-30.png)
```

![h:300](./images/2022-11-10-20-10-23-30.png)

# リンク

Google は[こちら](https://www.google.com)

# 表

Marp で横並びのデザインを簡単にする時にも便利です。九九の途中まででも書いてみます。

|     | 1   | 2   | 3   |
| --- | --- | --- | --- |
| 1   | 1   | 2   | 3   |
| 2   | 2   | 4   | 6   |
| 3   | 3   | 6   | 9   |

# 引用

> 引用文

となります。スライド内で引用した箇所を表せます。

# コード

プログラムを添付する時に使います。

```c
int main(void){
    printf("%s\n","Hello World");
    return 0;
}
```

# 水平線

楽に区切られます。

```md
---
```
