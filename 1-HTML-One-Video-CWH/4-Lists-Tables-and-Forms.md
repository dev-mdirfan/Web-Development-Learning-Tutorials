# Lists, Tables and Forms

- [MDN Reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)

## Lists

- Lists are used to display content which represents a list
  - Unordered List
  - Ordered List

### Unordered List :

- Used to list unordered items

      <ul>
        <li>Home Page</li>
        <li>About Page</li>
                ....
      </ul>

- ul - unordered list
- li - list item
- ol - ordered list
- UL has `type` attribute and that has values - `circle`, `square`, `disc`

### Ordered List :

- Used to list ordered items

      <ol>
        <li>Phone</li>
        <li>PC</li>
        <li>Laptop</li>
      </ol>

- `type="I"` attribute can be the values- `A`, `a`, `I`, `i`, `1`

## Tables :

- The `<table>` tag is used to denote tables in HTML.
- It is used to format & display tabular data.

- `<tr>` tag is used to display table row
- `<td>` tag is used to display table data

- `<th>` tag is used in place of table data for displaying table headers

- We can define as many table rows as we want.

#### To add a caption to the table, we use `<caption>` tag inside table

- `<caption` tag is used for display massage before table start.

### thead and tbody Tag :
- **`<thead>` Tag :-** used to wrap table head (caption & tr with th)

  - tr & th tag will be inside thead tag for wrap caption may or may not be inside the thead tag

- **`<tbody>` Tag :** used to wrap the table body

- **thead** and **tbody** used to give css styles in a group and also easy to differentiate styles from multiple forms.
- **Note :** Don't wrap the table using `<div>` tag

### Colspan Attribute : in th tag
* This attribute is used to write calls spanning multiple columns.

      <th colspan="3">Max Score</th>
    * it spans 3 columns 

## HTML Forms :
* An HTML form is used to collect input from the user `<form>` tag is used for same
* It has attribute `action` to connect with backend

      <form action="form.php">
          ---Element of the Form---
      </form>

* There are different form elements for different kinds of user input.

### input element :
* Can be of type text, checkbox, radio, button and submit. We also have a file type
### textarea element :
* Define a multi line text input `cols` and `rows` attribute can be used to size the textarea.
### select element :
* Defines a drop down lists

      <!-- form Tag -->
      <div>
          <h1>Travel Form for our trip</h1>
          <form action="form.php">
              <!-- input Tag -->
              <input type="text" placeholder="Enter Your Name">
              <!-- label Tag -->
              <label for="sectionida">
                  <input type="radio" value="Section a" name="section" id="sectionida">Section A
              </label>
              <label for="sectionidb">
                  <input type="radio" value="Section b" name="section" id="sectionidb">Section B
              </label>
              <label for="sectionidc">
                  <input type="radio" value="Section c" name="section" id="sectionidc">Section C <br>
              </label><br>
              <label for="foodcanteen">
                  <input type="checkbox" name="canteen" id="foodcanteen" class="red">Want Food Canteen Card
              </label><br>
              <br>
              <textarea name="explain" id="explain" placeholder="Explain why you want to join" cols="30" rows="10"></textarea>
              <select name="car" id="car">
                  <option value="no-car">Select Your Car</option>
                  <option value="omni">omni</option>
                  <option value="dzire">Dzire</option>
                  <option value="i10">i10</option>
                  <option value="i20">i20</option>
              </select>
          </form>
      </div>

#### Note :
* You don't have to remember all the tags, you will automatically memorize them with practice

### Embedding Videos :
#### iframe Tag :
* From YouTube you can also embed the video (it uses `<iframe>` tag which takes all source to our page. Avoid using this)
* google doesn't allow `iframe` tag for google.com

      <!-- embedding video Tag -->
      <div>
          <!-- Embedding video from YouTube -->
          <iframe width="560" height="315" src="https://www.youtube.com/embed/xNTW2KfErTM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

          <!-- iframe Tag Example -->
          <iframe src="https://www.bing.com" frameborder="0" width="892px" height="400px"></iframe>

          <!-- iframe not working which don't allow to embed -->
          <iframe src="https://www.google.com" frameborder="0" width="400px" height="400px"></iframe>
      </div>

#### video Tag :
* `video` tag is used to play videos in HTML

      <video src="harry.mp4">Error</video>

      <div>
        <!-- video Tag from system -->
        <video src="harry.mp4" controls autoplay width="400px"></video>
      </div>

#### Attribute for video :
* We can use :
  * width : To adjust width of a video (Hight automatically adjust)
  * autoplay : We can use autoplay/loop to autoplay or loop the video


# Practice Set :
1. Create an HTML page with video embedded inside it.
2. Replace this video in 1 with a YouTube video.
3. Create an HTML form for a travel website to book a vacation.
4. Create a table displaying score of cricket players in a match using HTML.(See online site copy them in your way.)