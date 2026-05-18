# Day 85
Like Casey Neistat said:
  "The most dangerous thing you can do in life is play it safe."

## Today I learned:
  1. Background-gradient. This is like a color transition between colors. You can use it as a background even without an image.
     You use it with:     background: linear/radial-gradient(); But what is linear and radial gradient? And how does ist works and effects?
     a. background: linear-gradient(direction, color-stop1, color-stop2, ...); I'll explain everything here.
       I. direction:   So what is direction. It defines from wich to wich side the colors go. You can write:   45deg; to right, to bottom or side/corner.
      II. color-stopX: That are the colors that are in the transition. So you csn have as many steps as you want.
     b. background: radial-gradient(shape size at position, color-stop1, color-stop2, ...)
       I. shape:       You have to choose between circle or ellipse. This defines the shape (I think that is understandable)
      II. size:        closest-side, closest-corner, farthest-side or farthest-corner. This defines where it will end. I think also understandable - size
     -      at:        Just a fillword
     III. position:    Here you can use keywords like center, top left, bottom right or procent data (15% 20% 5% 18%)
     -- You should understand colorstop. Try it out. It is funny!
  2. Accesibility- Again! So you should have high contrast and don't use hard to see pictures with much texture and everything.
  3. Let's talk a bit about borders. You make a border with:
         border: Xpx solid color;
     But what makes solid and are there other things like it?
       a. solid- this makes a solid line. A going line without any white spaces between it.
       b. dashed- This makes -as the name sais- a dashed line. It is like: "- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -"
       c. dotted- like the name said this makes a dotted line. I think you can understand it. So some dots around the img.
       d. double- makes a double thin line with your px.value - the line thickness.
  4. I'm very excited for this. It's the border-radius. You know when you don't have sharp edges but round things? Right. This property makes it. And you even could make a circle with it!


That's all for today. But that's a good stuff for 5 body battery from 18:12 (now it is 20:16)
