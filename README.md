This is testing of .md file to learn and undertsand


Examples

Text

It's very easy to make some words **bold** and other words *italic* with Markdown.
You can even [link to Google!](http://google.co.in)

Lists

Sometimes you want numbered lists:

1. One
2. Two
3. Three

Sometimes you want bullet points:

* Start a line with a star
* Profit!

Alternatively,

- Dashes work just as well
- And if you have sub points, put two spaces before the dash or star:
  - Like this
  - And this

Headers & Quotes

# Structured documents

soemtimes it's useful to have different levels of headings to structure your documents. Start lines with a `#` to create headings. Multiple `##` in a row denote smaller heading sizes.

### This is a third-tier heading

You can use one `#` all the way up to `######` size for different heading sizes.

If you'd like to quote someone, use the > character before the line:

> Coffee. The finest organic suspension ever devised... I beat the Borg with it.
> - Captain Janeway

Code

There are many different ways to style code with GitHub's markdown. If you have inline code blocks, wrap them in backticks: `var example = true`. If you've got a longer block of code, you can indent with four spaces:

	if (isAwesome) {
		return true
	}

GitHub also supports something called code fencing, which allows for multiple lines without indentation:

```
if (isAwesome) {
	return true
}
```

And if you'd like to use syntax highlighting, include the language:

```javascript
if (isAwesome) {
	return true
}
```

```c
if (isAwesome) {
	return true
}
```
Extras

GitHub supports many extras in Markdown that help you reference and link to people. If you ever want to direct a comment at someone, youcan prefix their name with an @ symbol: Hey @hexavik - love your sweater!

But I have to admit, tasks lists are my favorite:

- [x] This is a complete item
- [ ] This is an incomplete item

When you include a task list in the first comment of an Issue, you will see a helpful progress bar in your list of issues. It works in Pull Requests, too!

And, of course emoji!

# Syntax guide

Here's an overview of Markdown syntax that you can use anywhere on GitHub.com or in your own text files.

## Headers

# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag

## Emphasis

*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

## Lists

### Unordered

* Item 1
* Item 2
  * Item 2a
  * Item 2b

### Ordered

1. Item 1
1. Item 2
1. Item 3
  1. Item 3a
  1. Item 3b

### Images

![hexavik Logo](/images/logo.png)
Format: ![AltText](www.hexavik.com)

### Links

http://www.hexavik.com - automatic!
[HexaVik](http://www.hexavik.com)

### Blockquotes

As Kanye West said:

> We're living the future so
> the present is our past.

### Inline code

I think you should use an
`<addr>` element here instead.

