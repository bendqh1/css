# Not

```css
.region--content .block:not(#block-globalrs-content) {
	background: var(--secondaryColor);
	padding: var(--majoris);
}
```

# Has

We can give special directives to element B inside element A the following way.

```css
.a:has(.b) {
  display: block !important;
}
```

Pseudocode explanation:

<pre>
SELECT ANY ELEMENT WITH THE CLASS a
IF IT **HAS** AT LEAST ONE CHILD ELEMENT WITH THE CLASS b
THEN GIVE ANY SUCH CHILD ELEMENT THE FOLLOWING **EXCEPTIONAL** CSS DIRECTIVES
</pre>
