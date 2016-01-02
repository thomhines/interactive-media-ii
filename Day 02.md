Day 2
=======================================

1. Coda Tutorial
2. Grid Frameworks

PREP
---------------------------------------

- Prep and Post [Coda clips](http://teaching.thomhines.com/342/Thom's%20Clips.clips) to Resources page
- Get URLs loaded in browser (coda plugins, frameworks)
- Post Questionnaire questions

		- What is the narrative that you are trying to show?
		- What is the primary objective of your site? Do you have other goals?
		- Who is your audience?
		- What is the overall tone that you want to convey?
		- What is the main form of interaction you want to explore? (How can you express your subject/tone through click-and-drag? scrolling? click-and-hold? hovering? hiding/revealing?)
		- How can the user express him/herself within a site about your subject?
		- Is there a particular environment/context that your site would be best in?


CLASS
---------------------------------------


### Quiz
- What version of HTML are we using?
- What folder on the web server do we put our files?
- What do we name our homepage HTML file?
- What is wrong with the following scripts.js file? ([CodePen example](http://codepen.io/thomhines/pen/rBxig))

Example:

	$(p).click(
		$(p).fadein;
	);

	Mention JS :( page on the blog.

- Go over homework



### Coda Tutorial (W14:1hr)

- Setting up sites
	- Groups
- Colors
	- Color picker
	- RGBA
	- Gradients

- List of sidebar items

- Split screen

- Code shortcuts
	- indenting
	- commenting
	

- Clips
	html5
	css
	jquery stuff
	
- Plugins
	- CSS Comb
	- PHP Tools
	- Hipster ipsum
	- EMCODA (encrypt email addresses)
		- select this, then hit **EMCODA**: asfasdf@asdfasd.com, Email me, Sucka!
	- Emmet 
		- div
		- div.container
		- div>ul>li
		- div>ul>li*5
		- div>ul>li{Item $} *5

- Books

- Publishing (try it on today's demo!)


###### Break

### Frameworks (W14:1.5hr)

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



HW
---------------------------------------
Whew, what a day! Somehow, we made it through. Have a great weekend, everyone!

1. **Create a 1-page site using a CSS frameworks**

	Using one of the frameworks we talked about in class today ([Bootstrap](http://getbootstrap.com/), [Foundation](http://foundation.zurb.com/), [Pure](http://purecss.io/), or any other comparable framework you find online, create a web page that has at least 2 columns (preferably 3 or 4, or differing amounts throughout the page), and enough filler content to make it feel kind of like a real web page. Try playing around with adding classes to buttons or form elements. If it helps, you can use the demo file from today or one of your projects from 341 to get content.
	

2. **Collect content for Project 1**

	Start to narrow your ideas down to exactly what you are going to be making your site about. Think about how your site can tell a story, what the major "plot points" will be, and how you can engage users through interaction to make the narrative more immersive and inclusive. Write a synopsis, collect some initial content/sketches/images, and describe at least a few forms of interaction that would make sense in the telling of your narrative.

		
3. **Post the your homework to WordPress**
	
	Just one last reminder that you should always post your HW to WordPress. If you want credit for your work, take the extra 30 seconds.


4. **jQuery ExTrA CrEdiT!!!!**

	For any of you who are interested in learning more about jQuery or want to get a small bump in their grade, finish the [jQuery Track](http://www.codecademy.com/tracks/jquery) on codecademy, and post a screen shot of your completed lessons to the blog.


### Useful Links
- [Coda Plugins](https://panic.com/coda/plugins.php#Plugins)
- [Thom's Coda clips](http://teaching.thomhines.com/342/Thom's%20Clips.clips)
