Give any `<a>` element the class `custom_button` to make it a button:

```css
* > .custom_button {
	word-break: break-word;
}

.custom_button {
	display: inline-flex !important;
	justify-content: space-around !important;
	align-items: center !important;
	margin: 75px auto 0 !important;
	border-radius: 10px !important;
	padding: 10px !important;

	text-align: center !important;
	font-size: 24px !important;
	font-weight: bold !important;

	text-decoration: none !important;
	-webkit-text-decoration: none !important;
	box-shadow: none !important;

	background: var(--actionColor) !important;
    color: #fff !important;
}

.custom_button:hover {
	background: #000 !important;
}


.custom_button a {
	color: #fff !important;
	text-decoration: none !important;
	border: none !important;
}

.custom_button a:hover {
	transition: unset !important;
	transition-duration: 0 !important;
	box-shadow: unset !important;
	text-decoration: none !important;

	color: #fff !important;
}
```
