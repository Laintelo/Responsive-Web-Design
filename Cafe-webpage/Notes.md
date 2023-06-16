# Learn basics CSS by building a Cafe Menu

In this course, I'll learn CSS by designing a menu page for a cafe webpage.

Note: For the styling of the page to look similar on mobile as it does on a desktop or laptop,
we need to add a meta element with a special content attribute:
<meta name="viewport" content="width=device-width, initial-scale=1.0" />

1. Selector CSS

With the CSS, we can add style to an element by specifying it in
the style element and setting a property for it like this:

element {
 property: value;
}

2. Div element

The div element is used mainly for design layout purposes unlike the other content
elements we have used so far.

3. Class Selector

So far we have been using type selectors to style elements.
A class selector is defined by a name with a dot directly in front of it, like this:

.class-name {
  styles
}

4. Block-level (example: p element)

p elements are block-level elements, so they take up the entire width of their parent element.
To get them on the same line, you need to apply some styling to the p elements
so they behave more like inline elements.

----------using case--------------
  <h2>Coffee</h2>
  <article>
    <p class="flavor">French Vanilla</p>
    <p class="price">3.00</p>
  </article>

  To get them on the same line, you need to apply some styling to the p elements
  so they behave more like inline elements. To do that, start by adding a class
  attribute with the value item to the first article element under the Coffee heading.
  ---------
  The p elements are nested in an article element with the class attribute of item.
  we can style all the p elements nested anywhere in elements with a class named item like this:
  .item p { }
  Using the above selector, add a display property with value inline-block so the p elements behave more like inline elements.

  -----------Using-case------------
  .item p{
  display: inline-block;
  }
  
