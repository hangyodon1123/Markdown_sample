# Markdown_sample

+ Only Japanese.

---
# 水平線
「-」「_」「*」を３つ記述。
```
---
```
---
# 見出し
先頭に#をレベルの数だけ記述。
```
# 見出し１
## 見出し２
### 見出し３
```
# 見出し１
## 見出し２
### 見出し３
---
# 引用
先頭に「>」を記述。
ネストは「>」を多重に記述。
```
> 引用
> 引用
>> 多重引用
```
> 引用
> 引用
>> 多重引用
---
# コード
バッククオート「`」３つ、またはダッシュ「~」３つで囲む。
~~~
```
input 'AAA'
```
~~~
```
input 'AAA'
```
---
# インラインコード
バッククオートで単語を囲む。
これが`インラインコード`のサンプルなのだ。

---
# 箇条書きリスト
「-」「+」「*」を先頭に記述。
ネストはタブを記述。
~~~
- List1
    - List1-1
        - List1-1-1
        - List1-1-2
    - List1-2
- List2
- List3
~~~
- List1
    - List1-1
        - List1-1-1
        - List1-1-2
    - List1-2
- List2
- List3
---
# 番号付きリスト
`番号.`を先頭に記述。
ネストはタブを記述。
番号は自動で採番される。
~~~
1. NList1
    1. NList1-1
    2. NList1-2
2. NList2
3. NList3
~~~
1. NList1
    1. NList1-1
    2. NList1-2
2. NList2
3. NList3
---
# Table
-と|を使い作成。
~~~
| 左 | 中央 | 右 |
|:---|:---:|---:|
|A |B |C |
|D |E |F |
~~~
| 左 | 中央 | 右 |
|:---|:---:|---:|
|A |B |C |
|D |E |F |
---
# LaTeX（数式表現)
まだ、勉強中なのだ。
~~~
Block-level formula:
```math
x = \dfrac{-b \pm \sqrt{b^2-4ac}}{2a}
```
In-line formula: ``x = \dfrac{-b \pm \sqrt{b^2-4ac}}{2a}``

Block-level formula:
```math
\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N
```
In-line formula: ``\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N``
~~~
Block-level formula:
```math
x = \dfrac{-b \pm \sqrt{b^2-4ac}}{2a}
```
In-line formula: ``x = \dfrac{-b \pm \sqrt{b^2-4ac}}{2a}``

Block-level formula:
```math
\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N
```
In-line formula: ``\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N``

---
