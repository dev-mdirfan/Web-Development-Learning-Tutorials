# Basic HTML Tags
We can add elements inside the body tag to define the page layout.

## HTML Element :
* Everything from starting to the ending tag

      <body>           <!-- Opening Tag -->
      -> Content <-
      </body>          <!-- Closing Tag -->

## HTML Attributes :
* Used to add more information corresponding to an HTML tag.
* ##### Example : Anchor Tag - href attribute
      <a href="https://google.com"> Google </a>
* We can either use single or double quote in attributes
* **Shortcut to multiple cursor -** `Alt` + `Click`

### Heading Tag :
* Heading tag is used to mark headings in HTML.
* From h1 to h6, we have tags for the most important to the least important headings.

      <h1> Most Important Heading </h1>
      <h2> Another Heading H2 </h2>
      <h3> Another Heading </h3>
      <h4> Another Heading </h4>
      <h5> Another Heading </h5>
      <h6> Another Heading </h6>
* **Note :** We should not use HTML headings to make that thick or bold.

### Paragraph Tag :
* Paragraph tags are used to add paragraphs to an HTML page.

      <p> This is a paragraph </p>

### Anchor Tag :
* Anchor tag is used to add links to an existing content inside an HTML page.
* ##### Example of absolute link -
      <a href="https://google.com> Click Google </a>
* ##### Example of relative link - 
      <a href="2-about.html"> Go to about </a>

### Image Tag :
* img tag is used to add images in an HTML page
* ##### Example of relative url of an image
      <img src="image.jpg" alt="Loading Error">
* ##### Example Absolute url of an image
      <img src="https://images.unsplash.com/photo-1660068226910-2e18eb033f1d?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1888&q=80" alt="Human Image">

### Bold, Italic and Underline Tags :
* We can use bold, italic and underline tags
* **Bold**

      <b> This is Bold </b>
* *Italic*

      <i> This is italic </i>
* <u>Underline</u>

      <u> This is underline </u>

### Break line - br tag
* br tag is used to create line breaks in an HTML

      <br>

### Big and Small Tag :
* We can make the text a bit longer and a bit smaller using big and small tags respectively.
* <big> Big Tag </big>

      <big> This is big </big>
* <small> Small Tag </small>

      <small>This is small<small>

### Horizontal Divider - hr tag:
* hr tag is used to create a horizontal ruler after used to separate the content.

      <hr>
<hr>

### Subscript and Superscript :
* We can add subscript and superscript in HTML as follows :
* Subscript : CO<sub>2</sub>

      <sub> Subscript <sub>

* Superscript : 10<sup>5<sup>

      <sup> Superscript </sup>

### pre tag :
* HTML always ignores extra and newlines. In order to display a price od text as is, we use pre tag.

      <pre>This is written
            using pre
            tag
      </pre>
* Example:
<pre>This is written
      as it is
      using pre tag
</pre>

## Practice Set :
1. Create an HTML page with a heading (title heading), a primary heading and a subheading. Which tag did you use?
2. Create a page with 5 wallpapers images taken from the internet.
3. Use br and hr tags to display a price of text with line breaks
4. Try to write the following chemical equation using HTML. Example : C + O<sub>2</sub> &rarr; CO<sub>2</sub>
    * Hint: [HTML arrow](https://www.w3schools.com/charsets/ref_utf_arrows.asp)
5. Try to write a wikipedia article using HTML.