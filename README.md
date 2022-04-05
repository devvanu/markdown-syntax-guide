# Markdown Syntax Guide

### Basic Syntax (Index) : 

[Headings](https://github.com/devvanu/markdown-syntax-guide/edit/main/README.md#headings)  
[Paragraphs](https://github.com/devvanu/markdown-syntax-guide/edit/main/README.md#paragraphs)  
[Line Breaks](https://github.com/devvanu/markdown-syntax-guide/edit/main/README.md#line-breaks)  
[Styling Texts](https://github.com/devvanu/markdown-syntax-guide/edit/main/README.md#styling-texts)  
[Blockquotes](https://github.com/devvanu/markdown-syntax-guide/edit/main/README.md#blockquotes)  
[Lists](https://github.com/devvanu/markdown-syntax-guide/edit/main/README.md#lists)  
[Quoting Code](https://github.com/devvanu/markdown-syntax-guide/edit/main/README.md#quoting-code)    
[Images](https://github.com/devvanu/markdown-syntax-guide/edit/main/README.md#images)  
[Horizontal Rule](https://github.com/devvanu/markdown-syntax-guide/edit/main/README.md#horizontal-rule)   
[Links](https://github.com/devvanu/markdown-syntax-guide/edit/main/README.md#links)  

### Advanced Syntax (Index) :  

Syntax Highlighting
Tables
Task Lists
Footnotes
Escape Sequence
Emoji
Mentioning people and teams

<br /> 

**_Note_**: Many Markdown applications allow you to use HTML tags in Markdown-formatted text. So, you can also create all the following markdown using HTML code.  

<br />

<!-- ============================ HEADINGS ======================= -->
## Headings

### #1 Markdown Method- 

    # Heading 1
    ## Heading 2
    ### Heading 3
    #### Heading 4
    ##### Heading 5
    ###### Heading 6

Output:

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

### #2 HTML Tags Method-

```
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```
Output :

<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>

### #3 Alternative Method for `<h1>` & `<h2>` tags-

```
Heading 1
=========
Heading 2
---------
```

Output :

Heading 1
=========
Heading 2
---------

<br/>

<!-- ======================= PARAGAPHS ======================== -->
## Paragraphs

To create paragraphs, use a blank line to separate one or more lines of text.

<br/>

<!-- ======================= LINE BREAKS ======================== -->
## Line Breaks

To create a line break or new line, use trailing white space (two or more spaces) or the `<br>` HTML tag at the end of the line. 

<br/>

<!-- ========================= STYLING TEXTS ====================== -->
## Styling Texts

### #1 Bold

    This is **bold text** 1
    This is __bold text__ 2
    This is b**old** text 3

Output:   

This is **bold text** 1  
This is __bold text__ 2  
This is b**old** text 3  

### #2 Italic

    This is *italicized text* 1
    This is _italicized text_ 2
    This is *italic*ized text 3
    
Output:  

This is *italicized text* 1  
This is _italicized text_ 2  
This is *italic*ized text 3 

### #3 Bold & Italic

    This is ***italic & bold*** text

Output:  

This is ***italic & bold*** text 1  
This is ___italic & bold___ text 2  
This is **_italic & bold_** text 3  
This is __*italic & bold*__ text 4  

### #4 Strikethrough

<br/>

<!-- ========================= BLOCKQUOTES ====================== -->
## Blockquotes

```
> Lorem ipsum, dolor sit amet consectetur adipisicing elit. Delectus, et?
> 
> Velit pariatur quidem similique sequi eius nihil quas vitae. Doloribus, vitae repellat.
```
Ouput:  

> Lorem ipsum, dolor sit amet consectetur adipisicing elit. Delectus, et?
> 
> Velit pariatur quidem similique sequi eius nihil quas vitae. Doloribus, vitae repellat.

### #1 Nested Blockquotes

```
> Lorem ipsum, dolor sit amet consectetur adipisicing elit. Delectus, et?
> 
>> Lorem ipsum dolor sit amet. 
```
Output:  

> Lorem ipsum, dolor sit amet consectetur adipisicing elit. Delectus, et?
> 
>> Lorem ipsum dolor sit amet. 

### #2 Blockquotes with Other Elements

```
> #### Blockquotes Best Practices!
> 
> - Try to put blank line before...
> - ... and after a blockquote.
> 
> Without *blank lines*, this might not look right.
```
Output:  

> #### Blockquotes Best Practices!
> 
> - Try to put blank line before...
> - ... and after a blockquote.
> 
> Without *blank lines*, this might not look right.

<br/>

<!-- ========================= LISTS ====================== -->
## Lists

### #1 Ordered Lists

To create, add line items with numbers followed by periods. The numbers don’t have to be in numerical order, but the list should start with the number one.

```
1. Item 1
2. Item 2
3. Item 3
    1. Sub-item 1
    2. Sub-item 2
5. Item 4
```
Ouput:  

1. Item 1
2. Item 2
3. Item 3
    1. Sub-item 1
    2. Sub-item 2
5. Item 4

### #2 Unordered Lists

To create, add dashes (-), asterisks (*), or plus signs (+) in front of line items.

```
- Item 1
- Item 2
    - Sub-item 1
    - Sub-item 2
- Item 3
- Item 4
```
Output:  

- Item 1
- Item 2
    - Sub-item 1
    - Sub-item 2
- Item 3
- Item 4

<br/>

<!-- ========================= QUOTING CODE ====================== -->
## Quoting Code

### #1 Inline Code

Put the the code or cmd within a sentence with single backticks or press `Ctrl/cmd`+`E` to insert the backticks for inline code.  

```
Use `git status` to list all new or modified files that haven't yet been committed.
```

Output:  

Use `git status` to list all new or modified files that haven't yet been committed.

### #2 Code Blocks

##### Method 1- using triple backticks

    Some basic Git Commands are:
    ```
    git init
    git status
    git add
    ```

Output:

Some basic Git Commands are:
```
git init
git status
git add
```

##### Method 2- using spaces or tab

    Normally indent the code with 4 spaces or one tab. (when they are in a list, indent them 8 spaces or 2 tabs)

Output:

    .container{
        max-width: 1200px;
    }


<br/>

<!-- ========================= IMAGES ====================== -->
## Images

```
![Alt Text](url)
```

Output: 

![Linux](https://upload.wikimedia.org/wikipedia/commons/0/09/Tux%2C_gray%EF%BC%8Fgrey_background.png)

<br/>

<!-- ========================= HORIZONTAL RULE ====================== -->
## Horizontal Rule

can create using 3 or more asterisks (***), dashes (---), or underscores (___) on a line. It's good to put blank lines before and after horizontal rule.

```
***

---

_______________
```

Output (all three will look same):  

***

<br />

<!-- ========================= Links ======================== -->
## Links

can create by enclosing link text in brackets and then follow it with URL in parantheses.

```
Search this on [Google](https://www.google.com/) instead.
```

Search this on [Google](https://www.google.com/) instead.

### #1 Adding Titles to the Link

You can add a title to a link by enclosing it in quotation marks after URL, but it's optional. This will appear as a tooltip when the user hovers over the link.

```
Search this on [Google](https://www.google.com/ "Google") instead.
```

### #2 URLs & Email Addresses
