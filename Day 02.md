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
- How many classes can you miss without it affecting your grade?
- Where does EVERY ASSIGNMENT need to be posted in order to get credit?
- How can you tell if I've given you credit for an assignment?
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



### Web Review





#### Positioning Presentation

Great place to look at layout info: [learnlayout.com](http://learnlayout.com/)


Load Layout Demo Files [(Empty)](http://teaching.thomhines.com/resources/positioning_template_empty.zip) [(Complete)](http://teaching.thomhines.com/resources/positioning_template_complete.zip)


- Make columns border-box so you can adjust paddings on each column without breaking layout

- Add <span class="dropcap"> to first letter in .main paragraph to demo spans

- Clearfix to make floats work out properly

- Make top-right badge appear in main column, not top right of page



Starting from this [multi-column template](http://teaching.thomhines.com/resources/2_col_html_template.zip) file, do the following:

- Tweak Basic CSS properties (including adding classes)
- Make multi-column
- Add link to jQuery (and scripts.js)
- Add events for click and hover











###### Break




### Media Queries Presentation

Add to work done before break and add responsiveness

Show them:

- [mediaqueri.es](http://mediaqueri.es/)
- [Responsive Doge](http://responsivememe.webflow.com/)



Add the following code to the responsive_template_empty CSS file:
	
	/* Responsive Styles */
	
	@media screen and (max-width: 800px) {
	
		body {
			background: #513737;
		}
		
		.container {
			width: 100%;
			margin: 10px 0;
		}
		
		header, nav, .main, .sidebar {
			width: 95%;
			margin: 10px auto;
		}
	
		.sidebar {
			float: none;
		}
	
	
	}
	
	@media screen and (max-width: 400px) {
		
		body {
			background: #3a553d;
			margin: 0;
		}	
		
		.container {
			width: 100%;
			margin: 0;
		}
		
		header, nav, .main, .sidebar {
			width: 100%;
			margin: 0;
			-webkit-border-radius: 0;
			-moz-border-radius: 0;
			border-radius: 0;
			padding: 10px;
		}
		
		nav {
			padding: 10px;
		}
		
		
		header h1 {
			font-size: 16px;
		}
		
	}



Other Options: 

- @media screen and (min-width: 900px)

- @media screen and (-webkit-min-device-pixel-ratio: 2) // RETINA DISPLAYS

- @media screen and (orientation: portrait)

- @media screen and (orientation: landscape)


### Introduce Project 1






HW
---------------------------------------
Whew, what a day! Somehow, we made it through. Have a great weekend, everyone!


4. **jQuery Stuff**

	Finish the "Modifying HTML Elements" lesson [jQuery Track](http://www.codecademy.com/tracks/jquery) on codecademy, and post a screen shot of your completed lesson to the blog.


1. **Create a 1-page site using a CSS frameworks** (Do this next week, due to missing first day of class)

	Using one of the frameworks we talked about in class today ([Bootstrap](http://getbootstrap.com/), [Foundation](http://foundation.zurb.com/), [Pure](http://purecss.io/), or any other comparable framework you find online, create a web page that has at least 2 columns (preferably 3 or 4, or differing amounts throughout the page), and enough filler content to make it feel kind of like a real web page. Try playing around with adding classes to buttons or form elements. If it helps, you can use the demo file from today or one of your projects from 341 to get content.

1. **Create a responsive, interactive (jQuery) site**

	Using media queries and jQuery, create a simple one page site that looks good at many sizes and responds to user input. 



2. **Do CSS Diner**

	Do all the exercises at [CSS Diner](http://flukeout.github.io/) and post a screenshot of the final page to the blog. Don't worry; it's fun!
	

2. **Collect content for Project 1**

	Start to narrow your ideas down to exactly what you are going to be making your site about. Think about how your site can tell a story, what the major "plot points" will be, and how you can engage users through interaction to make the narrative more immersive and inclusive. Write a synopsis, collect some initial content/sketches/images, and describe at least a few forms of interaction that would make sense in the telling of your narrative.

		
3. **Post the your homework to WordPress**
	
	Just one last reminder that you should always post your HW to WordPress. If you want credit for your work, take the extra 30 seconds.




### Useful Links
- [Coda Plugins](https://panic.com/coda/plugins.php#Plugins)
- [Thom's Coda clips](http://teaching.thomhines.com/342/Thom's%20Clips.clips)