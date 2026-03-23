# Day 29
Like Yoda said: “The greatest teacher, failure is.” 

## Today I learned:
 1. About the radio tag. You use it in input but with type="radio" instead of text. It's the same as any other input element.
    It shows with the name attribute wich element is in the same choice family. This Tag creates small circles that you can click to choose.
 2. About checkboxes. So like in the radio tag you only change the type to checkbox. The name also defines the "family" here.
    If you want your checkbox checked you write in the input element checked. This creates little squares wich you can check.
3. The select and option tags. You know when you are on a website and you have to pick your country? Often is used this element.
   It makes a square in wich you click and you choose your element. By default the element that is shown at start is the first.
   If you want to change it use selected in one option. This is made easy for understanding. If you want to do proffesional use value etc.:
     <select id="..." name="a">
       <option id="..." name="a">Bad</option>
       <option id="..." name="a" selected>Good</option>
4. The textarea tag. It's like an input type text but for more than one line. Like for comments. Inside of it you can use:
   cols="(it defines the visible width)" and rows="(number of visible rows/lines)"
