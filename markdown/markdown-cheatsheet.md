##### Table of Contents  
[Headers](#headers)  
[Emphasis](#emphasis)  
[Lists](#lists)  
[Links](#links)  
[Images](#images)  
[Code](#code)  
[Tables](#tables)  
[Blockquotes](#blockquotes)  
[Inline HTML](#html)  
[Horizontal Rule](#hr)  

## Headers

```no-highlight
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

# H1
## H2
### H3
#### H4
##### H5
###### H6

## Emphasis

```no-highlight
Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~
```

Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~

## Lists

Unordered list can use asterisks asterisks, pluses, and hyphens - interchangably.

```no-highlight
* asterisks
- hyphens
+ pluses
```
* asterisks
- hyphens
+ pluses

Ordered lists use numbers followed by periods.

```no-highlight
1. Item 1
2. Item 2
3. Item 3
```
1. Item 1
2. Item 2
3. Item 3

## Links

There are two ways to create links (inline and reference).

```no-highlight
[This is a inline-style link](https://example.com)

[This is a inline-style link with title](https://www.example.com "Example's Homepage")

[This is a reference-style link][Arbitrary case-insensitive reference text]

[This is relative path reference to a local resource](../home/me/README.md)

[You can use numbers for reference-style link definitions][1]

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: https://dev.java
```

[This is a inline-style link](https://example.com)

[This is a inline-style link with title](https://www.example.com "Example's Homepage")

[This is a reference-style link][Arbitrary case-insensitive reference text]

[This is relative path reference to a local resource](../home/me/README.md)

[You can use numbers for reference-style link definitions][1]

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: https://dev.java

## Images

```no-highlight
Here's our logo (hover to see the title text):

Inline-style: 
![alt text](https://openjdk.java.net/images/duke-thinking.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://openjdk.java.net/images/duke-thinking.png "Logo Title Text 2"
```

Here's our logo (hover to see the title text):

Inline-style: 
![alt text](https://openjdk.java.net/images/duke-thinking.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://openjdk.java.net/images/duke-thinking.png "Logo Title Text 2"

## Code 

To indicate a span of code, wrap it with backtick quotes (`)

```no-highlight
Inline `code` has `back-ticks around` it.
```

Inline `code` has `back-ticks around` it.

Blocks of code are either fenced by lines with three back-ticks (```)

<pre lang="no-highlight"><code>```javascript
let s = "JavaScript syntax highlighting";
console.log(s);
```</code></pre>

```javascript
let s = "JavaScript syntax highlighting";
console.log(s);
```

<pre lang="no-highlight"><code>```java
String s = "Java syntax highlighting"
System.out.print(s);
```</code></pre>

```java
String s = "Java syntax highlighting"
System.out.print(s);
```

## Tables

* Colons can be used to align columns.
* There must be at least 3 dashes separating each header cell. 
* The outer pipes (|) are optional
* There's no need to make the raw Markdown line up prettily

```no-highlight
| A             | B     | C |
| ------------- |:-----:| ----:
| XXXX          | YYY   |ZZZZZZ|
| 111111        | 22222 |3
```

| A             | B     | C |
| ------------- |:-----:| ----:|
| XXXX          | YYY   |ZZZZZZ|
| 111111        | 22222 |3|

## Blockquotes

```no-highlight
>Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
>Fusce vehicula malesuada massa, eget fermentum erat volutpat mattis. Duis et commodo.
```
>Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
>Fusce vehicula malesuada massa, eget fermentum erat volutpat mattis. Duis et commodo.

## Inline HTML

You can use raw HTML.

```no-highlight
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
```

<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>


## Horizontal Rule

Three or more:

```
---
***
___
```
---
***
___