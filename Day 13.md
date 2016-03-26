Day 13
=======================================

1. CSS Pre-Processors
2. Group Design Crits
3. Work Session


PREP
---------------------------------------



CLASS
---------------------------------------




### Finish Project 1 Presentations



### Housekeeping

- Scripts at bottom of document, not in head



### Interaction Inspiration
- Use quiz app to pick on random folks (3?)
- What were some of the cool interactions you found?
- What were the objectives of the sites you found?
- How did the interactions suit the content?






#### Frameworks (W14:1.5hr)

Benefits:
- Takes away much of the work of coding by hand
- Tons of useful tweaks and features like clearfix, text handling, alignment, etc.
- Grid systems
- Responsive
- Form fields and the like




- [960.gs](http://960.gs/)
	- zip includes templates for sketching UI, and template files for most major image programs including Illustrator and Photoshop
	- Need to wrap 960 grid in a container:
	
		`<div class="container_12">`
	
	- This will create a box 4 columns wide in our grid:
	
		`<div class="grid_4">`

	- This will add 3 columns of space before that same box
	
		`<div class="prefix_3 grid_4">`
		
	- This will add 3 columns of space *after* that same box
	
		`<div class="suffix_3 grid_4">`

- [Fluid 960](http://www.designinfluences.com/fluid960gs/) 
	- Requires changes to class names

- [Responsive 960](https://github.com/tylerwolff/960-Responsive-Grid)
	- add 960-responsive.css after 960.css. You're done!

- [Foundation](http://foundation.zurb.com/)

- [Bootstrap](http://getbootstrap.com/)
	- Many more features, including styles for common elements and some basic jQuery plugins for creating carousels, modal dialogs, tooltips, etc.
	- RESPONSIVE!
	
	- Demo: Download bootstrap, and get one of their example templates



- [Pure](http://purecss.io/)
	- Similar to Bootstrap, but lighter.
	- Breaks several components into parts (grids, forms, menus, buttons, tables)
	- Grid system uses fractions instead of sub-columns (pure-u-1-3 for 1/3 width)


LET'S TRY IT!

[Bootstrap Example](http://teaching.thomhines.com/resources/bootstrap_example.zip) ([Complete version](http://teaching.thomhines.com/resources/bootstrap_example_complete.zip)). Have students create new Coda bookmark and upload that file to the server.

### Flexbox

[gridly](https://github.com/IonicaBizau/gridly/) - SUPER simple flexbox based CSS framework
[gridlex](http://gridlex.devlint.fr/) - More complex, basically has class names for every flexbox feature

### CSS Pre-Processors

#### [SASS](http://sass-lang.com/guide)
Better for explaining pre-processors, but not the best for using.

Here's why we're not using it:

- Requires Ruby
- No JS version
- Different code structure than LESS


#### [LESS](http://lesscss.org/)

- How to install it
	- download and upload less.min.js to server
	- link
		
		`<link rel="stylesheet/less" type="text/css" href="styles.less" />`
		`<script src="less.js" type="text/javascript"></script>`
		Make sure you include your stylesheets **before** the script.
	- change .css file to .less
	- make sure to change stylesheet link to `rel="stylesheet/less"`


- What it can do (described on lesscss.org) 
	- nesting
		nav {
			li { display: inline; }
		}
	- variables
		@bgcolor: #333;
		@bordersize: 5px;

	- math
		.sidebar { background: (@bgcolor * 3) }
	
	- mixins
		- download and open [LessHat](http://lesshat.com/)
		
			`@import "lesshat.less";`
		
		- add border-box
			
			`* {
				.box-sizing(border-box)
			}`
		
		- add rounded corners to divs

			`.border-radius(14px);`





#### The Downsides of using Pre-Processors
- Not standard
- Requires extra code to run it (JS/PHP/etc.)
- Makes it really hard to go back to normal code
	

### Go over designs in small groups


HW
---------------------------------------

Next class is cancelled, so don't come to class unless you want to meet your classmates and get direct feedback on your work. You'll have to arrange this yourselves, of course.

1. **Project 1 Self-Evaluation**

	Write 2-3 paragraphs on how you feel Project 1 went, what you learned, what you wish went differently, etc. I'd love to hear what you thought and what we should focus on next. 


2. **Rough Comps**

	We didn't get a chance today to talk about your wireframes, but we will be devoting the majority of class next time to discussing your work so far. Don't start jumping ahead yet; stay focused on getting the best designed site you can. Using your wireframes, start to play around with the look and feel of your sites. Don't worry about filling in the details at this point, I want you to explore a breadth of design options in low fidelity. Create at least three distinct, rough design directions (one page each) by next class. 



