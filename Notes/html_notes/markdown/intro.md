###### [back](../../README.md)
An introduction to html
-------------
### What is html?
###### From the [W3Schools][0] Website:

> * HTML stands for Hyper Text Markup Language
> * HTML describes the structure of Web pages using markup
> * HTML elements are the building blocks of HTML pages
> * HTML elements are represented by tags
> * HTML tags label pieces of content such as "heading", "paragraph", "table", and so on
> * Browsers do not display HTML tags, but use them to render the content of the page

In short, Html is used to pass information to the browser on how to style pages.

### What are Tags?
Keywords surrounded by angle brackets that are read by the rendering engine. After parsing the file, the engine applies style based on the surrounding 'tags'.

#### Paragraph Tag
The paragraph tag is the most basic text display tag. It displays the inner-text in block format. Used for the main body of a given section.

###### For example:

```{.html caption="Hello World"}
<p>Hello World!</p>
```

###### Will produce:

> <p>Hello World!</p>

The above example uses simple paragraph tags \<p\> to enclose the plaintext between them.
Notice the \'/' before the 'p' in the second tag.
This indicates this is a closing which tells the browser to end paragraph styling there.

#### Header Tags
Header tags are used to introduce different sections of your pages. They help break up the flow of information displayed in your page and make articles easier to read.

###### For example:

```{.html caption="Hello Headers"}
<h1>Header1!</h1>
<h2>Header2!</h2>
<h3>Header3!</h3>
<h4>Header4!</h4>
```

###### Will produce:

> <h1>Header1!</h1>
> <h2>Header2!</h2>
> <h3>Header3!</h3>
> <h4>Header4!</h4>

#### List Tags
List tags can be used to separate independent sets of data. Very useful for setting information apart from bigger blocks of text.

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

### Simple html profile
#### Objective:
Create a basic profile with your name inside an h1 header, about me inside an h2 header, a paragraph block with a summary of yourself, and an ordered/unordered list on a topic of your choice (i.e. favorite movies, goals, what your learning, facts about yourself, etc).

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
> <p>I have been programming since April 2016.</p>
> <p>I currently code in:</p>
> <ul>
> 	<li>vb</li>
> 	<li>c#</li>
> 	<li>php</li>
> 	<li>html/css</li>
> 	<li>sql</li>
> </ul>


[0]: https://www.w3schools.com/html/html_intro.asp "W3Schools"
