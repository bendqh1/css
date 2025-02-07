## Question

Reducing 100vh to 50vh made it look better but for some reason 25vh doesn't work and brings back the original appearance. Why?

## Answer

The reason 25vh doesn’t work as expected could be related to the behavior of flexbox and how vh (viewport height) interacts with the layout.

When you set height: 50vh, it makes the .region--footer-bottom take up 50% of the viewport height, which might be enough space to display the content without gaps.

However, 25vh may not leave enough space for flexbox to properly center the content and could cause the original issue with positioning.

This may be better:

```css
min-height: 100px;
padding: 20px;
```
