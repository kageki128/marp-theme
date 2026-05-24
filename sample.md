---
marp: true
paginate: true
theme: lab
math: katex
html: true
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

<!-- _class: section-head -->

# セクション見出し

---

## 見出し

### 小見出し

テキスト$^1$

- 箇条書き1
    - 箇条書き1-1
- 箇条書き2

> 1: 脚注

---

## 画像

![w:900 center](https://picsum.photos/seed/picsum/1920/1080)

---

## 数式 / コードブロック

$\LaTeX$ と `code block` も使える。

$$
f(x) = \int_{-\infty}^\infty
    \hat f(\xi)\,e^{2 \pi i \xi x}
    \,d\xi
$$

```java
public class Main {
  public static void main(String[] args) {
    System.out.println("Hello, Marp!");
  }
}
```

絵文字も使える:smile:

---

<!-- _class: two-cols -->

## 2カラムレイアウト

<div class="cols">
  <div>

### 左カラム

左側のテキスト

- 箇条書き1
- 箇条書き2
- 箇条書き3

  </div>
  <div>

### 右カラム

右側のテキスト

- 箇条書き1
- 箇条書き2
- 箇条書き3

  </div>
</div>
