# Heading

Start a line with a hash character `#` to set a heading. Organize your remarks with subheadings by starting a line with additional hash characters, for example `####`. Up to six levels of headings are supported.

Alternatively, on the line below the text, add any number of `==` characters for heading level 1 or `--` characters for heading level 2.

**Best practices:** Markdown doesn't agree on how to handle a missing space between the number signs `#` and the heading name. For compatibility, always put a space between the number signs and the heading name.

```markdown
# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4

Heading level 1
===============

Heading level 2
---------------
```

# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4

Heading level 1
===============

Heading level 2
---------------

# Bold
To bold text, add two asterisks or underscores before and after a word or phrase. To bold the middle of a word for emphasis, add two asterisks without spaces around the letters.

**Best practices:** Markdown doesn't handle underscores in the middle of a word. For compatibility, use asterisks to bold the middle of a word for emphasis.

```markdown
**This is bold text**

__This is bold text__

Love**is**bold
```

**This is bold text**
__This is bold text__
Love**is**bold

# Italic
To italicize text, add one asterisk or underscore before and after a word or phrase. To italicize the middle of a word for emphasis, add one asterisk without spaces around the letters.

**Best practices:** Markdown doesn't agree on how to handle underscores in the middle of a word. For compatibility, use asterisks to italicize the middle of a word for emphasis.

```markdown
*This is italic text*

_This is italic text_

A*cat*meow
```

*This is italic text*
_This is italic text_
A*cat*meow

# Strikethrough
Defines text that has been deleted from a document. To strikethrough text, add double tilde before and after.

```markdown
    ~~This is mistaken text~~
```

~~This is mistaken text~~

# Unordered list
To create an unordered list, add dashes `-`, asterisks `*`, or plus signs `+` in front of line items. Indent one or more items to create a nested list.

**Best practices:** Markdown doesn’t agree on how to handle different delimiters in the same list. For compatibility, don’t mix and match delimiters in the same list — pick one and stick with it.

```markdown
- First item
- Second item
- Third item
  - First sub-item
  - Second sub-item
- Fourth item
```

- First item
- Second item
- Third item
  - First sub-item
  - Second sub-item
- Fourth item

# Ordered list
To create an ordered list, add line items with numbers followed by periods. The numbers don’t have to be in numerical order, but the list should start with the number one.

```markdown
1. First item
2. Second item
3. Third item
   1. First sub-item
   2. Second sub-item
4. Fourth item
```

1. First item
2. Second item
3. Third item
   1. First sub-item
   2. Second sub-item
4. Fourth item

# Task list
To create a task list, add dashes `-`, asterisks `*`, or plus signs `+` and brackets with a space `[ ]` in front of task list items.  
To select a checkbox, add an x in between the brackets `[x]`.

```markdown
- [x] Caesar salad
- [ ] Cherry tomatoes
- [ ] Coconut cookies
```

- [x] Caesar salad
- [ ] Cherry tomatoes
- [ ] Coconut cookies

# Quote
To create a blockquote, add a `>` in front of a paragraph.

Blockquotes can contain multiple paragraphs. Add a `>` on the blank lines between the paragraphs.

Blockquotes can be nested. Add a `>>` in front of the paragraph you want to nest.

```markdown
> First quote paragraph.
>
>> Nested second quote paragraph.
```

> First quote paragraph.
>
>> Nested second quote paragraph.

# Code
To denote a word or phrase as code, enclose it in backticks `` ` ``.

If the word or phrase you want to denote as code includes one or more backticks, you can escape it by enclosing the word or phrase in double backticks ` `` `.

To create code blocks, indent every line of the block by at least four spaces or use three backticks ` ``` ` on the lines before and after the code block.

```markdown
At the command prompt, type `nano`.

    ```
    const sum = (a, b) => a + b;
    console.log(sum(3, 2));
    ```
```

At the command prompt, type `nano`.

```
const sum = (a, b) => a + b;
console.log(sum(3, 2));
```

# Link
To create a link, enclose the link text in brackets (e.g., `[NotesHub]`) and then follow it immediately with the URL in parentheses (e.g., `(https://noteshub.app)`).

You can optionally add a title for a link. This will appear as a tooltip when the user hovers over the link. To add a title, enclose it in parentheses after the URL.

To quickly turn a URL or email address into a link, enclose it in angle brackets.

Alternatively, you can use automatic URL linking, which means any URLs will be automatically converted into links.

**Best practices:** Markdown doesn’t agree on how to handle spaces in the middle of a URL. For compatibility, try to URL encode any spaces with `%20`.

```markdown
[NotesHub](https://noteshub.app)

[NotesHub](https://noteshub.app "NotesHub App")

<https://noteshub.app>

<contact@noteshub.app>

https://noteshub.app
```

[NotesHub](https://noteshub.app)
[NotesHub](https://noteshub.app "NotesHub App")
<https://noteshub.app>
<contact@noteshub.app>
https://noteshub.app

# Image
To add an image, add an exclamation mark `!`, followed by alt text in brackets, and the path or URL to the image asset in parentheses. You can optionally add a title after the URL in the parentheses.

To add a link to an image, enclose the Markdown for the image in brackets, and then add the link in parentheses.

```markdown
![Lime Kiln Point State Park](/images/photos/sanjuan_island.jpg "San Juan Island")

[![Beautiful view after sunset](/images/photos/hawaii_sunset.jpg)](https://www.instagram.com/alex.titarenko/)
```

![Lime Kiln Point State Park](https://www.noteshub.app/images/photos/sanjuan_island.jpg "San Juan Island")
    
[![Beautiful view after sunset](https://www.noteshub.app//images/photos/hawaii_sunset.jpg)](https://www.instagram.com/alex.titarenko/)

# Table
To add a table, use three or more hyphens `---` to create each column’s header, and use pipes `|` to separate each column. You can optionally add pipes on either end of the table.

You can align text in the columns to the left, right, or center by adding a colon `:` to the left, right, or on both side of the hyphens within the header row.

```markdown
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |


| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |
```

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |


| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |

# Horizontal rule
To create a horizontal rule, use three or more asterisks `***`, dashes `---`, or underscores `___` on a line by themselves.

**Best practices:** For compatibility, put blank lines before and after horizontal rules.

```markdown
    ***
    
    ---
    
    _________________
```

***

---

_________________

# Footnotes
Footnotes allow you to add notes and references without cluttering the body of the document. When you create a footnote, a superscript number with a link appears where you added the footnote reference. Readers can click the link to jump to the content of the footnote at the bottom of the page.

To create a footnote reference, add a caret and an identifier inside brackets `[^1]`. Identifiers can be numbers or words, but they can't contain spaces or tabs. Identifiers only correlate the footnote reference with the footnote itself — in the output, footnotes are numbered sequentially.

Add the footnote using another caret and number inside brackets with a colon and text (`[^1]`: My footnote.). You don't have to put footnotes at the end of the document. You can put them anywhere except inside other elements like lists, block quotes, and tables.

```markdown
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
There are two ways to add emoji: copy and paste the emoji into your Markdown-formatted text, or type emoji shortcodes.

In most cases, you can simply copy an emoji from a source like [Emojipedia](https://emojipedia.org/) and paste it into your document.

[Emoji shortcodes](https://gist.github.com/rxaviers/7360908) begin and end with a colon and include the name of an emoji.

```markdown
Gone camping! :tent: Be back soon.

That is so funny! :joy:
```

Gone camping! :tent: Be back soon.

That is so funny! :joy:

# HTML
If provided formatting constructions are not enough, you can use HTML tags.

```html
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