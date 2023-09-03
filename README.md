# Intro To Markdown

## What Is Markdown?
Lightweight markup language with a plain text formatting syntax

Can be converted into HTML/XHTML and other formats

It is main purpose is readability and ease of use

Markdown uses _md_ as a file extension

Will automatically display in the GitHub repository

Is cheat sheet you can have it for future reference

## What Is It Used For?
Readme Files (GitHub, etc)

Forum & Blog Posts

Used In Many Static Site Generators

## Some Things You Can Format
##### Some of the basic types of formatting that you can do with core markdown
- Headings 
- Lists
- Emphasis -> ex:(bold & italic)
- Links
- Blocks Of Code
- Images
- Blockquotes
- Horizontal Rules


<!-- Heading -->
# Heading 1   <!-- Give us the largest heading -->
## Heading 2
### Heading 
#### Heading 4
##### Heading 5
###### Heading 6

<!-- Emphasis => Italics -->
<!-- We can wrap whateve we want to italicize -->
<!-- 
    To Escape These Characters

    We use backslash to show the asterisks next to this text 
-->
*This text* is italic   <!-- * -> asterisks -->

_This text_ is italic

<!-- Emphasis => Strong -->
<!-- We can wrap whateve we want to bold -->
**This text** is bold  

__This text__ is bold

<!-- Emphasis => Strikethrough -->
<!-- We can wrap whateve we want to strikethrough -->
~~This text~~ is strikethrough   <!-- ~ -> tilde -->

<!-- Horizontal Rule -->
<!-- It gives us these lines so you can use these to kind of separate your content -->
---  
<!-- triple underscores -->
___


<!-- Blockquotes -->
<!-- 
    We use greater than
    It just gives us like background and gives this blue line on the side here this border
 -->
> This is a quote

<!-- Links -->
<!--
    Brackets to write the Text
    Parenthesis for the link
    If you wanted to have a title where I hover over the link => inside the parenthesis we will put a space and then write your title in some quotes 
 -->
[Google](https://www.google.com)

[Google](https://www.google.com
"Google")

<!-- UL => Unordered List -->
* Item 1
* Item 2
* Item 3
    * Nested Item 1
    * Nested Item 2

<!-- OL => Ordered List -->
1. Item 1
1. Item 2
1. Item 3
    1. Item 1
    1. Item 2

<!-- Inline Code Block -->
<!-- Use one of these backticks for instance -->
`<p>This is a paragraph</p>`


<!-- Image -->
![Markdown Logo](https://markdown-here.com/img/icon256.png)

<!-- GitHub Markdown -->

<!-- Code Blocks -->

<!-- You can specify syntax specific code blocks  -->
```js
    function add(num1, num2){
        return num1 + num2;
    }
```

<!-- Tables -->
| Name     | Email                   |
| ------   | -------                 |
| Afrah    | afrah.almahdi@gmail.com |
| Mohammed | mohammed@gmail.com      |

<!-- Task Lists -->
* [x] Task 1  <!-- Complated Task -->
* [x] Task 2
* [] Task 3   <!-- Uncomplated Task -->
