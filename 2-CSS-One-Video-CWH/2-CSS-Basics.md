# CSS Basics
* We will create our first CSS website in this section

## What is DOM ?
* DOM stands for `document object model` when a page is loaded, the browser creates a DOM of the page which is constructed as a tree of objects.

## HTML id and class attributes :
* When an HTML element is given an id, it serves as a unique identifier for that element.
* On the other hand, when an HTML element is given a class, it now belongs to that class. More than one element can belong to a single class but every element must have a unique id (if assigned).

* We can add multiple classes to an element like this

      <div id="first" class="c1 c2 c3">
      </div>
    * Multiple classes followed by spaces in `class` attribute
    * One class can have multiple class values.
    * Multiple classes can have same class value.

### Three ways to add CSS to HTML
* There are 3 ways to add CSS to HTML

1. `<style>` tag -> Adding `<style>...</style>` to HTML
2. Inline CSS -> Adding CSS using style attribute `style=""`
3. External CSS -> Adding a stylesheet (.css) to HTML using `<link>` tag

## CSS Selectors
* A css selectors is used to select an HTML element for styling

      body{
        color : red;      <!-- Declaration(property : value) -->
        background : pink;      <!-- declaration -->
      }
- Here `body` is selector
- 

## Element Selector
- It is used to select an based off the tag name for example :

      h2{
        color : blue;
      }
- h1, h2, div, p, span, ul, nav, main, select etc.

## ID Selector
- It is used to select an element with a given id for example :

      #first{               <!-- # is used to target by id -->
        color : white;
        background : black;
      }

## class Selector
- It is used to select an element with a given class for example :

      .red{
        background :red;
      }

## Important Notes
- We can use group selectors like this :

      h1, h2, div {
        color : blue;
      }

- We can use element.class as a selector like this :

      p.red {         <!-- all paragraph of red class will get color red -->
        color : red;
      }

- `*` Can be used as a universal selector to select all the elements

      * {
        margin : 0;
        padding : 0;
      }

- **Most Important :** An inline style will override external and internal styles
  - Inline higher priority
  - Internal low priority than inline
  - External low priority than external

## Comments in CSS
- Comments in css is text which is not parse and is thus ignored

      /* hello */

# Practice Set

1. Create a website with a class red div which has a background color of red and color white.
2. Create an element with id head and verify that background color works on it as inline, external as well as using style tag css
3. Create a css class one and verify that it works an multiple elements.
4. Create multiple css classes and verify that all of these work on the same element
5. Have a look at the MDN CSS reference and try to play around with few key-value css rules.