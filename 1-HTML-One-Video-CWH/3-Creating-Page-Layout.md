# Creating a Page Layout
* When we use the right tag in right place, it results in a better page layout, better indexing by search engines and better user experience.
* We use the following tag to get the job done -
## Website Layout
    <header>  (It contains nav tag)
    <main>    (It contains main content)
    <footer>

## Inside the main tag we insert the following tag -
    <main>          (The main opening tag)
        <section>   (A page section)
        </section>
        <article>   (a self contained content)
        </article>
        <aside>     (Content aside from the content eg. ads)
        </aside>
    </main>         (The main closing tag)

* Creating a page like this is not necessary but it creates a readable & structure layout. Also they are useful for SEO

## Link Attributes :
* Contact page opens in same tab -

      <a href="/contact">Contact Us</a>

* To opens in new tab -

      <a href="/contact" target="_main">Contact Us</a>
      <a href="/contact" target="_blank">Contact Us</a>

* We can put any content inside an anchor tag (images, headings etc are all allowed)

* If the page is inside directory, we need to make sure that we link to the correct page (same applies to img tag as well) for that give right path.

* We can add links to images like this

      <a href="/about"><img src="a.jpg" width="120"></a>
    * Hight will be set automatically

## Div Tag :
    <div>
        <h1>Heading H1</h1>
        <p>Heading is important is HTML</p>
    </div>
    <div>
        <h1>Why use Bootstrap</h1>
        <p>Because it beautify our web page</p>
    </div>
* Diva tag is often used as a container for other elements div is a `block` level element. (Always takes full width)

## Span Tag :
* span is an `inline` container (Takes as much as necessary)

      <span>
    
      </span>


### Inline element :
* Inline element takes only what size it wants (resize line)

      <a></a> <abbr> <acronym>
      <b></b> <bdo></bdo> <big></big> <br> <button>
      <cite> <code>
      <dfn>
      <em>
      <i> <img> <input>
      <kbd>
      <label>
      <map>
      <object> <output>
      <q>
      <samp> <script> <select> <small> <span> <strong> <sub> <sup>
      <textarea> <time> <tt>
      <var>

### Block element :
* No other can be place to right block element (Full line)

      <address> <article> <aside>
      <blockquote>
      <canvas>
      <dd> <div> <dl> <dt>
      <fieldset> <figcaption> <figure> <footer> <form>
      <h1>-<h6> <header> <hr>
      <li>
      <main>
      <nav> <noscript>
      <ol>
      <p> <pre>
      <section>
      <table> <tfoot>
      <ul>
      <video>


# Practice Set :
1. Create a SEO friendly website using HTML. (Systematic Layout)
2. Create an HTML page which opens google when clicked on an image.
3. Create a website which has your 5 top use website Bookmarked. The link should be opens in new tab.