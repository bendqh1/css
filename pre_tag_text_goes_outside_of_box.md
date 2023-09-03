Try this reset

```css
white-space: pre-line;
```

But, this may vanish all indentations anywhere in `pre` tags in the website so it might as well be better off to just add line breaks in the particular text itself.

And maybe also

```css
display: block;
position: relative;
overflow: scroll;
box-sizing: border-box;
line-break: normal;
word-wrap: break-word;
padding: 25px;
```
