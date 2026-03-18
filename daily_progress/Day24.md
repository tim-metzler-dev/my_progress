# Day24
Like Jerry Rice: "Today I will do what others won't, so tomorrow I can accomplish what others can't."

	
## Today I learned:
	1. You can make required elements inside your form. 
		<form action="">
		  <label for="…">… (Required field):</label>
		  <input
		    required  <---! That makes the type to a "test" like for email it tests if you have an @." --->
		    type="…(like email wich will make it required to use an @)"
		    name="you understand"
		    id="…"
		    minlength="how many characters the form must contain at least."
		    maxlength="how many characters the form can contain at max."
		  />
		  <button type="submit">Submit Form</button>
		</form>
	2. You have different states of an form. For the example i'll use onle the input tag instead of the full form etc. tag:
		A. The disabled state. (it makes impossible for the user to click on the form. It is disabled! (Guess everyone could have thougt that :) ))
			<input disabled type="email" name="email" id="email" />
		B. The readonly state. It makes impossible for the user to write down something in the form but they can use read what stands in value.
			<input
			  readonly
			  type="email"
			  name="email"
			  id="email"
			  value="example@email.com"
			/>
