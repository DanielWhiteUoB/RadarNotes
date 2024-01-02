# Hello markdown

## Basics

### Text

Like Latex, a new line is required to trigger a new paragraph. It is smart to put an empty line between anything that will be separate.

If we end a sentence with two spaces..  
then it will also introduce a line break.

### Headings 

use Hashes for headings (converts to <h6>Heading</h6>)

### Text Highlighting

Stars make text **bold**, and also _underscores_ can be used.  

If we just use one it will become _italics_. Also _**bold italics**_ is useable. Underscores and italics can be mixed and matched but seems that in Zettler the default is _**underscore-star-star**_ and the mirror image.

~~Double Tilde~~ gives us strikethrough. Single ~ is used in some other flavours.

== highlighting does not work everwhere == , is equivalent to <mark>highlighted</mark>.

We do super: e^-ipi^ (e<sup>-ipi</sup>)

And sub: H~2~O (is H<sub>2</sub>0)

:smile: emojis are possible in some. Or just copy paste 😎 

### Blocks and Special

Use the `back tick` for monospace font.

Can do check list as follows:
- [ ] unchecked
- [X] checked

Tripple backticks 
```python
for i = range(100):
	print('do the thing')
```
This is all part of the extended specification. Tabs otherwise are used.

## Links
<!-- Links are:[DisplayText](link) -->

Links can be relative (.\filepath)

[First link](.\RadarNotes.md)

Or absolute (<https://google.com>)

## Images
* From internet (not reliable)
<!-- Images are the exact same but are preceeded by a ! -->
![FromInternet](https://ieeexplore.ieee.org/mediastore_new/IEEE/content/media/9764147/9763897/9764352/9764352-fig-5-source-large.gif)

<!-- ![FigFromFile](.\Images\Misc\UoB_transparent.png "Figure caption/alt text") -->
* from file
    ![FigFromFile](.\Images\Misc\UoB_transparent.png "Figure caption/alt text")

## Blockquotes
> angle bracket
>
> text
> > which can be nested
> > which is really cool and nice

***

We above to a horiztontal rule with __astrixs__, dashes or underscores. Zettler use astrixes

***

## Lists 

### Numbered list 

1. Item 1
2. Item 2
3. Thing 3

### Bullet

* Use astrix
* Use dash
* Use plus symbol
* Then using tab or 4 spaces
    + we can do a
    + nested list
    + And mixing types:
         1. we can then do an
         2. ordered list
         3. where we start with 1. (or any number)
    + back to sub
* back to main list

## GitHub Markdown

### Table 

At least 3 dashes to separate the header, with pipes at all columns

| C1 | C2|
| ----:|:--------:|
|col1|col2|

To allign within columns, but a colon at the  end (right align) or both (center) of the dash separator 

_**|                                     EOD |**_ 