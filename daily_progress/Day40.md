We are officially 40 days in! To everyone who is trying the same thing: Just start. And continue no matter how small the day is just continue, because repitition beats one big day!
I started completely without knowing GitHub and didn't even watched any video I just started. And you can do the same!

# Day 30
Like Dale Carnegie said: 
"If you are not in the process of becoming the person you want to be, you are automatically engaged in becoming the person you don't want to be."



## Today I learned:
	1. There are two attributes:  aria-labelledby and aria-label. They add a text label to an element that screen readers can read. They both work exactly the same. 
	2. But why do we have two different?
		You use label for elements that don't have visible text and write your own. In aria-labelledby you write down an id of another element and it will read that element.
	3. A new input type:
		  <input
		    type="range"
		    min="0"
		    max="100"
		    value="30"
		    aria-labelledby="volume-label volume-details">
		This makes the input like an setter for volume wich you can change. Max and min define the maximum value and min the minimum, while valua sets the value that is there when you did nothing with the input.
	4. To make elements invisible for people with disabilitys use:     
    aria-hidden="true"  as an attribute in your element that you want to hide. You use this to hide   Icons and images that only have a decorative purpose    or    Duplicated content.
    But keep in mind that tis only hides the element from people with accesibilitys. Later in CSS we will talk about how to hide this element from all people (hint: display: none)
