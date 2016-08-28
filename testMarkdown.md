# chari.github.io
---
layout: post
title: "Markdown quick reference for github pages"
date: 2016-08-28
category: Markdown
---

# Markdown quick reference for github pages

Below have basic syntaxes for writing [markdown] (https://en.wikipedia.org/wiki/Markdown) pages.

<!-- Headings -->

### Headings

```
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
```

> # Heading 1

> ## Heading 2

> ### Heading 3

> #### Heading 4

----

### Highlighting

```
**bold**
__bold__

*Emphasis*
_Emphasis_
```

> **bold**

> __bold__

> *Emphasis*

> _Emphasis_

----

### Lists

#### Unordered List
```
* list item 1
* list item 2
	* sub list item 1
	* sub list item 2
		* nested sub list item 1
		* nested sub list item 2

```

* list item 1
* list item 2
	* sub list item 1
	* sub list item 2
		* nested sub list item 1
		* nested sub list item 2

#### Ordered List

```

1. list item 1
2. list item 2
	1. sub list item 1
	2. sub list item 2
		1. nested sub list item 1
		2. nested sub list item 2

```

1. list item 1
2. list item 2
	1. sub list item 1
	2. sub list item 2
		1. nested sub list item 1
		2. nested sub list item 2

----

### Quoted text

```
> Quoted text.
> > Quoted text within another quoted text.

```

> Quoted text.
> > Quoted text within another quoted text.

----

### List items quoted text

```
> * Quoted 
> * List
```

> * Quoted 
> * List

----

### Code
To display code in Markdown

<pre>
```
public static void main(String arg[]) {
  System.out.println("Hello world"); 
}
```
</pre>


```
public static void main(String arg[]) {
  System.out.println("Hello world"); 
}
```
Note: symbol <code>`</code> is known as Grave. Which can be found above the <code>Tab</code> button in Keyboard.

> you can also 4 ~ (tilde) symbol at the begining and end of the code to display code as below

<pre>
~~~~
public static void main(String arg[]) {
  System.out.println("Hello world"); 
}
~~~~
</pre>

### Highlight Code

The below is the syntax to highlight java code

<pre>
``` java
public static void main(String arg[]) {
  System.out.println("Hello world"); 
}
```
</pre>

``` java
public static void main(String arg[]) {
  System.out.println("Hello world"); 
}
```

----

### Links

```
syntax :
[LinkName] (url)

e.g. 
[wiki] (https://en.wikipedia.org/wiki/Main_Page)
[google] (https://google.com)

```

Links to wiki and google pages

[wiki] (https://en.wikipedia.org/wiki/Main_Page)

[google] (https://google.com)

----

### Reference link

Unlike Normal links(previous example), the syntax for this

in previous e.g. [google] (https://google.com) the url "https://google.com" is placed within ().

In here same thing can be achieved with below code

```
[google] [1]

[1]: https://google.com

```

Usually reference links are used within a paragraph. 
e.g.

[Techtaste] [1] is my site, which is hosted on [github] [2] pages. [Jekyll] [3] used for generating this site.

[1]: http://techtaste.in "Get hands on techs"
[2]: https://github.com/Raghavendrak555 "github link"
[3]: https://jekyllrb.com/ "Learn Jekyll"

output of the above example

> [Techtaste] [1] is my site, which is hosted on [github] [2] pages. [Jekyll] [3] used for generating this site.

[1]: http://techtaste.in "Get hands on techs"
[2]: https://github.com/Raghavendrak555 "github link"
[3]: https://jekyllrb.com/ "Learn Jekyll"

----

### Table
Please refer this [post] [1] for creating tables.


The below is sample example to show how to create a table in Markdown.

```

| Tables   |      Are      |  Cool |
|:---------|:-------------:|------:|
| col 1 is |  left-aligned | $1600 |
| col 2 is |    centered   |   $12 |
| col 3 is | right-aligned |    $1 |

```

The above text in markdown generates tables as below.

| Tables        |      Are      |  Cool |
|:--------------|:-------------:|------:|
| col 1 is      |  left-aligned | $1600 |
| col 2 is      |    centered   |   $12 |
| col 3 is      | right-aligned |    $1 |

----

### Task list
These are usually checkboxes. starts either with `- [ ]` or `- [X]. The former is used to for uncheked and the later one is for checked boxes.

```

Technologies I have good knowledge on
- [x] HTML5
- [x] CSS3
- [x] JavaScript
- [x] Jquery
- [x] Angular
- [ ] Angular 2
- [x] Node.js
- [ ] React.js
- [ ] Photoshop
- [ ] UI design
- [ ] UX
- [x] Design Patterns
- [x] Data Structures & Algorithems
- [x] Jekyll
- [x] Java
- [x] Spring MVC
- [x] C++
- [x] C
- [x] Wordpress
- [x] Git
- [x] Android

Familiar with the below techs
- [x] Docker
- [x] Ansible
- [x] Gradle

```

Technologies I have good knowledge on

- [x] HTML5
- [x] CSS3
- [x] JavaScript
- [x] Jquery
- [x] Angular
- [ ] Angular 2
- [x] Node.js
- [ ] React.js
- [ ] Photoshop
- [ ] UI design
- [ ] UX
- [x] Design Patterns
- [x] Data Structures & Algorithems
- [x] Jekyll
- [x] Java
- [x] Spring MVC
- [x] C++
- [x] C
- [x] Wordpress
- [x] Git
- [x] Android

Familiar with the below techs

- [x] Docker
- [x] Ansible
- [x] Gradle

----
