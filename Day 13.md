ART 342 - Day 13
=======================================

1. CSS Pre-Processors
2. Group Design Crits
3. Work Session


PREP
---------------------------------------



CLASS
---------------------------------------

### Quiz

- What are some of the features of a product website?
- What should be the main focus of a product website? (emotion OR the user)


### Housekeeping

- SHOW AND TELL WITH JASON SANTA MARIA!
- Scripts at bottom of document, not in head



### Finish Project 1 Presentations


### Interaction Inspiration
- Use quiz app to pick on random folks (3?)
- What were some of the cool interactions you found?
- What were the objectives of the sites you found?
- How did the interactions suit the content?





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
		<link rel="stylesheet/less" type="text/css" href="styles.less" />
		<script src="less.js" type="text/javascript"></script>
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

**IMPORTANT NOTE:** Don't forget, we'll be meeting next class in AB 320 for the first hour of class to attend Jason Santa Maria's Show & Tell Lecture. Give yourself a reminder! Don't be late!

1. **Rough Comps**

	We didn't get a chance today to talk about your wireframes so far, but we will be devoting the majority of class next time to discussing your work so far. Don't start jumping ahead yet; stay focused on getting the best designed site you can. Using your wireframes, start to play around with the look and feel of your sites. 
	
	Instead of focusing on filling in the details at this point, I want you to explore a breadth of design options in low fidelity. Create at least three distinct, rough design directions by next class. 


