# Heading

# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4

Heading level 1
===============

Heading level 2
---------------

# Bold
**This is bold text**
__This is bold text__
Love**is**bold

# Italic
*This is italic text*
_This is italic text_
A*cat*meow

# Strikethrough
~~This is mistaken text~~

# Unordered list
- First item
- Second item
- Third item
  - First sub-item
  - Second sub-item
- Fourth item

# Ordered list
1. First item
2. Second item
3. Third item
   1. First sub-item
   2. Second sub-item
4. Fourth item

# Task list
- [x] Caesar salad
- [ ] Cherry tomatoes
- [ ] Coconut cookies

# Quote
> First quote paragraph.
>
>> Nested second quote paragraph.

# Code
At the command prompt, type `nano`.

```
const sum = (a, b) => a + b;
console.log(sum(3, 2));
```

# Link
[NotesHub](https://noteshub.app)
[NotesHub](https://noteshub.app "NotesHub App")
<https://noteshub.app>
<contact@noteshub.app>
https://noteshub.app

# Image
![Lime Kiln Point State Park](https://www.noteshub.app/images/photos/sanjuan_island.jpg "San Juan Island")
    
[![Beautiful view after sunset](https://www.noteshub.app//images/photos/hawaii_sunset.jpg)](https://www.instagram.com/alex.titarenko/)

# Table
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |


| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |

# Horizontal rule
***

---

_________________

# Footnotes
Footnotes allow you to add notes and references without cluttering the body of the document. When you create a footnote, a superscript number with a link appears where you added the footnote reference. Readers can click the link to jump to the content of the footnote at the bottom of the page.

To create a footnote reference, add a caret and an identifier inside brackets `[^1]`. Identifiers can be numbers or words, but they can't contain spaces or tabs. Identifiers only correlate the footnote reference with the footnote itself — in the output, footnotes are numbered sequentially.

Add the footnote using another caret and number inside brackets with a colon and text (`[^1]`: My footnote.). You don't have to put footnotes at the end of the document. You can put them anywhere except inside other elements like lists, block quotes, and tables.

```
Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.
```

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.

# Emoji
Gone camping! :tent: Be back soon.

That is so funny! :joy:

# HTML
If provided formatting constructions are not enough, you can use HTML tags.

```
This is <mark>highlighted text</mark> using HTML tag
```

This is <mark>highlighted text</mark> using HTML tag

# Merge conflict
When during the notebook synchronization notes can't be merged without conflicts, two alternative variants will be provided so you can pick the right one.

```
:::conflict{variant=a}
some text
:::

:::conflict{variant=d}
altered text
:::
```

:::conflict{variant=a}
some text
:::

:::conflict{variant=d}
altered text
:::