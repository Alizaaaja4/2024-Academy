# In this section we're gonna talk about *those* contents or we're gonna say **Web content**.

Web contents that we see in every web are inside `<body>` element, for example we've done in setup where we type "Hello World" to check the output.
What else besides *hello world* that we can do to develop a skeleton of the web?

**Before that, I'm gonna say that html body contents are like mail, you can imagine a mail with its heading, body mail, list, footer, and the other contents of mail.**

Let's talk about heading first as it is the most important part to states the hierarchy of the text.

---
## HEADING


- ### Tags : 
  `<h1>`, `<h2>`, until `<h6>` (Don't forget about the closing tags like `</h1>`)

Now open your index.html file and fill the body with those tags, for example:
```html
<body>
    <h1>This is heading one</h1>
    <h2>This is heading two</h2>
    <h3>This is heading three</h3>
    <h4>This is heading four</h4>
    <h5>This is heading five</h5>
    <h6>This is heading six</h6>
</body>
```

#### <mark>Preview:</mark>
<body>
    <h1>This is heading one</h1>
    <h2>This is heading two</h2>
    <h3>This is heading three</h3>
    <h4>This is heading four</h4>
    <h5>This is heading five</h5>
    <h6>This is heading six</h6>
</body>

> It shows the difference of size in the text. That differences are used to states the hierarchy of the contents, such as title and sub-title.

---
Besides heading, there's some tags that will shown as a normal paragraph, the tag is.
```html
<p> *some text* </p>
```
#### <mark>Preview:</mark>
<p> *some text* </p>
==================================

That's all about Heading, next are about **List**, in Microsoft Word, you can simply choose which list that we're gonna use in paragraph bar, but in html there's several tags that we can use
to declare the list, let's see what those tags are ;D

---
## LIST
List were divided into 2 types:
1. Unordered List   : It listed not in order, usually like symbols etc.
2. Ordered List     : It listed in order, ascending or descending like numbers or character.

---
## 1. Unordered List
- ### Tags :
```html
<ul> 
    <li> *something* </li>
    <li> *something* </li>
</ul>
```
#### <mark>Preview:</mark>
<ul> 
    <li> *something* </li>
    <li> *something* </li>
</ul>

Unordered list use bullet as its pointer to the listed item, you too can add heading to the list like:
```html
<ul> 
    <li><h1> it has heading </h1> this side doesn't have heading </li>
    <li><h4> it has heading </h4> this side doesn't have heading </li>
</ul>
```
#### <mark>Preview:</mark>
<ul> 
    <li><h1> it has heading </h1> this side doesn't have heading </li>
    <li><h4> it has heading </h4> this side doesn't have heading </li>
</ul>

---
## 2. Ordered List
- ### Tags :   
```html
<ol> 
    <li> *something* </li>
    <li> *something* </li>
</ol>
```
#### <mark>Preview:</mark>
<ol> 
    <li> *something* </li>
    <li> *something* </li>
</ol>

Tags like `<ol>` wil list the item with ordered number by **default**, but you can use alphabet or roman numeral system as list with add some type attributes:

- #### Roman numeral            
```html
<ol type="I"> 
    <li> *something* </li>
    <li> *something* </li>
</ol>
```
#### <mark>Preview:</mark>
<ol type="I"> 
    <li> *something* </li>
    <li> *something* </li>
</ol>

- #### Alphabet numeral
```html
<ol type="A"> 
    <li> *something* </li>
    <li> *something* </li>
</ol>
```
#### <mark>Preview:</mark>
<ol type="A"> 
    <li> *something* </li>
    <li> *something* </li>
</ol>

- ###  Here is the list for the attributes:
<center>

| Attribute | Description |
| :-----------: | :-----------: |
| 1 | Number (default) |
| I | Roman Uppercase |
| i | Roman Lowercase |
| A | Alphabet Uppercase |
| a | Alphabet Lowercase |

</center>

---

That's all for part 1, Try some experiment like mixing its tags or make it a nested list or everything that on your mind and GOOD LUCK !!!