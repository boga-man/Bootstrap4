# Bootstrap Important points

## Bootstrap grid system (Layout Control)

[PDF link](https://d3c33hcgiwev3.cloudfront.net/fpUlZDA6EeiISxJZ7npQ3g_7f52f660303a11e896e5a527ee2f14ca_4-Bootstrap-Grid.pdf?Expires=1597622400&Signature=CWyhj3ggSk4f9kfIObiWwW3ziSrzeS2oeOmqcbJ4PhvjGtCVN5LF6Pi6Vyxhcn8ZfGvpk6fIgtLCB6tSxlzUJNb5XRcq~A6pP-QZgsv8wc9pIkxCdpbk94q4C1jhujaRz1DwOBSmXOl0vaf6b609OfgtcvVPjZAiJdFM1kbTxBw_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)
- Grid system helps us in designing responsive, mobile-first web pages.
- It makes use of the CSS FlexBox.
- When you specify #columns to an element, that #columns applies to that specifed screen 
  size and all the sizes above it.
  Eg: `col-sm-5` declaration means that, the element occupies 5 colums of a row for screen sizes
  small to extra large.
	- There's another class called `col-auto`, whose width will be determined by the 
	  other components in the row,
- If the #columns isn't specified, then bootstrap will automatically arrange the items.
  Eg: 1. Item1 -> `col-sm` Item2 -> `col-sm` Item3 -> `col-sm`     
      In this case, three items will be given four columns each in the same order.
  Eg: 1. Item1 -> `col-sm` Item2 -> `col-sm-6` Item3 -> `col-sm`     
      In this case, first item occupies three, second six (because it is specified) and 
      the third ocuupies remaining three columns.
- [`order-*-*`](https://stackoverflow.com/questions/51115456/bootstrap-4-ordering-class) 
  lets you decide the order of the contents in particular screen size.
- Vertical and Horizontal alignment is also possible in Bootstrap4 (since flexbox was used in this version).
  Eg: align-items-center (vertical), justify-content-center(horizontal)
- Column offsets are also possible.
  Eg: `offset-sm-1` moves the element left by one column in small and above screen sizes.
- `.jumbotron` class can be used to set its content apart from all others.