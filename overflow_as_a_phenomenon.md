According to the CSS basic box model, an element's width and height are applied to its content box. Padding falls outside of that content box and increases the element's overall size.

As a result, if you set an element with padding to 100% width, its padding will make it wider than 100% of its containing element. In your context, inputs become wider than their parent.

One can change the way the box model treats padding and width; set the box-sizing CSS property to border-box to prevent padding from affecting an element's width or height; with some HTML elemtns that may be done automatically.
In my case I needed to do that for an <a> element, but not for a <input> element.
  
So, either we give to an **item**:

```css
box-sizing: border-box;
```  

In some cases, giving the following to **an item's container** might help:

```css
/* First, ensure that there is no "min-width" */
width: auto;
```
  
or

```css
display: flex;
```

I had a case where I some overflowing text in a table floated outside its area in mobile.
