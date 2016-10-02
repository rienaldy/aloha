Synopsis:
	Aloha is a project to demonstrate the HTML, CSS, command line, and GIT skills learnt in the first week of the fron-end web development program at RED academy. It shows a landing page of a fictional eCommerce webpage. 


Lessons learnt & Code Example:

1. Framing in HTML and styling in CSS
2. Appropriately using classes and IDs as selectors
3. Using a CSS reset
4. Using background property. for example, the one used in the sign-up section:
	background: url(images/wave-bkgd.jpg) no-repeat center bottom;
5. Using the float property & using clearfix 
6. Demonstrate effective use of box model properties
7. Demonstrate effective use of CSS properties for altering the visual display of text (e.g. font-family, font-style, text-transform, etc.)
8. Incorporate custom fonts using @font-face. for example:
	@font-face {
		font-family: 'Raleway';
		src: url('Raleway-LightItalic.eot');
		src: url('Raleway-LightItalic.eot?#iefix') format('embedded-opentype'),
			url('Raleway-LightItalic.woff') format('woff'),
			url('Raleway-LightItalic.ttf') format('truetype'),
			url('Raleway-LightItalic.svg#Raleway-LightItalic') format('svg');
		font-weight: 300;
		font-style: italic;
	}
9. Use an icon font - using font awesome
	first by linking font awesome in the html head:
		<link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css" rel="stylesheet" integrity="sha384-T8Gy5hrqNKT+hzMclPo118YTQO6cYprQmhrYwIiQ/3axmI1hQomh7Ud2hPOy8SP1" crossorigin="anonymous">	
	And then i tagging it in the body where approriate, such as:
	<i class="fa fa-pinterest-square" aria-hidden="true"></i>
10. Use CSS3 properties where appropriate (e.g. border-radius)
12. initialize a Git repository in the root directory with a customized .gitignore file
13. Pushed to GitHub (with all commits synced to it)
14. Creating a README.md file


Design Specifications:
	Typography:

	The base font size is 16px for all screen width 600px and up (the mobile base font size is 14px)
	The body font family is Raleway Light
	The headings font family is Playfair Display
	
	Colours:

	The HEX code for the body font colour is #2d2d2d
	The HEX code for the light grey text colour is #969696
	The HEX code for orange brand colour is #e2574c (used for links, some headings, and buttons)
	The HEX code for the link hover state colour is #b64036
	The HEX code for the light grey border colour is #d7d7d7
	The HEX code for the dark grey background colour in the footer is #242424
	
	Screen Sizes:

	The width of the desktop-friendly content area is 1240px, the width of the tablet-friendly content area is 600px


