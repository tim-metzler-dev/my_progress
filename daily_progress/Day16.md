# Day 16
Like Steven Martin said: "Be so good that they can't ignore you.

## Today I learned:
	1. That you use <em> to give special attention to a word and you use the <i> tag to make it different like other language.
	2. You use the <strong> tag for special importancy and the <b> tag to give a word special meaning like product names.
	3. I learned how to make description lists. They have three main elements:
		<dl>                                                    <!--- Description list --->
			<dt>stands for description term element</dt>
			<dd>stands for description details</dd>
		</dl>
	4. The blockquote tag. It`s for displaying an quote. You can also use paragraphs in it. It`s used like this:
		<blockquote cite="the url of the qoute or location where to find it. Like books etc.">
		Here comes the quote
		</blockquote>
	5. But if your quote  is short and you want to write it down in a paragraph you can also use the q tag:
		<q cite="…"></q>
	6. You can use the cite element also like em or such to show where you got the thing.
	7. You use the <abbr> tag if you use an abbreviation in the website. The title attribute isn`t nessacairy but it helps the user to understand your content better. Like:
		<p>I'm learning  <abbr title="Hyper Text Markup Language">HTML</abbr> right now.</p>
	8. If you want to show data of your company (email, mobile number, adress…) you should put it in the semantic <adress></adress> element instead of a div element. 
	9. To make a mobile number usable in html (you click and it will open it on your phone) you usen an anchor tag with href set to tel:+and_your_number if you want to do the same thing with an email set the href to mailto:contact@company.com. But you should know that spammers often use these mails.
	10. You use the time element in your code to describe a date and time in a paragraph. It's good to use it for SEO. You use it like this: 
		<time datetime="YYYY-MM-DDTHH:MM:SS">Date and time</time>

