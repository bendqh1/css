```css
.a_bit_about_me_wrapper {
	display: block;
	box-sizing: border-box;
	width: 100%;
}

.a_bit_about_me_text {
	margin: var(--majoris);
	padding: var(--majoris);
	background: whitesmoke;
}

.a_bit_about_me_image {
	max-width: 100%;
	height: auto;
	margin: 0 auto 0;
	padding-right: var(--majoris);
	padding-left: var(--majoris);
}

@media screen and (min-width: 999px) {
	.a_bit_about_me_wrapper {
		display: flex;
		justify-content: space-around;
		align-items: center;
	}

	.a_bit_about_me_text {
		min-height: 500px;
	}
	

	.a_bit_about_me_image {
		max-width: 50%;
		max-height: 500px;
		padding-right: 0;
		padding-left: 0;
	}
}
```
