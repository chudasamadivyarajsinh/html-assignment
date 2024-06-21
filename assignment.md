### (1) are the html tags are elements the same thing?

#### ans.
html tags and element are related distinct concepts in html.
**html tags:-** these are the actual cod snippents that difine the the start and end of an html element.tags are enclosed in angle brackets.
 **example:-**`<i> this is italic </i>`
 **html elements:-** an element consists of an apening tag,content , and a closing tag. element are the building blocks of an html documents.

 ### (2) what are tags and attributes in html?
 #### ans.
 in html tags and attributes are fundamental components used to create and modify web content.
**<u>html tags:-</u>** tags are the building blocks of html.they define the structure and content of a webpage.tags are enclosed in angle brackets and usually come in pairs:an opening tag and a closing tag.the closing tag is similar to the opening tag but includes a forward slash before the tag name.

**<u>html attributes:-</u>** 
attributes provide additional information about an html element. they are included within the opening tag and come in name-value paris .the attributes name is followed by an wquals sign and the attribute value is enclosed in quotes.
**example:-** 
  ```html     
       <html>
    <head>
        <title>welcome</title>
    </head>
    <body>
        <a href="https://media-cdn.tripadvisor.com/media/photo-s/1d/f5/78/04/serenade-restaurant-bar.jpg ">
        </body>
        </html>
```

### (3) what are void elements in html?

#### ans.

 **void elements :-**
 void elements in html are elements that do not have closing tags and cannot contain any child elements or text content.these elements are self-contained and are used for specific purpose like inserting images,line breaks,or meta-information in a webpage.since they are self-closing,they are typically written with a single tag.
 ### example:-
 ```html
<html>
  <head>
    <title> example of void element</title>
    </head>
    <body>
      <img src="image.jpg">
      <br>
      <hr>
      <input type="text" name="firstname">
      <link rel="stylesheet" href="styles.css">
      </body>
      </html>
```
 
 ### (4) what are html entities?
 #### ans.
 html entities are special codes used to represent characters that have  specific meanings in html or are not easily typed on a keyboard.these entities are usedful for displaying reserved characters in html content without causing confusion in the html structure.they are also used for displaying special characters and symbols that are not available on a standard keyboard.
 ### example:-
```html
&lt;
&#65;
&#x03a9;
&copy;
&euro;
```


### (5) What are different types of lists in HTML?

#### ans.

#### (1) ordered list:-
ordered lists are used to create a list of items that are presented in a specific sequence,typically numbered.
#### example of ol tag:-

```html
 <html>
    <head>
        <title>ol tag </title>
    </head>
    <body>
        <ol type="a" start="2">
            <li> chudasama </li>
        </ol>
    </body>
</html>
```

#### (2) unoreder list :-
unorderd lists are used to create a list of items that do not need to be in a specific sequence,typically marked with bullets. 
#### example of ul tag:-

```html
<html>
    <head>
        <title> list tag </title>
    </head>
    <body>
        <ul type="square">
            <li> chudasama (a)</li>
            <li> divyarajsinh (a)</li>
        </ul>
    </body>
    </html>
```

#### (3) description list:-
* HTML < dl > element to define a description list.
* HTML < dt > element to define the description term.
* HTML < dd > element to describe the term in a description list.

#### example of description list:-

```html
<html>
  <head>
    <title>document</title>
  </head>
  <body>
    <dl>
      <dt>science</dt>
      <dd>
        Optogenetically controlled inflammasome activation demonstrates two
        phases of cell swelling during pyroptosis · TNF-α signals through ITK-
        ...
      </dd>
    </dl>
    <dl>
      <dt>social science</dt>
      <dd>
        Social science is one of the branches of science, devoted to the study
        of societies and the relationships among individuals within those
        societies.
      </dd>
    </dl>
  </body>
</html>
```

### (6) What is the ‘class’ attribute in HTML?
### ans.
In HTML, the class attribute is used to specify one or more class names for an element. It is a way to apply styling and behavior to multiple elements without needing to repeat the styles in each individual element. Here are some key points about the class attribute:
```html
<div class="container">
    <p class="intro">This is an introduction.</p>
    <p class="intro">Another introduction.</p>
</div>
```

### (7) What is the difference between the ‘id’ attribute and the ‘class’ attribute of HTML elements?

#### ans.

##### <u> id attributes:-</u>
The id attribute is used to uniquely identify an element within the document.
Each id value must be unique within a single HTML document. This uniqueness allows JavaScript and CSS to target and manipulate specific elements directly.
#### example of id attributes:-

```html
<html>
<head>
<title></title>
</head>
<body>
   <div id="header">
    <h1>Welcome</h1>
</div>
</body>
</html>
```

##### <u>class attributes:-</u>
 The class attribute is used to classify (or group) multiple elements that share similar characteristics.
Multiple elements can share the same class value. This allows you to apply styles or functionality to all elements with the same class using CSS or JavaScript.

#### example of class attributes:-

```html
<html>
<head>
<title></title>
<style></style>
</head>
<body>
<p class="intro">This is the introduction.</p>
<p class="intro">Another introduction.</p>
</body>
</html>
```

### (8) What are the various formatting tags in HTML?

#### ans.

HTML Formatting Elements
Formatting elements were designed to display special types of text:

- < b> - Bold text
- < strong> - Important text
- < i> - Italic text
- < em> - Emphasized text
- < mark> - Marked text
- < small> - Smaller text
- < del> - Deleted text
- < ins> - Inserted text
- < sub> - Subscript text
- < sup> - Superscript text

### (9) How is Cell Padding different from Cell Spacing?

#### ans.
 Parameters |	Cellpadding |	Cellspacing
|-----------|-------------|------------|
Purpose	| Cell padding is the term used to describe the area between a table cell’s border and its content.|	The gap between each neighbouring cell is often called “cellspacing.”
Process of Creation	|It may be made using the HTML table> tag but changes the type property to cell padding. |	It may be produced using the HTML table> tag. However, that changes the type property to cell spacing.
Number of Cells	| It concerns just one cell. |	It is exposed to several cells (more than one) at once.
Default Value | 	The default value for cell padding is 1.|	Cellspacing has a default value of 2.
Effectiveness|	When compared to cell spacing, it is quite effective. It is, therefore, very commonly used.|	Comparatively speaking, it is less efficient than cell padding.
### cell padding example:-
```html
<html>
<head>
    <title>Cell Padding Example</title>
    <style>
        table {
            border-collapse: collapse;
            width: 50%;
        }
        td {
            border: 1px solid black;
            padding: 20px; 
        }
    </style>
</head>
<body>
    <h2>Table with Cell Padding</h2>
    <table>
        <tr>
            <td>Cell 1</td>
            <td>Cell 2</td>
        </tr>
        <tr>
            <td>Cell 3</td>
            <td>Cell 4</td>
        </tr>
    </table>
</body>
</html>

```
### cell spacing example:-
```html
<html>
  <head>
 <title>Cell Spacing Example</title>
    <style>
        table {
            border-collapse: separate;
            border-spacing: 20px;
            width: 50%;
        }
        td {
            border: 1px solid black;
        }
    </style>
</head>
<body>
    <h2>Table with Cell Spacing</h2>
    <table>
        <tr>
            <td>Cell 1</td>
            <td>Cell 2</td>
        </tr>
        <tr>
            <td>Cell 3</td>
            <td>Cell 4</td>
        </tr>
    </table>
</body>
</html>
```


### (10) How can we club two or more rows or columns into a single row column in an HTML table?

### ans.
To combine two or more rows or columns into a single row or column in an HTML table, you can use the rowspan and colspan attributes of the < td> (table data) or < th> (table header) elements.



```html
<html>
  <head>
    <title>document</title>
  </head>
  <body>
    <table border="2" cellspacing="5" cellpendding="5">
      <caption>
        <h1>basic html table</h1>
      </caption>
      <tr>
        <th>leval1</th>
        <th>leval2</th>
        <th>leval3</th>
        <th>info</th>
        <th>name</th>
      </tr>
      <tr>
        <td rowspan="6">system</td>
        <td rowspan="4">system apps</td>
        <td rowspan="3">systemenv</td>
        <td>app test</td>
        <td>foo</td>
      </tr>
      <tr>
        <td>app memory</td>
        <td>foo</td>
      </tr>
      <tr>
        <td>app test</td>
        <td>bar</td>
      </tr>
      <tr>
        <td>systemenv2</td>
        <td>app test</td>
        <td>bar</td>
      </tr>
      <tr>
        <td rowspan="2">system memory</td>
        <td rowspan="2">memory test</td>
        <td>memory func</td>
        <td>foo</td>
      </tr>
      <tr>
        <td>apes test</td>
        <td>foo</td>
      </tr>
    </table>
  </body>
</html>
```

### (11) What is the difference between a block-level element and an inline element?

#### ans.
Block Elements|	Inline Elements|
|-------------|----------------|
Block elements always start from a new line.	|Inline elements never start from a new line.
Block elements cover space from left to right as far as it can go.|	Inline elements only cover the space as bounded by the tags in the HTML element.
Block elements have top and bottom margins.|	Inline elements don't have a top and bottom margin.
Examples of block elements - < p>,< div>,< hr> . |	Examples of inline elements - < span>,<u br>

### (12) How to create a Hyperlink in HTML?

#### ans.
Creating a hyperlink in HTML is straightforward. The < a> (anchor) tag is used to define a hyperlink, which links to another webpage or a different location within the same page. The href attribute specifies the URL of the page the link goes to.

```html
<html>
  <head>
    <title>HTML Links</title>
  </head>

  <body>
    <p>Click on the following link</p>
    <a
      href="https://media-cdn.tripadvisor.com/media/photo-s/1d/f5/78/04/serenade-restaurant-bar.jpg "
    ></a>
  </body>
</html>
```

### (13) What is the use of an iframe tag?

#### ans.
The < iframe > (inline frame) tag in HTML is used to embed another document within the current HTML document. It allows you to display content from another source on your web page, such as a webpage, PDF, video, or interactive content, without having to redirect the user to a different page.

##### example:-

```html
<html>
    <head>
        <title>my website</title>
    </head>
    <body>
        <iframe src="https://en.wikipedia.org/wiki/Wikipedia#History"
        hight="1000px"
        width="1000px"
        frameborder="2">
    </iframe>
  </body>
</html>
```

### (14) What is the use of a span tag? Explain with example?

#### ans.
The < span> tag in HTML is a generic inline container used to group and style inline elements or text with CSS. It does not add any structural meaning or line breaks to the content it wraps; instead, it is primarily used for styling purposes or for targeting specific parts of text or inline elements with CSS or JavaScript.
#### example:-

```html
<html>
  <head>
    <title>Span Tag in HTML</title>
  </head>
  <body>
    <h1>Hello Ninjas</h1>
    <p>
      Be more than a coder
      <span style="color: orangered;font-weight: bold;">
        Be a Coding Ninja!!!
      </span>
      Let the jobs chase you.
    </p>

    <p>World has enough <span id="my-section">coders</span>.</p>

    <script>
      var section = document.getElementById("my-section");
      section.style.backgroundColor = "yellow";
    </script>
  </body>
</html>
```

### (15) How to insert a picture into a background image of a web page?

#### ans.

##### How to add background image in HTML:
(1) Open the HTML file in text editor.
(2) Within the starting < body> tag in your Html file, type < Body background=” “>
(3) Give the path of the image we want to add. ( Example, < Body background=”C:Usersanshuman.singhDownloadsinfoedge.jpg “>
(4) Save the Html file in the text editor and run the file.

##### example:-

```html
<html>
  <head>
    <title>document</title>
  </head>
  <body
    background="E:\images\mahindra-thar-2020-left-front-three-quarter34.jpeg"
  ></body>
</html>
```

### (16) How are active links different from normal links?

#### ans.
* <u>normal links:-</u>
 Default state of links, styled with default browser styles (usually blue and underlined).
##### Example:-
```html
<html>
    <head>
        <title>welcome</title> 
    </head>
    <body>
        <a href ="https://www.cookingcarnival.com/wp-content/uploads/2022/04/Veg-hot-dog-4.webp">
    </body>
</html>
```

* <u>Active Links:-</u>
State of links when they are currently being interacted with (clicked but page not yet loaded), styled using :active CSS pseudo-class.
Example
```html
<html>
<head>
   <title>Difference between normal links and active links</title>
   <style>
      a:hover {
         color: red;
         background-color: transparent;
         text-decoration: underline;
      }
      a:active {
         color: yellow;
         background-color: transparent;
         text-decoration: underline;
      }
   </style>
</head>
<body>
   <h3>Click here to visit → <a href="https://www.tutorialspoint.com/">Tutorialspoint</a>
   </h3>
</body>
</html>
```
 ### (17) What are the different tags to separate sections of text?
 #### ans.
 In HTML, there are several tags that are commonly used to separate and structure sections of text within a document. These tags help organize content into logical sections, making it easier to style and manage with CSS, and also improve accessibility and SEO. Here are the main tags used to separate sections of text.
##### example:-
```html
<html>
<body>
    <section>
    <h1> to <h6>
    <p>
    <header>
    <footer>
    <nav>
    <hr>
    <br>
</body>
</html>
```
### (18) What is SVG?

#### ans.

(1) HTML SVG is used to describe the two dimensional vector and vector/raster graphics.
(2)HTML SVG is a modularized language which is used to describe graphics in XML.
(3)It describe two-dimensional vector and mixed vector/raster graphics in XML.
(4)It is a W3C recommendation.
(5)SVG images and their behaviors are defined in XML text files. So as XML files, you can create and edit an SVG image with text editor, but generally drawing programs like inkspace are preferred to create it.
(6)SVG is mostly used for vector type diagrams like pie charts, 2-Dimensional graphs in an X,Y coordinate system etc.
(7)The < svg> element specifies the root of a SVG fragment.
(8)You can animate every element and every attribute in SVG files.
 ### (19) What is difference between HTML and XHTML?
 #### ans.
 

S.No.|HTML	|XHTML
-----|------|-----
1.|	Hypertext mark-up language - - > HTML|	Extensible Hypertext Mark-up Language - - > XHTML.
2.|	Tim Berners created in 1991|	World wide web consortium or W3C created in 2000
3.|	It is an extension of standard generalized markup language or SGML|	It is a combination of extensible markup language XML and hypertext markup language HTML
4.|	It stored in a document file format	|It stored as a markup language format
5.|	It is not case sensitive as there is no mandatory rule to write the entire mark up in uppercase or lower case. It can also be a combination of both.|	It is case-sensitive, and every tag and attribute used inside must be in lowercase.





 ### (20) What are logical and physical tags in HTML?
 
 #### ans.
 in html, tags can be categorized into logical tags and physical tags based on their purpose and effect on the content. 
 * <u>logical tag:-</u>logical tags is semantic tag.define the structure and meaning of content.
 
``` html
<header>
  <nav>
    <article>
      <section>
```
 * <u>physical tag:-</u>define the appearance of content.
 
``` html
<B></B>
<I></I>
<U></U>
<small></small>
```
