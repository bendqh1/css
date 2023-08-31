Create two site branding blocks, one for sitename-siteslogan and one for the logo.

## Make sitename-siteslogan and logo one on top the other

```css
@media screen and (max-width: 1290px) {
	.region-header .block {
		float: none;
	}

	.region-header .site-branding {
		float: none;
	}

	[dir="rtl"] .region-header .block {
		float: none;
	}

	[dir="rtl"] .region-header .site-branding {
		float: none;
	}
}
```

## Make sitename-siteslogan one alongside the other

```css
@media screen and (min-width: 1291px) {
	#block-globalrs-sitebranding {
		float: right;
	}

	#block-globalrs-sitebranding-2 {
		float: left;
	}
}
```
