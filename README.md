# pkg `css for dR` (v1)

A general css repository for de-liKeR for the purpose of rapid dev.  
This is especially aiming to be the base of document system, not web applications.

## Usage

`g.css`: [https://v1.css.dr-0x.com/g.css](https://v1.css.dr-0x.com/g.css)  
`area.css`: [https://v1.css.dr-0x.com/area.css](https://v1.css.dr-0x.com/area.css)  
`text.css`: [https://v1.css.dr-0x.com/text.css](https://v1.css.dr-0x.com/text.css)


## Design Concept

**This is currently developed under `version 1`**

For `version 1`, there are three main css files.

- `g.css`

This is the global css file, which is necessary for all css ecosystem of dR.  
In other words, all the design system under dR must load this file.

`g.css` is paying attention particulary the compatibility, lightness and simplicity.

In short, this is so-called `reset.css` for dR.

- `area.css`

This css file provides the area related design system.  
In dR css v1, the design concept is based on atomic design, but not the usual thing.

In many cases, atomic design provides the system based on components, like button or input field.  
However, the goal of this version is to divide atomic design into design part and function part.

So, thinking about **design's atomic design**, I reached this system.

`area.css` provides the space divider, like line and shadow. Each component which wants to use isolated space can refer to this css.

- `text.css`

Since the web consists of text, text is vital for css.  
`text.css` provides the text-related css styles.

But currently, this file is kept blank. The clear border between text and g.css cannot be considered.
