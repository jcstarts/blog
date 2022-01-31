+++
title = "Markdown Reference"
date = "2022-01-30T23:02:05-06:00"
author = "Jordan Cochran"
authorTwitter = "jcstarts" #do not include @
cover = "markdown.png"
tags = ["markdown"]
keywords = ["markdown", ""]
description = "Quickly find out how to write something in markdown..."
showFullContent = false
readingTime = false
+++

**Table Of Contents**

---
- [Headings](#headings)
- [Paragraphs](#paragraphs)
- [Emphasis](#emphasis)
- [Horizontal Rules](#horizontal-rules)
- [Line Breaks](#line-breaks)
- [Lists](#lists)
- [Links](#links)
- [Images](#images)
- [Block Quotes](#block-quotes)
- [Code](#code)
- [Raw HTML](#raw-html)
- [More References](#more-references)
---

## Headings

To make a heading, add a '#' at the start of the line with a
space after.

```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

## Paragraphs

Paragraphs are just plain text inside your markdown.

```markdown
This is a paragraph
```

## Emphasis

You can Bolden or Italicize your markdown by wrapping words
in '**' for bold, or a single '_' for italics.

```text
**BOLD**

_Italic_
```

## Horizontal Rules

You can get a horizontal line across your page by adding '---'
on a line by itself.

If you add this line right under a word, that word becomes a
heading.

```markdown
---
```

```markdown
This is a heading
---
```

## Line Breaks

You can get a line break on your page by adding '<br>' on a line by itself.
It's also possible to get a line break by adding a blank line inbetween paragraphs.

```markdown
<br>
```

## Lists

Lists can be made by adding a number at the start of a line followed by a space.
You can also achieve an unordered list by using a '-', '+', or '*' instead of a number,
watch out though, make sure to use just one of the three, don't mix and match.

**Ordered Lists**

```markdown
1. First Item
2. Second Item
3. Third Item
```

**Unordered Lists**

```markdown
- First Item
- Second Item
- Third Item
```

## Links

To create a hyperlink in your page, wrap you link text in open and closing
'[' ']' square brakets, the link itself will be wrapped in parenthesis
'(' ')'.


```text
[link text](https://examplesite.com)

[JCstarts](https://jcstarts.github.io)
```

## Images

```text
![alt text](./path/to/image.png)

![tuxy](tuxy.png)
```

![tuxy](images/tuxy.png)

## Block Quotes

To make a quote or block quote, start the line with a '>' followed
by a space, for a multi-line quote just start everyline with a '>'.

Also there should be a blank line above and below your quotes.

```markdown
> This is a quote.

> This is a
> Multi-line
> quote.
```

## Code

To show off code in your markdown page, you have to make a code
fence, this is done by wrapping it in three backticks '\`\`\`'
followed by the programming language.

Like so...

````markdown
```go
package main

import "fmt"

func main() {
  fmt.Println("Hello World!")
}
```
````

## Raw HTML

You can also use raw html in your markdown, in fact,
everything we've covered so far can be done with the html
equivalent.

Some markdown parsers don't allow html in your document, due
to security reasons. So if your html isn't rendering correctly,
check the documentation.

```html
<h1>Hello World</h1>

<p>This is a paragraphs in HTML</p>
```

## More References

Here are a few more resources to learn and explore Markdown.

- [Awesome Markdown List](https://github.com/mundimark/awesome-markdown)
- [Markdown Guide](https://www.markdownguide.org/basic-syntax/)
- [Github Flavored Markdown](https://github.github.com/gfm/)
