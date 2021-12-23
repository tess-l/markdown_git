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
We can just add text to create a paragraph.
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



## Images



```markdown
![Alternative text](https://picsum.photos/100)
```



## Links



```markdown
[EDteam](https://ed.team)
```



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


