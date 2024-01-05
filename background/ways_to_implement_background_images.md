There are several ways to implement background images.

## First way

Make the image darker in a image manipulation tool such as GIMP.

## Second way with CSS

Put the text in a `<div>` inside a `<div>` containing the image as a background image and make the first <div> to have a transparent background this way `background: rgba(0,0,0,0.50);`

## Third way with CSS (which I like the most)

```css
.homepage_after_hero {
	padding:50px;
	background-image: linear-gradient( rgba(0, 0, 0, 0.70), rgba(0, 0, 0, 0.70)) , url("IMAGE");
	background-size: cover;
	background-position: top;
	background-repeat: no-repeat;
}

.homepage_after_hero h2, .homepage_after_hero h3, .homepage_after_hero p {
	margin-block: unset !important;
	margin-bottom: 25px !important;
	color: #fff;
}
```

[Credit for DaveMaxwell from sitepoint for this third way](https://www.sitepoint.com/community/t/is-there-a-css-and-or-js-hack-to-effect-the-darkness-of-a-background-image-directly/432222/1).
