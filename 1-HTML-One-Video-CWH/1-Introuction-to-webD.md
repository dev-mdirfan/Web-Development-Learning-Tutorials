# Introduction
## HTML
#### HTML- Hyper Text Markup Language
* HTML is the language of the web. It is used to create websites.
* We use HTML tags to define look & feel of a website.
* With understanding of these tags and how to put them together, we can create beautiful websites easily!

#### Then why CSS & JavaScript
* HTML is used for defining layout of a page - A bare bone page structure.

## CSS
* CSS is used to add styling to that bare bone page created using HTML.

## JavaScript
* JavaScript is used to program logic for the page layout
* Example- What happen when a user hovers on a text, When to hide or show elements e.t.c

## A Beautiful Analogy
* HTML        = Car Body (Only Metal)
* CSS         = Car Paint, Decoration etc
* JavaScript  = Car Engine + Interior Logic

## Installing VS Code
* We can use any text editor of our choice. 
* Install VS Code

# HTML Tutorial -
* We start building a website by creating a file named `index.html`
* `index.html` is a special filename which is presented when the website root address is typed.

## A Basic HTML Page
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width,  initial-scale=1.0">
        <title>Document</title>
    </head>
    <body>

    </body>
    </html>
* Write this line of code with `!`+`Enter` provided by **Emmet Abbreviation**

1. `<!DOCTYPE html>` specifies this is an HTML5 Doc
2. `<html>` root of an HTML page
3. `<head>` Contains page metadata
4. `<title> Harry's Website </title>` Contains Title
5. `</head>` Closing head tag
6. `<body>` The main body of the page (rendered by browser) and visible
7. `<h1> This is a heading </h1>` Heading Tag
8. `<p> My Paragraph </p>` Paragraph Tag
9. `</body>` Closing Body Tag
10. `</html>` Closing HTML Tag

* A tag is like a container for either content or other HTML tags

    `HTML Document` + `Browser` = `Rendered Page`

#### Dummy Text :
* For crating Dummy Text - `lorem30` + `Enter`

#### Important Notes :
* **Head** & **Body** tags are children of **HTML** Tag
* **HTML** is the parent of **Head** & **Body** Tags
* Most of the **HTML** elements have the opening & closing tag with content in between opening & closing tags.
* Some **HTML** tags have no content. There are called Empty elements
    ##### Example : 
      <br>
      <hr>
* We can either use `.htm` or `.html` extension
* You can use "Inspect Element" or "View Page Source" option from chrome to look into a website's HTML code.
    * HTML Element = Start Tag + Content + End Tag

#### Comments in HTML :
* Comments in HTML are used to mark text which should not be parsed. They can help document the source code.
* **Shortcut -** `Ctrl` + `/`

      <!-- This is comment -->

#### Case Sensitive :
* HTML is a case insensitive language.
    
      <H1> and <h1> tags are the same

#### Practice Set :
1. Inspect your favorite website and change something on the page which is displayed.
2. Go to your favorite website and try to view the page source and write the exact lines of code. Does it clone the website? why?