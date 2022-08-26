# HTML
## How to structure a website ?
* HTML like alphabets of any website (A,B,C,D,E...). Because of without HTML that website doesn't exits.
* HTML - Hyper Text Markup Language

### What is Markup Language ?
* A Language in which give the instructions using tags.

### What are the Elements ?
* Elements are the individual components of HTML document.
* Every elements has different meanings.
* Inside elements has some tags. And with the help of these tags makes element.

### What is Tags ?
* Syntax of Tags  :

| Opening Tags| Syntax of Element | Closing Tags |
| --- | --- | --- |
| `<tagName>` | `texts or content` | `</tagName>` | 

* Some of the tags don't have the **closing tags**
    * **Example -** `<img src="location.jpg">` because of no text content in `img tag`

### Nesting of Elements :
    <TagName>
            <TagName>
                    <TagName>
                            <TagName>
                
                            </TagName>
                    </TagName>
            </TagName>
    </TagName>

* Element inside Element
* With the help of this we mix the properties of the elements an that forms whole document structure.
* But this is still document in the form of text we need some designs for that we use attributes.

<h3 style="background-color:DodgerBlue; color:yellow; text-align:center">What is Attributes ?</h3>
<h3 style="color:yellow;">What is Attributes ?</h3>

* Example :
    
      <h1 style="color:blue;">Welcome to Apna College</h1>
* Some additional property used in every element -
    * for example - In `img tag` we can change hight and width

          <img src="location.jpg" width="350px" high="550px">

* <p style="color:red">Syntax of attributes :</p>

    * It written in only opening tag.
    * <p style="color:lightgreen">Opening Tag</p>

          <tagName attributeName="attribute Value">
* Example :

          <p align="left">Namaste! Welcome to Apna College</p>

* Specific attributes :- which will required necessary otherwise it does't work

      <img src="location.jpg">
      <input type="text">

* Boolean Attributes :- Some attributes doesn't have value

      <input type="text" required>
      <input type="text" disabled>

* General purpose Attributes :- It can be used in every element
    1. ID :- Unique
        * It gives unique name of a specific element

              <tagname id="attribute value">

    2. Class :- None-Unique
        * It can be used more than one time

        