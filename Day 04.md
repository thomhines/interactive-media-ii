Day 4
=======================================

1. Discuss good/bad sites from HW
2. Discuss project ideas in groups of 5
3. Wireframes tutorial


PREP
---------------------------------------
- Load up sites
- Load up [SVG Demo File](http://teaching.thomhines.com/resources/svg_template.zip)

CLASS
---------------------------------------

### Quiz

- What are the three plugins we used on Monday? (Stellar, waypoints, scrollto)
	- What do each of them do?
- What are the general steps necessary for adding a jQuery plugin to a site? (link to jquery, link to plugin JS file, add necessary code from plugin's docs)
- What is a waypoint?
- How to we make it work?
- How do we check the direction of a waypoint event?




### Housecleaning
- Any Questions from last time?
- Update your WP names so that I know who you are
- Even if you didn't get a working practice site, at least post your homework for credit and write about what went wrong!
- Clearfix
- Go over homework

### Discuss good and bad interactivity in web sites
Make a list of common things that are good and bad on the board

#### GOOD:
- simplicity
- clarity
- good navigation
- type/aesthetics
- white space
- considers audience
- affordances
- narrative
- immersive
- unique
- good interactivity
- transitions
- color cohesion
- imagery
- pacing
- hierarchy 
- information architecture
- speed
- conventions

#### BAD:

- no clear objectives
- clutter
- readability
- bad interactivity
- pop up windows
- unsolicited audio
- bad content
- lack of control
- lack of continuity
- no affordances (or) misrepresentation
- lack of contrast
- no accessibility
- broken sites
- non-responsive
- too much user control
- poor framework



### Annotated comps



### SVG Images

[Based on CSS-Tricks](http://css-tricks.com/using-svg/)
and using [SVG Demo File](http://teaching.thomhines.com/resources/svg_template.zip)


- What are they?

- Why use SVG at all?
	- Small file sizes that compress well
	- Scales to any size without losing clarity (except very tiny)
	- Looks great on retina displays
	- Design control like interactivity and filters
		- [Polygon's PS4 Review](http://www.polygon.com/a/ps4-review)

- How do we make them? (Demo this in Illustrator)


<hr>
***NOTE: SVGs don't naturally work on PSU's servers.***

In order to get them to work, you must follow these steps:


1. In Coda, navigate to your 'public_html' folder on the server.
2. In the 'public_html' folder, create a file named '.htaccess'. Note: the filename starts with a period.
3. Paste this into it:

		AddType image/svg+xml svg
		AddType image/svg+xml svgz
		
4. Hit Save

Applying this in your public_html folder will make it so that it works in all of your subfolders, so you shouldn't have to do this again! Nice!


<hr>


We can use SVG files in a few different ways:

- Link to them in an <img> 
	- Fallback: `<img src="image.svg" onerror="this.onerror=null; this.src='image.png'">`
	
- CSS Backgrounds
	- Must set proper width and height
	-  or use `background: contain;`
	
- Inline
	- Just copy and paste SVG code into HTML
	- PHP includes `<?php include("kiwi.svg"); ?>`
	
		- NOTE: In order for this to work, you have to change your file to .php and you may have to edit your .svg file and remove the first few lines of code (everything before the `<svg>` tag)

- Advanced: Modifying SVG w/ CSS. NOTE: This only works with inline and object-based SVG files
	- By using class names, you can style individual elements within an SVG
	- [Chris Coyier's Kiwi Codepen](http://codepen.io/chriscoyier/pen/evcBu)
	- [SVG Attribute Reference](https://developer.mozilla.org/en-US/docs/Web/SVG/Attribute)
	- [SVG Animated Icons](http://codepen.io/noahblon/pen/lxukH)
	- [SVG Ampersand](http://codepen.io/AliChow/pen/Lvntq)





###### Break


### Split into groups and go over wireframes. 

10 minutes per student, 2 to explain, 8 to disucss.
[Reapeaterrrr timer](http://repeaterrrr.com/oWTEQf1)

- What is the main objective of your site?
- What are the secondary objectives?
- What is the story you are trying to tell?
- What are the major interactions you want to include in your site?
- How can you involve the user more?
	












HW
---------------------------------------

1. **Design Comps**

	Design and bring in **three (3)** solid directions on the most complex or central page of your site. Stay true to the work you had done with your wireframes, but experiment with color, type, texture, etc. Each direction should feel unique and address the goals you had set for your site stylistically, and each direction should include at least two "states" or moments of interaction/animation. Post them to the blog.



### Useful Links
- [Using SVG on CSS-Tricks](http://css-tricks.com/using-svg/)
- [Building Better Interfaces with SVG](http://slides.com/sarasoueidan/building-better-interfaces-with-svg#/)
- [How to Go Beyond the Basic With SVG Filters](http://www.creativebloq.com/netmag/how-go-beyond-basics-svg-filters-71412280)