# Day 51
Like Tony Robbins said:
  "No matter how many mistakes you make or how slow you progress, you are still way ahead of everyone who isn't trying."


## Today I learned:
  1. There are three main ways to apply css in a web page: inline, internal, or external
  2. The inline way is using the style attribute inside the element you want to style like:
       style="color: green;"
     It isn't recommended to use, because it makes the code harder to maintain.
  3. The internal way is putting an style tag inside the HTML. like
         <style></style>
     Again this one is harder to maintain in bigger projects, because it mixes HTML and CSS.
  4. The external CSS is what we learned.
     The great thing about this is, that you can have multiple on these for dofferent things / pages. Like this:
       <link rel="stylesheet" href="styles.css">
