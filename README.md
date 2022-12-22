**MARKDOWN PRACTICE**

<!--Headings -->

# Heading 1 #

**Paragraph.**

*List item number one.

*List item number two.

<Hello!>

## Heading 2 ##

### Heading 3 ###
#### Heading 4 ####
##### Heading 5 #
###### Heading 6 ##

<!-- Italics -->

*Text* in italic.

_Text_ in italic.

<!-- Strong -->

**Text** is strong.

__Text__ is strong.

<!--Strikethrough: tilde -->

~~Text~~ is strikethrough.

<!-- Horizontal rule: triple hyphens or underscore to separate content -->

---
___

<!-- Show the specific characters with escape -->

\*Surround text by literal asterisk.\*

<!-- Blockquotes -->

>If you’re going to try, go all the way.

Otherwise, don’t even start.

<!--HyperLinks -->

This exercise is inspired by: 

[Daring Fireball](http://daringfireball.net/ "Daring Fireball") "Markdown: Syntax"

[Traversy Media](https://www.youtube.com/watch?v=HUBNt18RFbo) "Markdown Crash Course"

<!-- List of items -->

* Item 1.

* Item 2.
    * Nested item 2.1.
    * Nested Item 2.2.

<!-- Order list -->

1. First item.
2. Second item.

<!-- Code Block -->

[Codewars](https://www.codewars.com/kata/5266876b8f4bf2da9b000362) "Who likes it?"

```JavaScript
function likes(names) {
  if(names.length === 0){
    return "no one likes this";
  }
  else if (names.length === 1){
    return `${names[0]} likes this`;
  }
  else if (names.length === 2){
    return `${names[0]} and ${names[1]} like this` 
  }
  else if (names.length === 3){
    return `${names[0]}, ${names[1]} and ${names[2]} like this` 
} else {
    return `${names[0]}, ${names[1]} and ${names.length - 2} others like this`
  }
}
```

---
___
<!-- Image -->

![Markdown logo](https://www.google.com/search?q=markdown+logo&source=lnms&tbm=isch&sa=X&ved=2ahUKEwiK17Ly84z8AhWHr6QKHU8mBNAQ_AUoAXoECAEQAw&biw=1920&bih=969&dpr=1#imgrc=uE0aDvHJlrnEMM "Google search for Markdown logo")

<!--Task lists -->

* [x] First task
* [x] Second task
* [ ] Third task

