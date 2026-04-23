# Day 58

Like Bill Gates said:
  "We get Comfort from those who agree with us, but
   we get Growth from only those who don't agree
   with us !"

## Today I learned:
  1. In CSS exist inline - and block elements. It's important to understand the difference.
      The inline elements only take as much space as thea need. They allow the other inline element to appear alongside them.
       Examples are: span, anchor and img.
         The CSS property is:        "display: inline;"
      The block elements take up the full width. They always start on a new line.
       Examples are: div, p, h, ol, ul and section..
         The CSS property is:        "display: block;"
  2. You can set a width to a block element (still the next element will be on the next line). But if you want to set a width or height for an inline element it doesn't work.
     This is why we use inline-block. It is the inline element (other inline alongside) but with enabled setting of width and height.
     You set it like this:    "display: inline-block;"
