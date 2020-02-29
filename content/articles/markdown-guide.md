+++
author = "Fr. Jim"
categories = ["articles"]
tags = ["2020"]
date = "2020-02-26"
description = "A Cheat Sheet for Markdown Documents"
featured = "markdown.jpg"
featuredpath = "/img/tech-articles"
featuredalt = "Markdown Text"
linktitle = ""
title = "Markdown Guide"
type = "post"

+++

This is an abridged version of Adam Pritchard's Wiki, which may be seen [here](https://github.com/adam-p/markdown-here). For more complete info, see [John Gruber's original spec](http://daringfireball.net/projects/markdown/) and the [Github-flavored Markdown info page](http://github.github.com/github-flavored-markdown/).

---

## Headers

```no-highlight
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

# H1
## H2
### H3
#### H4
##### H5
###### H6

---

## Emphasis

```no-highlight
For italics, use *asterisks* or _underscores_

For bold, use **asterisks** or __underscores__.

For bold+italics use **asterisks and _underscores_**.

For strikethrough use two tildes ~~Scratch this.~~
```
For italics, use *asterisks* or _underscores_

For bold, use **asterisks** or __underscores__.

For bold+italics use **asterisks and _underscores_**.

For strikethrough use two tildes ~~Scratch this.~~

---

## Lists

(In this example, leading and trailing spaces are shown with with dots: ⋅)

```no-highlight
1. First ordered list item
2. Another item  
⋅⋅* Unordered sub-list
5. Can begin with any number
⋅⋅1. Ordered sub-list

⋅⋅⋅For indented paragraphs within list items, add 3 spaces before each line.
⋅⋅⋅You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).
⋅⋅⋅To have a line break without a paragraph, you will need to use two trailing spaces.⋅⋅
⋅⋅⋅Note that this line is separate, but within the same paragraph.⋅⋅

* Unordered list can use asterisks
- Or minuses
+ Or pluses
```

1. First ordered list item
2. Another item
  * Unordered sub-list. 
1. Actual numbers don't matter, just that it's a number
  1. Ordered sub-list
4. And another item.

   You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

   To have a line break without a paragraph, you will need to use two trailing spaces.  
   Note that this line is separate, but within the same paragraph.  
   (This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)

* Unordered list can use asterisks
- Or minuses
+ Or pluses

---

## Links

There are two ways to create links.

```no-highlight
[Inline-style link](https://start.duckduckgo.com)

[Inline-style link with title](https://start.duckduckgo.com "DuckDuckGo Homepage")

[Reference-style link][Arbitrary case-insensitive reference text]

[Relative reference to a repository file](../blob/master/LICENSE)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com>

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: https://fatherjim.tech
[link text itself]: http://www.reddit.com
```

[Inline-style link](https://start.duckduckgo.com)

[Inline-style link with title](https://start.duckduckgo.com "DuckDuckGo Homepage")

[Reference-style link][non-case-insensitive reference text]

[Relative reference to a repository file](../blob/master/LICENSE)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com>

Some text to show that the reference links can follow later.

[non- case-insensitive reference text]: https://www.mozilla.org
[1]: https://fatherjim.tech
[link text itself]: http://www.reddit.com

---

## Images

```no-highlight
Here's my picture (hover to see the title text):

Inline-Style: 
![alt text](https://fatherjim.tech/img/main/logo2.jpg "Fr. Jim Inline-Style")

Reference-Style: 
![alt text][logo]

[logo]: https://fatherjim.tech/img/main/logo2.jpg "Fr. Jim Reference-Style"
```

Here's my picture (hover to see the title text):

Inline-Style: 
![alt text](/img/main/logo2.jpg "Fr. Jim Inline-Style")

Reference-Style: 
![alt text][logo]

[logo]: /img/main/logo2.jpg "Fr. Jim Reference-Style"

---

## Code and Syntax Highlighting

```no-highlight
Inline `code` has `back-ticks around` it.
```

Inline `code` has `back-ticks around` it.

Blocks of code could be fenced by lines with three back-ticks <code>```</code> or all lines indented by 4 spaces.

    ```javascript
    var s = "JavaScript syntax highlighting";
    alert(s);
    ```
 
    ```python
    s = "Python syntax highlighting"
    print s
    ```
 
    ```
    No language indicated, so no syntax highlighting. 
    But let's throw in a &lt;b&gt;tag&lt;/b&gt;.
    ```



```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```

```python
s = "Python syntax highlighting"
print s
```

```
No language indicated, so no syntax highlighting in Markdown Here (varies on Github). 
But let's throw in a <b>tag</b>.
```

---

## Tables

```no-highlight
Colons can be used to align columns.

| Left-Aligned |  Centered  | Right Aligned |
| :----------- | :--------: | -------------:|
| A            | B          | C             |
| X            | Y          | Z             |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the 
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
```

Colons can be used to align columns.

| Left-Aligned |  Centered  | Right Aligned |
| :----------- | :--------: | -------------:|
| A            | B          | C             |
| X            | Y          | Z             |

There must be at least 3 dashes separating each header cell. The outer pipes (|) are optional; the raw Markdown does not have to line up perfectly. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

---

## Blockquotes

```no-highlight
> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote. 
```

> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote. 

---

## Inline HTML

Not working for this theme.

---

## Horizontal Rule

```
Three or more...

---

Hyphens

***

Asterisks

___

Underscores
```

Three or more...

---

Hyphens

***

Asterisks

___

Underscores

---

## Line Breaks

To insert a line break, either add a blank line between two lines or add 2 spaces at the end of the line.

```
Here's a line for us to start with.

This line is separated from the one above by two new lines, so it will be a *separate paragraph*.

This line also a separate paragraph, but...
This line is only separated by a single newline, so it's a separate line in the *same paragraph*.
```

Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a *separate paragraph*.

This line also begins a separate paragraph, but...  
This line is only separated by a single new line, so it's a separate line in the *same paragraph*.

---

## YouTube Videos

They can't be added directly but you can add an image with a link to the video like this:

```no-highlight
<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
```

Or, in pure Markdown, but losing the image sizing and border:

```no-highlight
[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)
```

---
