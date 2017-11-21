An introduction to Html
-------------
### What is html?
###### From the [W3Schools][0] Website:

> * HTML stands for Hyper Text Markup Language
> * HTML describes the structure of Web pages using markup
> * HTML elements are the building blocks of HTML pages
> * HTML elements are represented by tags
> * HTML tags label pices of content such as "heading", "paragraph", "table", and so on
> * Browsers do not display HTML tags, but use them to render the content of the page

In short, Html is used to pass information to the browser on how to style pages.

### What are Tags?
Keywords surrounded by angle brackets that are read by the rendering engine. After parsing the file, the engine applies style based on the surrounding 'tags'.

###### For example:

```{.html caption="Hello World"}
<p>Hello World!</p>
```

###### Will produce:

> <p>Hello World!</p>

The above example uses simple paragraph tags \<p\> to enclose the plaintext between them.
Notice the \/ before the p in the second tag.
This indicates this this the closing tag tells the browser to end paragraph styling there.

There are many different tags used for templating.

###### For example:

```{.html caption="Hello Headers"}
<h1>Hello Header!</h1>
<h2>Hello Header2!</h2>
<p>Hello Paragraph!</p>
```

###### Will produce:

> <h1>Hello Header!</h1>
> <h2>Hello Header2!</h2>
> <p>Hello Paragraph!</p>

Other useful tags include ordered and unordered lists.

###### For example:

```{.html caption="Lists"}
<ol>
	<li>Item 1</li>
	<li>Item 2</li>
	<li>Item 3</li>
</ol>

<ul>
	<li>Item 1</li>
	<li>Item 2</li>
	<li>Item 3</li>
<ul>
```

###### Will produce:

><ol>
>	<li>Item 1</li>
>	<li>Item 2</li>
>	<li>Item 3</li>
></ol>
>
><ul>
>	<li>Item 1</li>
>	<li>Item 2</li>
>	<li>Item 3</li>
><ul> 


Profile Demo
------------
### Objective:
Create a pasic profile with your name in an h1 header, about me with an h2 header, a paragraph block with an a summary of yourself, include an ordered list and an unordered list of your choice (favorite movies, expectations, quick facts about yourself)

###### Example:

```{.html caption="Profil Demo"}
<h1>Matt Markwald</h1>
<h2>about me:</h2>
<p>I have been coding since April 2016.</p>
<p>I currently code in:</p>
<ul>
	<li>vb</li>
	<li>c#</li>
	<li>php</li>
	<li>html/css</li>
	<li>sql</li>
</ul>
```

###### Result:
> <h1>Matt Markwald</h1>
> <h2>about me:</h2>
> <p>I have been coding since April 2016.</p>
> <p>I currently code in:</p>
> <ul>
> 	<li>vb</li>
> 	<li>c#</li>
> 	<li>php</li>
> 	<li>html/css</li>
> 	<li>sql</li>
> </ul>


[0]: https://www.w3schools.com/html/html_intro.asp "W3Schools"
