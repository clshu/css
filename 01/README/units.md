# CSS Units

- ## Let browser decides font-size. Don't use <html> to set font size.
- ## px,1/96th inch. Default font size 16px. 1/96th inch. The only absolute size to use.
- ## percent, by default 100% (relative to the parent)
- ## rem relative to the font size of the root element. Default 1rem
- ## em -> rem -> root element font size. Usually used in padding, margin. Releative to the font size of the element. e.g. Button padding
- ## ch: From paper printers. Based on the
- ## vw: IT doesn't count rolling bar". % better
  ```
  No.
  body {
    height: 100vw;
  }
  Yes.
  body {
    min-height: 100vh;
  }
  ```
