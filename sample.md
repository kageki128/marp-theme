---
marp: true
paginate: true
theme: lab
math: katex
---

<!-- _class: title -->

# タイトル

#### 〜サブタイトル〜

YYYY/MM/DD
林研究室 学士4年
景浦 誠


---

## 目次

1. セクション1
2. セクション2
3. セクション3

---

## 見出し

### 小見出し

テキスト

- 箇条書き1
    - 箇条書きネスト
- 箇条書き2$^1$

> 1: 脚注

---

## コードブロック

```java
public class Main {
  public static void main(String[] args) {
    System.out.println("Hello, Marp!");
  }
}
```

---

## 数式

$$ I_{xx}=\int\int_Ry^2f(x,y)\cdot{}dydx $$

$$
f(x) = \int_{-\infty}^\infty
    \hat f(\xi)\,e^{2 \pi i \xi x}
    \,d\xi
$$

こんな感じで数式を書くことができる。もちろんインラインの $\LaTeX$ も使える。  
ついでに絵文字も使える:smile:

---

## 図

1. まず[このいらすとやのリンク](https://www.irasutoya.com/2018/10/blog-post_723.html)から画像（`kenkyu_woman_seikou.png`）を右クリックでダウンロードしてください。
2. この Markdown のあるディレクトリの中に `images` という名前のディレクトリを作り、先ほどダウンロードした画像を配置してください。これで準備が整いました。

![w:300 center](./images/kenkyu_woman_seikou.png)
