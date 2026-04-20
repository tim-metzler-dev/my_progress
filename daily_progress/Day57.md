Like Jim Rohn said:
  "Learn from the negative as well as the positive, from the failures as well as the successes."

## Today I learned:
  1. I learned about CSS combinators. I will explain some:
       I. The descendant combinator. It is used to combine the second selector with the first one if it is an anchestor of it (parent/parent's parent) So it combines nested elements.
           For example:    figure img {border: 4px solid black;}  In this case if there are multiple images in the figure they all would get a black border.
      II. The child combinator (>). It is used to edit the direct child of an element.
           For example: div > span{...: ...;}   This sets the first child (the span directly after the div) to edit.
     III. The next-sibling combinator (+). It selects the element directly after the other one.
           For example:    img + figcaption {border: 4px solid black;}    In this example the figacaption is selected. In the code (HTML) it is : <img><figacaption></figacaption>
     III. The last is the subsequent-sibling combinator (~)  - difficult name, but easy function.
          It functions like the next-sibling combinator but also can target any siblings that follow the specified element
           For example: h2 ~ p {color: green;}    If there are many p after h2, they all will be green.
