# Notes

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
- ### button, input, select
- ## [Specifity Calculator](https://specificity.keegan.st/)
