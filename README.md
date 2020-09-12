## Refactorization for Horiseon Website
**Objective:** Refactoring existing html and css files to _meet semantic tag guidelines_ and _identify potential accessibilty issues_
![Image of Horiseon Webpage](assets/images/screenshot.png)
### Process:
**1.  Read provided HTML to identify potential issues**

The given code can be improved my applying semantic tags and alt on images
![Image of code that do not satisfy guidelines](assets/images/code-err-snip.png)

Semantic tags can make it easier for programmers to identify what segments of code control which parts of the HTML. Adding alt on images is mainly for for accessibility purposes. If the user's interface in unable to render the given image, the alt provides a description of the image sufficient for the user to understand what the image was supposed to be.

**2.  Apply fixes for the semantic tags**
1. For HTML

Examples of nonsemantic tags:
```bash
<div class="header">
<div class="content">
<div class="search-engine-optimization">
...
```
Examples of nonsemantic tag fixes:
```bash
<header>
<main class="content">
<section class="search-engine-optimization">
...
```

2. For CSS

Examples of unfixed css classes:
```bash
.header{
    ...
}
.header h1{
    ...
}
.footer{
    ...
}
.footer h2{
    ...
}
...
```
Examples of fixed css classes:
```bash
header{
    ...
}
header h1{
    ...
}
footer{
    ...
}
footer h2{
    ...
}
...
```
**3.  Apply fixes for alt on images**

