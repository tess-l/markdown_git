## Headers



```markdown
# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6
```



## Paragraphs



```markdown
We can just add text to create a paragraph,
using the intro/enter key we can do a line break.

By doing two line breaks we can leave the current element, this includes paragraphs, quotes, code blocks, etc.
```



## Lists



```markdown
* Not ordered list
* Item 2
    * Sub-item 1
        * Sub-item 2
* Item 3

1. Ordered list
2. Item 2
    1. Sub-item 1
        1. Sub-item 2
3. Item 3
```

> Note: for unordered lists we could use the symbols: *, -, +. And for ordered lists we can use numbers or the alphabet.



## Images



```markdown
![Alternative text](https://picsum.photos/100)
```



## Links



```markdown
[EDteam](https://ed.team)


<!-- Automatic links -->

<https:www.google.com>
```

> Note: we could use the automatic links when we would like to show the URL directly.



## Reference to images and links



If we have several links that lead to the same site we can make a reference (preferably at the end of the document) to those links:

```markdown
> Quote that has links to [Google], to visit [Google].


<!-- Reference -->

[Google]: https://www.google.com
```



For images we can do the same, replacing the URL with a word that we would like to use to make the reference, replacing the parenthesis with brackets: 

```markdown
![Alternative text][referenceToImage]


<!-- Reference -->

[referenceToImage]: https://picsum.photos/150/
```



## Comments



```markdown

<!-- This is a comment -->

```



## Text format



```markdown
We can create **bold** text and *italic*.

For strikethrough text we enclose the ~~text~~ using the ~ symbol. 

And for underlined text we use <u>the u tag</u> to enclose the text.
```

> Note: we could also use the underscore symbol instead of asterisk for bold and italic text.



## Horizontal row



To create a horizontal row, we could use three times one of the following symbols: *, -, _

```markdown

***

* * *

---

- - -

___

_ _ _

```

> Note: we could also add a blank space between them just for aesthetic as shown above.



## Quotes



```markdown
> We can create a quote by using the '>' symbol.

You could also have nested quotes  by adding more '>' symbols:

> Hello!
>> Nested quote!

```



## Code



We could write line code or code block by using the backtick symbol ( \` ). To format code or text into its own distinct block, use triple backticks to enclose the text.

```markdown
Here we will add a `line code`.
```

> Note: for the examples we used to show the syntax, we have used the triple backticks so we can create a distinct block.

When writing a code block, we can specify the language by adding the name of the language after the first tripe backticks. Markdown is going to create a class so we can manipulate it later, such as adding styles.

