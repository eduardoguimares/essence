---
aliases:
  - How to approach obsidian
---
This vault should represent my learning process
I'm focusing on higher complexity concepts because simple concepts are easily available on the Internet
It should be accessible and understandable to anyone long-term

# Constant improvement of the ideas

A process I like to call -> Gardening
Many ideas still need curation because this space is the representation of my understanding of the world, so it will never be the final product

## Process
Should be frictionless
1. Find an interesting idea that I care about (should prioritize good quality sources)
2. Find a good page to keep it (or create a new page) - it requires me to have some level of understanding of the concept in order to position it with other knowledge
3. Capture the idea - either reference word by word (good for the first time) or with my own words
4. Add a footnote (alt+f) for proper credit - only if my writing relies a lot on the external content and if it's an unique idea
	- If it's easily accessible knowledge - I don't need to add a footnote
	- If it's a research paper, then {name of the paper} - {author(s)}
	- If it's a very insightful youtube video or article, then {name of the source with external link} - {author}
	- If it's an unique idea from an author who shares their idea through multiple sources, then the name of the author is enough
5. Add the reference (alt+r) - in case I saved it on Zotero

Later revisions
1. Disintegrate the idea - that forces me to understand more deeply the idea because I need to position the idea comparatively with the other concepts
2. Distill - Eliminate what doesn't matter
3. Organize the important pieces
4. Refine the writing

## When I have doubts

I can explore the doubts using %%%% comments

## When it is a personal opinion

It's ok, I can keep it that way. I could add a footnote to say it's my opinion

# Pages

Each page should be a concept
	If the page is too long, I should separate each section into other pages, ideally in sub concepts, or change it to a canvas
	For details on how I want to structure the notes, I can use the comment format

Not doing one page for each day because I prefer to directly add new content into a note and in the long-term I don't care about the dates
	I want this to become as timeless as possible

Not doing pages about people because I don't have much to add about the person. It's just best to keep an external link to a page of the person on the Internet

Not doing summaries of articles, books, videos, etc. because the ideas of the source need to be deeply connected with the other ideas

## Content format

- Text > Excalidraw > Image (avoid as much as possible)
- **Bold** could be used in key words or sentences
- *Italic* for word to word citations
- Footnotes should be used for citations and personal comments
- There should be a blank paragraph between each element for better reading in live mode
- There should be no indentations for simple paragraphs because the read mode doesn't show them (and there's no easy way to create this)

### Callouts

> [!a]- For examples
> Could be folding or not

> [!b] Or highlights

# Citations

Even though it is my dream to build a hyperconnected information system, for now I have to be pragmatic

## Books and other high value sources

These sources should be saved in Zotero, completely available offline and referenced with a shortcut.

As many details should be added. If box is not fulfilled, then it should not be included. Some examples:

[^1]: Author: José
Date: 2011
URL: example.com/webpage

Notes: not adding a link directly to the web archive because if the link is broken, then in the future the user or me can simply search it the web archive; not creating a proper page for each source because I won't make many notes and it just adds to the mess

Note: the integration only imports dates from the year 1971

## Low value sources

These should not be saved in Zotero because it is a waste of time and should be added manually. It could be a quote difficult to trace back to its origin. It could be a tweet. It could be an idea of an article or video of a common concept

The author and year is the most important. I won't be saving the URL because the source is low value. Some examples:

[^3]: José, 2014
[^4]: *The title of some thing*, Tom Cruise (2000)

# Metadata

In the future, I'll be able to hide specific properties like excalidraw-plugin and cssclasses
- Tags - tolearn, todevelop, toorganize (hidden)
- Aliases
- Topic

# Folders

As simple as possible
- Main folder - pages and canvas of concepts + home page
- Media - images, gifs, excalidraws
- For me - pages only for me

# Plugins

| Using | Plugin                                                        | Situation                                                                                                                                                                                                                                                                                                              |
| ----- | ------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ✔️    | Excalidraw                                                    | Essential for a good representation of my thinking                                                                                                                                                                                                                                                                     |
| ✔️    | Zotero integration                                            | Very useful to save automatically notes and highlights of a pdf in an Obsidian page and to add citations easily                                                                                                                                                                                                        |
| ✔️    | Style settings                                                | Needed to customize the theme                                                                                                                                                                                                                                                                                          |
| ✔️    | Callout manager                                               | Custom callouts                                                                                                                                                                                                                                                                                                        |
| ✔️    | Footnote shortcut                                             | Adds a very useful footnote shortcut                                                                                                                                                                                                                                                                                   |
| ✔️    | Tag wrangler                                                  | Nicer way to manage tags                                                                                                                                                                                                                                                                                               |
| ✔️    | Pinned notes                                                  | For the pinned notes in the left ribbon                                                                                                                                                                                                                                                                                |
| ✔️    | Ribbon divider                                                | For the left ribbon                                                                                                                                                                                                                                                                                                    |
| 〰️    | Emoji toolbar                                                 | Better one because I can see all the options                                                                                                                                                                                                                                                                           |
| 〰️    | Image toolkit                                                 | Useful to preview the image and to zoom in, but it's only useful for me and I don't use images that much                                                                                                                                                                                                               |
| 〰️    | Mouse wheel image zoom                                        | Increase image seize easily, but it's only useful for me and I don't use images that much                                                                                                                                                                                                                              |
| 〰️    | Advanced canvas                                               | Could be useful if I want to change extra canvas default settings                                                                                                                                                                                                                                                      |
| 〰️    | Obsidian auto node resize                                     | In case I want canvas notes to resize automatically                                                                                                                                                                                                                                                                    |
| 〰️    | Smart random notes                                            | Could be useful when I have a bigger vault                                                                                                                                                                                                                                                                             |
| ❔     | Linter                                                        | It seems that it could be useful for automating formats in footnotes, lists, etc.                                                                                                                                                                                                                                      |
| ❔     | Smart connections                                             |                                                                                                                                                                                                                                                                                                                        |
| ❔     | Excalibrain                                                   | Very good plugin with an interesting concept, but some problems<br>- New metadata is added to each note (which complexifies my vault)<br>- It could be a pain in the ass to decide on which type of relationship each link is<br>- I don't feel the need to have that extra complexity<br>- Not aesthetically pleasing |
| ❌     | Webpage HTML export                                           | Easy way to export vault to html (but still need to do it manually and manually publish it) - internal links don't work and last update was some years ago                                                                                                                                                             |
| ❌     | [Dataview](https://blacksmithgu.github.io/obsidian-dataview/) | With the new tables, this isn't needed                                                                                                                                                                                                                                                                                 |
| ❌     | Harper                                                        | Grammar corrector. Very limited                                                                                                                                                                                                                                                                                        |
| ❌     | Language tool integration                                     | Need Language tool premium                                                                                                                                                                                                                                                                                             |
| ❌     | Advanced tables                                               | Similar but worse than Notion databases                                                                                                                                                                                                                                                                                |
## Excalidraw

Because of quartz (publish to website framework), I have to display svg files on the markdown files

## Publish

See Anytype "Website hosting, domain and building"

# Limitations

Words can be limiting if not used correctly
	There are ideas that can be linked but if I use different words to describe similar ideas, then I might miss the link
		Should use the same word for the same concept
	The current definition of a word shapes how we perceive the meaning of something

# Archive

Previously in the bibliography template

```
# My notes

{% for annotation in annotations -%} 
    {%- if annotation.annotatedText -%}(Page {{annotation.page}}) *{{annotation.annotatedText}}* %%[Page {{annotation.page}}](zotero://open-pdf/library/items/{{annotation.attachment.itemKey}}?page={{annotation.page}}&annotation={{annotation.id}})%%{%- endif %} 
    {%- if annotation.imageRelativePath -%}![[{{annotation.imageRelativePath}}]]{%- endif %} 
{% if annotation.comment %}>{{annotation.comment}}{% endif %} 
{% if annotation.allTags %}>{{annotation.allTags}}{% endif %} 
{% endfor -%}
{{markdownNotes}}
```