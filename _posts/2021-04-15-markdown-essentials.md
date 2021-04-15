---
layout: post
title: Markdown Essentials
---


Markdown Essentials
Strong/bold
Surround with two asterisks for strong/bold.

Surround with **two asterisks for strong/bold**.
Emphasis/italic
Surround with underscores for emphasis/italic.

Surround with _underscores for emphasis/italic_.
Links
Put link titles in square brackets and link targets in parentheses following the closing square bracket.

[Put link titles in square brackets](https://gist.github.com/raghubetina/a1b6e89e24a8c3acae6f0b63a1fd3323#links) and link targets in parentheses following the closing square bracket.
Bulleted lists
For bulleted lists: one space, followed by a dash, followed by a space, and then the item:

First bullet
Second bullet
etc
For bulleted lists: one space, followed by a dash, followed by a space, and then the item:

 - First bullet
 - Second bullet
 - etc
Technically, you don't need the space before the hyphen; but you can and I like it to help make lists visually distinct, and for aligning nested lists better.

You can also use asterisks instead of hyphens if you prefer.

Numbered lists
For numbered items, one space, followed by the number, followed by a dot, followed by a space, and then the item:

First point
Second point
etc
For numbered items, one space, followed by the number, followed by a dot, followed by a space, and then the item:

 1. First point
 2. Second point
 3. etc
Technically, you don't need the space before the number; but you can and I like it to help make lists visually distinct, and for aligning nested lists better.

Multiple blocks within list items
To nest something within the same list item, go to the next line and then indent by 4 spaces:

I am a list item that has multiple paragraphs.

This is the second paragraph of the first list item.

You can have as many paragraphs as you want.

This is the second list item.

etc

To nest something within the same list item, go to the next line and then indent by 4 spaces:

 - I am a list item that has multiple paragraphs.

    This is the second paragraph of the first list item.
    
    You can have as many paragraphs as you want.
 - This is the second list item.
 - etc
Technically, you can use any number of spaces, not just 4; as long as it's more than what you indented the first level by. I use 4 to make nested list items align nicely with parent list items.

Nesting lists within lists
You can nest other lists within lists by indenting 8 spaces, 12 spaces, etc:

Top level

Second level
3a

3b

Another paragraph in 3b.

3c

Back out to second level.
Some explanatory text still in the very first bullet.

Second top level bullet.

etc

 - Top level
    - Second level
        1. 3a
        2. 3b
        
            Another paragraph in 3b.        
        3. 3c
    - Back out to second level.
    
    Some explanatory text still in the very first bullet.
 - Second top level bullet.
 - etc
Headings
Heading level 1
Heading level 2
Heading level 3
Heading level 4
Heading level 5
Heading level 6
# Heading level 1

## Heading level 2

### Heading level 3

#### Heading level 4

##### Heading level 5

###### Heading level 6
Horizontal rules
Add horizontal rules to separate sections with three dashes.

---

Add horizontal rules to separate sections with three dashes.

---
Blockquotes
The person who chases two rabbits, catches neither.

— Confucius

> The person who chases two rabbits, catches neither.
>
> — Confucius
Inline code
Highlight variable names, etc, in the middle of a line by surrounding it with backticks.

Highlight `variable` names, etc, in the middle of a line by `surrounding` it with backticks.
Code blocks
Start a code block with a line comprised of three backticks, followed optionally by the language (if you want syntax highlighting). End the code block with another line comprised of three backticks:

class Person
  attr_accessor :first_name
  attr_accessor :last_name

  def full_name
    return self.first_name + " " + self.last_name
  end
end
```ruby
class Person
  attr_accessor :first_name
  attr_accessor :last_name

  def full_name
    return self.first_name + " " + self.last_name
  end
end
```
Tables
Generate them:

https://thisdavej.com/copy-table-in-excel-and-paste-as-a-markdown-table/
https://www.tablesgenerator.com/markdown_tables
Strikethrough
Strike something out and replace it by surrounding it with two tildes.

~~Strike something out~~ and replace it by surrounding it with two tildes.
Task lists (GitHub-only)
On GitHub, you can make interactive task lists, which e.g. add handy counters to Issues and Pull Requests indicating your progress towards completing them:

 - [x] Finish my changes
 - [ ] Push my commits to GitHub
 - [ ] Open a pull request
 Finish my changes
 Push my commits to GitHub
 Open a pull request
Task lists are not respected by most other Markdown parsers, other than GitHub's.

Converting Rich Text to Markdown
Sometimes it's useful to convert Rich Text (i.e. from Word, or copy-pasted from anywhere else really) into Markdown. Try this site for that.

