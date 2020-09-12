## Refactorization for Horiseon Website
**Objective:** Refactoring existing html and css files to _meet semantic tag guidelines_ and _identify potential accessibilty issues_
![Image of Horiseon Webpage](assets/images/screenshot.png)
### Process:
**1.  Read provided HTML to identify potential issues**

The given code can be improved my applying semantic tags and alt tags
![Image of code that do not satisfy guidelines](assets/images/code-err-snip.png)
**2.  Apply fixes for the semantic tags**

Examples of nonsemantic tags:
```bash
<div class="header">
<div class="content">
<div class="search-engine-optimization">
...
```
Examples of nonsemantic tag fixes:
```bash
<header
<main class="content">
<section class="search-engine-optimization">
...
```