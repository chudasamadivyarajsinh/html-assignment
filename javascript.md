#### Q-1 What is JavaScript?

#### ans.

JavaScript is a programming language used to make web pages interactive. It allows developers to add features like animations, pop-ups, form validation, and dynamic content. It runs directly in the browser, making websites more engaging and functional.

#### Q-2 What is the use of isNaN function?

#### ans.

The isNaN() function in JavaScript is used to determine whether a value is NaN (Not-a-Number). It helps identify if a value cannot be interpreted as a valid number.

**example:-**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Add Elements Dynamically</title>
  </head>
  <body>
    <script>
      console.log(isNaN(123)); // false (123 is a number)
      console.log(isNaN("Hello")); // true ('Hello' cannot be converted to a number)
      console.log(isNaN(NaN)); // true (NaN is considered NaN)
      console.log(isNaN(undefined)); // true (undefined is not a number)
      console.log(isNaN("123")); // false ('123' can be converted to a number)
    </script>
  </body>
</html>
```

#### Q-3 What is negative Infinity?

#### ans.

Negative Infinity in JavaScript is a special value that represents a number smaller than any other number. It occurs when a negative number is divided by zero or when a value goes beyond the lowest limit JavaScript can handle.

**example:-**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Add Elements Dynamically</title>
  </head>
  <body>
    <script>
      console.log(-Infinity); // Output: -Infinity
      console.log(-Infinity < -1000); // Output: true
      console.log(-Infinity < 0); // Output: true
      console.log(-Infinity === Number.NEGATIVE_INFINITY); // Output: true
    </script>
  </body>
</html>
```

#### Q-4 Which company developed JavaScript?

#### ans.

JavaScript was developed by Netscape Communications Corporation. It was created in 1995 by Brendan Eich while he was working at Netscape. The language was originally called Mocha, later renamed to LiveScript, and finally became known as JavaScript. Its primary purpose was to enable interactive web pages and enhance the user experience on the internet.

#### Q-5 What are undeclared and undefined variables?

#### ans.

- Undeclared variables are variables that have not been declared using var, let, or const before being used. Trying to access them will cause a reference error.
- Undefined variables are variables that have been declared but not assigned a value. Their value is undefined by default.

#### Q-6 Write the code for adding new elements dynamically?

#### ans.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Add Elements Dynamically</title>
  </head>
  <body>
    <script>
      // Create a new element
      let newElement = document.createElement("p");
      newElement.textContent = "This is a new paragraph.";

      // Add the new element to the body
      document.body.appendChild(newElement);
    </script>
  </body>
</html>
```

#### Q-7 What is the difference between ViewState and SessionState?

#### ans.

- ViewState doesn’t exist, but similar functionality can be achieved using hidden fields, cookies, or localStorage to store data on the client-side for a single page.
- SessionState can be implemented using sessionStorage, which stores data on the client-side that lasts for the duration of the browser session (until the tab or browser is closed).

#### Q-8 What is === operator?

#### ans.

In JavaScript, the === operator is the strict equality operator. It compares two values for equality without performing type conversion. This means that both the value and the type must be the same for the comparison to return true.

**example:-**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Add Elements Dynamically</title>
  </head>
  <body>
    <script>
      console.log(5 === 5); // true (same type and value)
      console.log(5 === "5"); // false (different types)
      console.log(true === 1); // false (different types)
      console.log(null === undefined); // false (different types)
    </script>
  </body>
</html>
```

#### Q-9 How can the style/class of an element be changed?

#### ans.

**example:-**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Add Elements Dynamically</title>
  </head>
  <body>
    <script>
      // Changing Inline Style
      document.getElementById("myElement").style.backgroundColor = "blue";
      document.getElementById("myElement").style.fontSize = "20px";

      // Changing Class

      // className
      document.getElementById("myElement").className = "newClass";

      // classList.add()
      document.getElementById("myElement").classList.add("highlight");

      // classList.remove()
      document.getElementById("myElement").classList.remove("highlight");

      // classList.toggle()
      document.getElementById("myElement").classList.toggle("active");
    </script>
  </body>
</html>
```

#### Q-10 How to read and write a file using JavaScript?

#### ans.

Reading and Writing Files in JavaScript:
**(1) In Browsers:**

- Read: Use the File API with <input type="file">.
- Write: Create files with Blobs and use the download attribute.

**(2) In Node.js:**

- Read: Use fs.readFile() to read files.
- Write: Use fs.writeFile() to write files

#### Q-11 What are all the looping structures in JavaScript?

#### ans.

JavaScript has the following looping structures:

1. for loop
2. while loop
3. do...while loop
4. for...in loop (used to iterate over object properties)
5. for...of loop (used to iterate over iterable objects like arrays, strings, and more)
   **example:-**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Add Elements Dynamically</title>
  </head>
  <body>
    <script>
      // for Loop
      for (let i = 0; i < 5; i++) {
        console.log(i);
      }

      // while Loop
      let i = 0;
      while (i < 5) {
        console.log(i);
        i++;
      }

      // do...while Loop
      let i = 0;
      do {
        console.log(i);
        i++;
      } while (i < 5);

      // for...in Loop
      const person = { name: "Alice", age: 25 };
      for (let key in person) {
        console.log(key, person[key]);
      }

      // for...of Loop
      const array = [10, 20, 30];
      for (let value of array) {
        console.log(value);
      }
    </script>
  </body>
</html>
```

#### Q-12 How can you convert the string of any base to an integer in JavaScript?

#### ans.

To convert a string of any base to an integer in JavaScript, use the **parseInt()** function. It takes two arguments: the string to convert and the base (radix) of the number system
**example:-**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Add Elements Dynamically</title>
  </head>
  <body>
    <script>
      parseInt("1010", 2); // 10 (binary to decimal)
      parseInt("FF", 16); // 255 (hexadecimal to decimal)
      parseInt("123", 8); // 83 (octal to decimal)
    </script>
  </body>
</html>
```

#### Q-13 What is the function of the delete operator?

#### ans.

The delete operator in JavaScript is used to remove properties from an object. It deletes the specified property and returns true if successful.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Add Elements Dynamically</title>
  </head>
  <body>
    <script>
      let obj = { name: "John", age: 30 };
      delete obj.age; // Removes the 'age' property
      console.log(obj); // Output: { name: "John" }
    </script>
  </body>
</html>
```

It cannot delete variables declared with var, let, or const.

#### Q-14 What are all the types of Pop up boxes available in JavaScript?

#### ans.

In JavaScript, there are three types of popup boxes:

- alert() - Displays a simple message with an OK button.
- confirm() - Shows a message with OK and Cancel buttons, returning true or false.
- prompt() - Prompts the user for input, with OK and Cancel buttons, and returns the input value.
  **example:-**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Add Elements Dynamically</title>
  </head>
  <body>
    <script>
      // alert()
      alert("This is an alert!");

      // confirm()
      confirm("Are you sure?");

      // prompt()
      prompt("What's your name?");
    </script>
  </body>
</html>
```

#### Q-15 What is the use of Void (0)?

#### ans.

In JavaScript, **void(0)** is used to evaluate an expression and return **undefined**. It is commonly used in hyperlinks to prevent navigation. By using **href="javascript:void(0);"** in an anchor tag, you ensure that clicking the link does not cause the page to reload or navigate to another URL.

#### Q-16 How can a page be forced to load another page in JavaScript?

#### ans.

A page can be forced to load another page in JavaScript using the following methods:

(1) **window.location.href:** Assign a new URL to this property to navigate to that page.
(2) **window.location.replace():** This method navigates to a new URL without saving the current page in the session history.
**example:-**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Add Elements Dynamically</title>
  </head>
  <body>
    <script>
      // window.location.href
      window.location.href = "https://www.example.com";

      // window.location.replace
      window.location.replace("https://www.example.com");
    </script>
  </body>
</html>
```

#### Q-17 What are the disadvantages of using innerHTML in JavaScript?

#### ans.

The main disadvantages of using innerHTML in JavaScript are:

**(1) Security Risks:** It can introduce cross-site scripting (XSS) vulnerabilities if user-generated content is inserted without proper sanitization.
**(2) Performance Issues:** Replacing innerHTML causes the entire DOM subtree to be re-parsed and re-rendered, which can be inefficient for large or frequently updated content.
**(3) Loss of Event Listeners:** Replacing elements using innerHTML will remove any event listeners attached to those elements.
**(4) Limited Functionality:** It sets the content as a string, which can make manipulating complex structures more difficult compared to using DOM methods.
