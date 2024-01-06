We can give an exception to element B inside element A, in case element A dictates element's B behavior.

```css
@media screen and (max-width: 999px) {
  .grid-full:has(.x) {
    display: block !important;
  }
}
```

Pseudocode explanation:

<pre>
SELECT ANY ELEMENT WITH THE CLASS grid-full
IF IT **HAS** AT LEAST ONE CHILD ELEMENT WITH THE CLASS x
THEN GIVE ANY SUCH CHILD ELEMENT THE FOLLOWING **EXCEPTIONAL** CSS DIRECTIVES
</pre>
