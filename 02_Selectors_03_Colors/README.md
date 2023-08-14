# CSS Selectors

- ## The style in head section, the internal stylesheet and stylesheet css have same precedence. The loading order decises. The last one wins out.
- ## The inline style in <p> has the highest precedence. Overwrite others.
- ## Avoid incline CSS
- ## Anatomy

  ```
  p {
    color: red;
  }

  p: Selector
  color: Property
  red: Property value
  'color: red': Declaration

  The Rule set is also called Rule
  ```

- ## When CSS rule, or declaration is wrong, it's ignored.

- ## [W3C CSS validator](https://jigsaw.w3.org/css-validator/)

- ## Specifity overrule the order of the execution
- ## Children elements injerit parent's rules
- ## Form elements, border are not inherited.
- ## button, input, select, etc.
- ## [Specifity Calculator](https://specificity.keegan.st/)

- ## [coolors.co](https://coolors.co/contrast-checker/333333-ffefd5) to check contrast

```
* universal selector */
/* * {
  font-family: monospace;
} */

html {
  font-family: monospace;
}

/* !important overide everything. But don't use it. */
main {
  color: green;
}
/* Element Selector */

/* body {
  font-size: 22px;
} */

/* h1 h2 is neted, h1, h2 are all selected */
h1,
h2 {
  color: blue;
}
.highlight {
  text-transform: uppercase;
  background-color: gold;
}

p {
  color: purple;
}
/* class selector. Starting with . */
.gray-text {
  color: gray;
}

/* id selector. Starting with # */
#second {
  font-style: italic;
}

```
