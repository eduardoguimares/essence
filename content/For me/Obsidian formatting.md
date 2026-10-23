From [help.obsidian.md](https://help.obsidian.md/How+to/Format+your+notes)
[Markdown guide](https://www.markdownguide.org/) if needed
- - -
# Internal linking
```
Link to a page: [[Internal links]].
```
# Headings
```
# This is a heading 1
## This is a heading 2
### This is a heading 3
#### This is a heading 4
##### This is a heading 5
###### This is a heading 6
```
or
```
Heading 1
===
Heading 2
---
```
# Links
```
This is a link to [[this note]]
```
or
```
This is a link to [[this note |refered note]]
```
or, if I want to link to a heading
```
This is a link to [[this note's heading#heading]]
```
# Emphasis
### Italic
```
*This text* and _this text_ will be italic
```

### Bold
```
**This text** and __this text__ will be bold
```

### Strike-through
```
~~This text~~ will appear crossed out
```

### Highlighting
```
==This text== will be highlighted
```

# Callouts
More information [here](https://help.obsidian.md/Editing+and+formatting/Callouts)
```
> [!info]
> [!todo]
> [!note]
> [!abstract] or [!summary] or [!tldr]
> [!tip] or [!hint] or [!important]
> [!sucess] or [!check] or [!done]
> [!question] or [!help] or [!faq]
> [!warning] or [!caution] or [!attention]
> [!failure] or [!fail] or [!missing]
> [!danger] or [!error]
> [!bug]
> [!example]
> [!quote] or [!cite]
```
#### *Examples*
> [!info]

> [!todo]

> [!note]

> [!abstract]

> [!tip]

> [!success]

> [!question]

> [!warning]

> [!failure]

> [!danger]

> [!bug]

> [!example]

> [!quote]

### Simple callout
```
> [!info]
```

### Callout with custom title
```
> [!info] Title
```

### Callout with custom title and content
```
> [!info] Title
> Any type of content
```

### Foldable callout
```
> [!info]Title
> Content is needed for this type of callout
```

### Nested callout
```
> [!info] This the first callout
> > [!info]This callout is nested and foldable
> > > [!info] This callout is nested in the foldable callout
```

### Custom callout
[CSS snippets](https://help.obsidian.md/Extending+Obsidian/CSS+snippets) required

> [!note] To learn

# Lists

### Unnumbered lists
```
Item 1
Item 2
  Item 2a
  Item 2b
```

### Numbered Lists
```
1. Item 1
2. Item 2
3. Item 3
   1. Item 3a
   2. Item 3b
```

### Check lists
```
[x] #tags, [links](), **formatting** supported
[x] list syntax required (any unordered or ordered list supported)
[x] this is a complete item
[?] this is also a complete item (works with every character)
[ ] this is an incomplete item
[ ] tasks can be clicked in Preview to be checked off
```

# Toggle

<details> <summary>Title of toggle (can only open toggle in reading view)</summary> <p>Content of toggle</p> </details>

# Blockquotes
```
> Human beings face ever more complex and urgent problems, and their effectiveness in dealing with these problems is a matter that is critical to the stability and continued progress of society.

\Doug Engelbart, 1961
```

# Horizontal Bar
```
Use *** or --(if right after normal text, creates a heading) or ___ or in a new line to produce an horizontal bar
```

# Code blocks
```
Text inside `backticks` on a line will be formatted like code.
```

Obsidian uses Prism for syntax highlighting. For more information, refer to [Supported languages](https://prismjs.com/#supported-languages)
```js
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

# Tables
`|` to separate columns (first and last `|` are opional)
`-----` to separate the header from the content (at least two hifens)

```
|First Header | Second Header|
|-----------| ------------|
|Content from cell 1 | Content from cell 2|
|Content in the first column | Content in the second column|
```

Conent will be automatically aligned to the left
```
|But you can align to the right| Or to the center|
|-------:|:-----:|
|If you add `:` at the end of the separator|If you add `:` to the beginning and end of the separator|
```

If you use aliases or if you resize and image, the pipe must be escaped with a `\` to prevent it being read as a table element.
```md
First Header | Second Header
-----------| ------------
[[Name of the note\|Visible text]]	|  ![[image.png\|200]]
```

# Embeds
More information [here](https://help.obsidian.md/Linking+notes+and+files/Embedding+files)
### Embed a note
```
![[Obsidian]]
```

### Embed a note but shows a different name
```
![[Obsidian|this page]]
```

### Embed a heading or a block
```
![[Obsidian#What is Obsidian]]
```

### Embed an image (from the vault)
```
![Engelbart.jpg]
```

### Embed an image from the web
```
![Engelbart](https://history-computer.com/ModernComputer/Basis/images/Engelbart.jpg)
```

### Embed an audio file from the vault
```
![[Excerpt from Mother of All Demos (1968).ogg]]
```

### Embed a pdf from the vault
```
![[Document.pdf]]
```

##### Embed a page from a pdf
```
![[Document.pdf#page=3]]
```

# Edit images

### Resize web image to 100 pixels wide
```
![Engelbart|100](https://history-computer.com/ModernComputer/Basis/images/Engelbart.jpg)
```

### Resize local image to 100x200
```
![[og-image.png|100x200]]
```

# Footnotes
```
Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: meaningful!

[^bignote]: Here's one with multiple paragraphs.
	"bignote" will be switched by a number in the reading mode
	You need to indent paragraphs to include them in the footnote.
	You need to switch to reading mode in order too see the "go-back" button
	Add as many paragraphs as you like.
```

```
You can also use inline footnotes. ^[notice that the caret goes outside of the brackets on this one.]
The text of the footnote will go to the end of the page and it will automatically refer to a number when the reading mode is switched. ^[cool isn't it!]
```

# Comments
```md
Here is some inline comments: %%This text doesn't appear in reading mode%%

Here is a block comment:
%%
This text
doesn't appear
in reading mode
%%
```

# Escaping
If the URL contains spaces, you can escape them by replacing them with `%20`.
```md
[Export options](Pasted%20image)
```