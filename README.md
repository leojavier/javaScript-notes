# javaScript-notes

##Chrome inspector
####DOM Manipulation
This section will have a few notes about how to manipulate the DOM `Document Object Model`


#### Selectors
Chrome has many selectors to manipulate the DOM. `querySelector` is one of them, is part of the document object and it takes the element that you want to select as an argument.

**Example: 1.0**
```sh
document.querySelector('a')
document.querySelectorALL('a')
```
*The example above (1.0) will return the first a tag from the DOM. `<a href="sample.html>link</a>"`*

The problem with the `querySelector` in this case scenario is that only returns one element. In order to return all the a tags from your DOM you should use `querySelectorALL` instead. This will return a list of all the links from the DOM.

**Example: 1.1**
```sh
document.querySelector('a')
document.querySelectorALL('a')
```
`$(a)` this function will return the same result as `querySelector` 
`$$(a)` this function will return the same result as `querySelectorAll` 

#### Make your content editable
**Example: 1.1**
```sh
document.body.contentEditable = true
```
*The example above (1.1) allows you to treat the website as a text document. You can edit, remove, or type across the DOM.*
