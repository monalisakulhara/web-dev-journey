# Learning Markdown

[Checkout this blog](https://blog.webdevsimplified.com/2023-06/markdown-crash-course/#interactive-markdown-editor)

### Paragraph

Normal Text

Here (for new paragraph we need to double enter)

There are flavors of markdown like github type markdown essentially they add some extra features in vanilla markdown.

### Headings

You know this!

### Code

This is how you enter code in md file using backtick .
This is `Let C = 10` in monospace font.
Use language syntax highlighting like give example. this is part of extended version.

```cpp
#include <iostream>
using namespace std;

int main(){
    cout << "Hello, World!" << endl;
    return 0;
}
```

### Bold & Italics

Text is **bold** or b**old** or **bold** . No b__old__

Text is _italics_ or _italics_ or i*talic*s

Text is _**bold**_ and _**italics**_

Text is ~~crossed off~~

Test is ==highlighted== -> this is in extended version of markdown not in github's flavor of markdown

<mark>hightlight</mark>

### Superscript and Subscript

again not in github flavor markdown
This is a ^superscript^ like X^2^

This is a ~subscript~ like H~2~O

in html: X<sup>2</sup> and H<sub>2</sub>O

### emoji

again dickhub does not support this
If you write :smile it will render right emoji.

So just copy paste for github😊

### Link

[This is a link](https://google.com)

[This is also a link](/page) for specific website page

or

<https://google.com>

or

[https://youtube.com](https://youtube.com)

### Images

same as link but with !.

![Google Logo](/articleAssets/2023-06/markdown-crash-course/Google_Normal.png)

### Block Quotes

> This
>
> is
>
> Block
>
> > Code
> >
> > > Nested

### Horizontal line

atleast three

---

or

---

or

---

### List

1. Item 1
2. Item 2
3. Item 3

- Item 1
- Item 2
- Item 3

* Item 1
* Item 2
* Item 3

- Item 1
- Item 2
- Item 3
  - Item 4
  - Item 5
    - Bread
    1. whole flour
    2. water

### Table

| Col 1 | Col 2   |
| ----- | ------- |
| This  | is      |
| an    | exam    |
| table | with    |
| two   | columns |

by Default they are left aligned . this is also left aligned.

| Col 1 | Col 2   |
| ----- | :------ |
| This  | is      |
| an    | exam    |
| table | with    |
| two   | columns |

to make right aligned

| Col 1 |   Col 2 |
| ----- | ------: |
| This  |      is |
| an    |    exam |
| table |    with |
| two   | columns |

to make center aligned

| Col 1 |  Col 2  |
| ----- | :-----: |
| This  |   is    |
| an    |  exam   |
| table |  with   |
| two   | columns |

### Checklist

- [ ] Unchecked
- [x] Checked
