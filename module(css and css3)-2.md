#### Q.1 What are the benefits of using CSS?
#### ans.
css offers several advantags for web devlopment:
 * separations of concerns
 * efficiency
 * consistency
 * responsiveness
 * time-saving
 * better device compatibility
 * positioning of design elements
 * better website speed
 * easier to maintain

 #### Q.2 What are the disadvantages of CSS? 
 #### ans. 
 **disadvantags:-**
 * cross-browser compatibility 
 * learning curve
 * maintence
 * Security Issues
 * Extra Work for Developers
 * Confusion due to many CSS levels
 * Cross-Browser Issues

 #### Q.3 What is the difference between CSS2 and CSS3? 
 #### ans.
 * <u> css-2 :- </u> 
 the basic toolbox with essential tools for styling fonts colors, and layouts.

 * <u> css-3 :- </u>
 a much bigger toolbox with fancy new tool for animations
 responsive,design,and richer visuals.


#### Q.4 Name a few CSS style components 
 #### ans.  
 * Selectors: Identify HTML elements to style.
* Properties: Define style attributes.
* alues: Specify settings for properties.
* Units: Measurement types.
* Media Queries: Enable responsive design .
* Pseudo-classes: Styles based on element state .
* Pseudo-elements: Target specific parts of an element .
* Layout Models: Flexbox and Grid for responsive layouts.
 

#### Q.5 What do you understand by CSS opacity? 
 #### ans.
 * 0 opacity:- completely transparent like a clear window you can see everythings behind it clearly.

 * 1 opacity:- completely opaque ( not transparent at all),like a solid background.you can't see anything behind it. 

  **Example:-**
 ```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            padding: 0%;
            margin: 0%;
            box-sizing: border-box;
        }
        img{
            height: 600px;
            width: 900px;
            opacity: 0.5;
        }
    </style>
</head>
<body>
        <img src="https://cdn.pixabay.com/photo/2024/04/19/04/39/kingfisher-8705377_1280.jpg">
</body>
</html>
 ```

 #### Q.6 How can the background color of an element be changed?  
 #### ans.
 you can change the background color of an elements in css using the background color property.simply specify the color value after the property name.

  **Example:-**
 ```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <style>
        *{
            padding: 0%;
            margin: 0%;
            box-sizing: border-box;
        }
        body{
            background-color: rgb(50, 50, 192);
        }
        .box{
            margin: 0 auto;
            height: 500px;
            width: 500px;
            background-color: lightblue;
            border-radius: 50px;
            border: 1px solid black;
        }
    </style>
  </head>
  <body>
    <div class="box">
    </div>
  </body>
</html>
 ```

 #### Q.7  How can image repetition of the backup be controlled? 
 #### ans.
image repetition in backups isn't directly controlled by css. css deals with styling webpages.not managing backups.


 **Example:-**
 ```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            padding: 0%;
            margin: 0%;
            box-sizing: border-box;
        }
       body{
        background-image: url(https://images.pexels.com/photos/147411/italy-mountains-dawn-daybreak-147411.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1); 
        background-repeat: repeat-y;
        /* background-repeat: repeat-x; */
        /* background-repeat: space; */
        /* background-repeat: round;  */
        /* background-repeat: no-repeat; */
        }
    </style>
</head>
<body>
    <div class="box">
    </div>
</body>
</html>
 ```

 #### Q.8 What is the use of the background-position property? 
 #### ans.
 the background-position property in css controls the intial placement of a background-image within its container element. imagine the background images sits on a canvas,and background-position lets you move it around on that canvas.

 **Example:-**
 ```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            padding: 0%;
            margin: 0%;
            box-sizing: border-box;
        }
        body{
            background-image: url(https://cdn.pixabay.com/photo/2017/03/27/04/37/sunset-2177324_640.jpg);
            background-repeat: no-repeat;
            background-position: top right;
           


            /* background-position: center; */
            /* background-position: top; */
            /* background-position: top left; */
            /* background-position: top right; */
            /* background-position: bottom right; */
            /* background-position: 20px 100px; */
            /* background-position: 100px 300px; */
            }
    </style>
</head>
<body>
    <div class="box"></div>
    
</body>
</html>
 ```

 #### Q.9  Which property controls the image scroll in the background? 
 #### ans.
 the property that controls how a background image scrolls in css is background attachment.

 **Example:-**
 ```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            padding: 0%;
            margin: 0%;
            box-sizing: border-box;
        }
        body {
           background-image: url(https://cdn.pixabay.com/photo/2023/08/16/21/10/cairn-8195026_640.jpg);
           background-attachment: scroll;
        
           /* background-attachment: fixed; */
           /* background-attachment: local; */

            }
    </style>
</head>
<body>
    
</body>
</html>
 ```

 #### Q.10 Why should background and color be used as separate properties? 
 #### ans.
 **(1) versatility:-** separating background and color allows for more flexibility.

**(2) complexity:-** the background property can handle multiple aspects like color image,and repetition.


 **Example:-**
 ```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body {
  background-color: #ea8a8a;
  color: #333;
}

h1 {
  background-color: #6cadf3;
  padding: 1rem;
}

p {
  background-color: #fff;
  color: #555;
  padding: 0.5rem;
}
    </style>
</head>
<body>
    <h1>chudasama divyarajsinh</h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis magnam velit ipsam quas provident vel explicabo, tempore culpa quisquam repudiandae?</p>
    
</body>
</html>
 ```


 #### Q.11 How to center block elements using CSS1?
 #### ans.
 to center block elements using css1 the main technique is:
 * set the 'width' of the block elements to fixed value.
 * set the 'margin-left' and 'margin-right' properties to 'auto'.
 this will center the block element horizontally within its parent container.

 **Example:-**
 ```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <style>
      * {
        padding: 0%;
        margin: 0%;
        box-sizing: border-box;
      }
      .box {
        text-align: center;
      }

      .inner-box {
        display: inline-block;
        text-align: left;
        margin: 10px;
      }
    </style>
  </head>
  <body>
    <div class="box">
      <div class="inner-box">box1</div>
      <div class="inner-box">box2</div>
      <div class="inner-box">box3</div>
    </div>
  </body>
</html>
 ```

 #### Q.12  How to maintain the CSS specifications?
 #### ans.
 * Consistency: Use a consistent naming convention for classes and IDs.
* Modularity: Break down your CSS into smaller, reusable components.
* Documentation: Comment your code to explain complex styles or layouts.
* Organization: Structure your CSS files logically, grouping related styles together.
* Preprocessors: Use CSS preprocessors like SASS or LESS to manage large stylesheets.
* Best Practices: Follow best practices such as BEM (Block Element Modifier) for structuring your CSS.
* Linting: Use CSS linters to enforce coding standards and catch errors.
* Responsive Design: Implement responsive design techniques to ensure your styles work across different devices.
* Version Control: Use version control systems like Git to track changes and collaborate with others.
* Testing: Regularly test your CSS in different browsers and devices to ensure compatibility

 #### Q.13 What are the ways to integrate CSS as a web page? 
 #### ans.
 there are three main ways to integrate css into a web page :

 (1) inline css:-
 Inline CSS involves adding styles directly to HTML elements using the style attribute. This is useful for applying unique styles to individual elements.

 **example:-**
 ```html
 <!DOCTYPE html>
<html>
<head>
    <title></title>
</head>
<body>
  <h1 style="color: blue;">This is a heading</h1>
</body>
</html>
 ```


 (2) internal css:-
 Internal CSS involves adding CSS styles within the < style > tags in the HTML document's < head > section. This keeps the styles organized within the same file.

 **example:-**
 ```html
 <!DOCTYPE html>
<html>
<head>
    <title></title>
  <style>
    h1 {
         color: blue; 
    }
    p {
         color: green;
          }
  </style>
</head>
<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph.</p>
</body>
</html>
 ```
 (3) external css:-
External CSS involves creating a separate CSS file and linking to it from the HTML document using the < link> element in the < head> section. This is the most common and recommended approach for larger websites.


 #### Q.14 What is embedded style sheets? 
 #### ans.
 * <u>definition:-</u> embeded css involves placing css rules directly within the html document, enclosed in '< style >' tags.


 **Example:-**
 ```html
<!DOCTYPE html>
<html>
  <head>
    <title></title>
    <style>
      body {
        background-color: #f0f0f0;
        font-family: 'Times New Roman', Times, serif;
      }

      h1 {
        color: #333;
        text-align: center;
      }

      p {
        color: #666;
        line-height: 1.5;
      }
    </style>
  </head>
  <body>
    <h1>Welcome to my website</h1>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis odio
      corporis modi minima illo ullam praesentium ex ratione, delectus fugit.
    </p>
  </body>
</html>
 ```

 #### Q.15 What are the external style sheets?
 #### ans.
  * <u>definition:-</u> external style sheets are separate css files that contain all the style definition for one or more html pages.


 **Example:-**
 ```html
 index.html:-

<!DOCTYPE html>
<html>
<head>
  <title></title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <h1>Welcome to my website</h1>
  <p>This is a paragraph tag</p>
</body>
</html>

 ```

 style.css:-
 ```css
 body {
  background-color: #f0f0f0;
  font-family: Arial, sans-serif;
}

h1 {
  color: #333;
  text-align: center;
}

p {
  color: #666;
  line-height: 1.5;
}
 ```




 #### Q.16 What are the advantages and disadvantages of using external style sheets? 
 #### ans.
 the main advantags of using external style sheets in css are:-
 (1) consistency and reusability
 (2) improved maintainability
 (3)faster lead times

 the main disadvantages of using external style sheets in css are :-
 (1) dependent on css file loading 
 (2) potential performance impact
 (3) versioning and caching challengs

 #### Q.17 What is the meaning of the CSS selector?
 #### ans.
 CSS selectors are patterns used to select and style HTML elements on a web page. They form the first part of a CSS rule and define which elements will be affected by the styles specified in the rule. Selectors can target elements based on various criteria, such as their type, class, ID, attributes, and their relationships with other elements in the document.

 #### Q.18 What are the media types allowed by CSS?
 #### ans.
 (1) all
 (2) screen
 (3) print
 (4) speech
 (5) braille
 (6) handheld


 **Example:-**
 ```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <style>
      @media screen, print {
        body {
          font-size: 16px;
        }
      }
    </style>
  </head>
  <body></body>
</html>
 ```



 #### Q.19 What is the rule set?
 #### ans.
 * selector:- the part of the rule that select the html element(s) to which the rule will be applied.
 * declaration block:- the part enclosed in curly braces '{}' that contains one or more declarations.
 * declaration:- a single rule that applies a property and value to the selected element(s). 

 **Example:-**
 ```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <style>
      /* Selector */
      h1 {
        /* Declaration Block */
        color: blue;
        font-size: 24px;
        text-align: center;
      }
    </style>
  </head>
  <body>
    <h1> hello</h1>
  </body>
</html>
 ```




 #### Q.20 Create Layouts 
 #### ans.
 ```html
 <!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <style>
      * {
        padding: 0%;
        margin: 0%;
        box-sizing: border-box;
      }
      body {
        background-color: rgb(160, 154, 154);
      }
      .card {
        height: 300px;
        width: 400px;
        background-color: #ffff;
      }
      img {
        height: 60%;
        width: 100%;
        object-fit: cover;
      }
      p {
        padding: 10px 20px;
        color: #626366;
      }
      .btns {
        display: flex;
        justify-content: space-between;
        padding: 10px 20px;
        align-items: center;
      }
      .btn a {
        text-decoration: none;
        color: black;
        border: 1px solid black;
        padding: 3px 5px;
      }
      .cards{
        display: flex;
        flex-wrap: wrap;
        gap: 30px;
        width: 1300px;
        margin: 30px auto;
      }
    </style>
  </head>
  <body>
    <div class="cards">
      <div class="card">
        <img
          src="https://cdn.pixabay.com/photo/2016/11/23/13/48/beach-1852945_1280.jpg"
        />
        <p>
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nulla beatae
          dicta officia dignissimos nisi fugit eius quia eaque eligendi sunt?
        </p>
        <div class="btns">
          <div class="btn">
            <a href="#">view</a>
            <a href="#">edit</a>
          </div>
          <div class="btn">6 hours ago</div>
        </div>
      </div>

      <div class="card">
        <img
          src="https://cdn.pixabay.com/photo/2013/07/18/20/26/sea-164989_1280.jpg"
        />
        <p>
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nulla beatae
          dicta officia dignissimos nisi fugit eius quia eaque eligendi sunt?
        </p>
        <div class="btns">
          <div class="btn">
            <a href="#">view</a>
            <a href="#">edit</a>
          </div>
          <div class="btn">6 hours ago</div>
        </div>
      </div>
      <div class="card">
        <img
          src="https://media.istockphoto.com/id/639775532/photo/taj-mahal-in-agra-india-on-sunset.jpg?s=612x612&w=0&k=20&c=_udES3mCNu1gV3YdlMy3eWa9J4dPYMBGA4IgUnx0hr0="
        />
        <p>
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nulla beatae
          dicta officia dignissimos nisi fugit eius quia eaque eligendi sunt?
        </p>
        <div class="btns">
          <div class="btn">
            <a href="#">view</a>
            <a href="#">edit</a>
          </div>
          <div class="btn">6 hours ago</div>
        </div>
      </div>
      <div class="card">
        <img
          src="https://media.istockphoto.com/id/1257164843/photo/drinks-with-blur-beach-and-sunset-in-background.jpg?s=612x612&w=0&k=20&c=46j2tTbBtTXXVXfJNH7HoEqkTbE8k919XxcOzkh4xoM="
        />
        <p>
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nulla beatae
          dicta officia dignissimos nisi fugit eius quia eaque eligendi sunt?
        </p>
        <div class="btns">
          <div class="btn">
            <a href="#">view</a>
            <a href="#">edit</a>
          </div>
          <div class="btn">6 hours ago</div>
        </div>
      </div>
      <div class="card">
        <img
          src="https://media.istockphoto.com/id/485563307/photo/silhouette-of-taj-mahal-agra-india.jpg?s=612x612&w=0&k=20&c=vwu_q4k11u3kQur5qbbp5vbAxlU4CDE8izOBpfnQVg4="
        />
        <p>
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nulla beatae
          dicta officia dignissimos nisi fugit eius quia eaque eligendi sunt?
        </p>
        <div class="btns">
          <div class="btn">
            <a href="#">view</a>
            <a href="#">edit</a>
          </div>
          <div class="btn">6 hours ago</div>
        </div>
      </div>
      <div class="card">
        <img
          src="https://media.istockphoto.com/id/1090614484/photo/golden-sunrise-over-tropical-beach.jpg?s=612x612&w=0&k=20&c=YnrlWfR6oekSZfcar2H6aa1Q2UnuEVbM0PRoWZfG-wA="
        />
        <p>
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nulla beatae
          dicta officia dignissimos nisi fugit eius quia eaque eligendi sunt?
        </p>
        <div class="btns">
          <div class="btn">
            <a href="#">view</a>
            <a href="#">edit</a>
          </div>
          <div class="btn">6 hours ago</div>
        </div>
      </div>
    </div>
  </body>
</html>
 ```
