# Markdown Cheet-sheet

## Headers
# H1 header

## H2 header

### H3 header

#### H4 header

##### H5 header

###### H6 header

---

## Paragraphs and formatting
Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt doloremque eius at quod cum veniam sequi quo possimus officia iusto voluptatibus eum accusantium non, nulla est temporibus reprehenderit illum! 

Beatae odit eius neque! Optio vitae, quaerat veritatis non voluptate molestias commodi, adipisci numquam inventore accusantium tempora in distinctio illo vel!

> shorter carriage return _with two spaces_

This is line 1  
This is line 2  
This is a longer line 3

This is *Italic* or this is _italic_.  
This is **Bold** and this is __Bold__ too.  
This is how to write ***Bold and Italic***  
This is ~~scraped~~.

> This is how block quote works  
>  
> this is how to write a block quote in seperate lines.

--- 

## Horizontal LIne
---
___
***

#### they are the same look anyway...
---
## Ordered List and sublist
1. item 1
    1. sub-item 1
    2. sub-item 2
        1. sub-sub-item
2. item 2
3. item 3

    nested paragraph

    nested 2nd paragraph

> ordered item doesn't need to be in exact order

1. item 1
1. item 2
1. item 3
    

## Unordered List
- item 1
    - sub-item 1
    - sub-item 2
        - sub-sub-item
- item 2
- item 3

---
## Codes

you can write `inline code`, 

or write blocky inline code between 3 back ticks
```
/**
 * @return string = "Hello World"
 */
var foobar = () => {
    var foo = "Hello"; 
    var bar = "World";

    return foo + " " + bar;
}
```
---
## Links
[Google.com](https://google.com) or 
[Google.com](https://google.com "Google homepage")
with alt text

##### Reference
[Treehouse][1]

[1]: https://teamtreehouse.com "Reference link to Treehouse"

---
## Images
![Google](https://pbs.twimg.com/profile_images/638786550206230529/fwnBbDZF_400x400.png)

##### Link with images & alt text
[![Google](https://pbs.twimg.com/profile_images/638786550206230529/fwnBbDZF_400x400.png)
](https://google.com "Links to google.com")

---
## Tables
Year | Episode | Name | Directors
:-:|:-:|-|-
1977|4|A New Hope|George Lucas
1980|5|The Empire Strikes Back|Irvin Kershner
1983|6|Return of the Jedi|Richard Marquand

> Guide:  
> - pipe between data cell
> - space don't matter, for readability only
> - use colon  ( ***:*** ) to push data alignment
