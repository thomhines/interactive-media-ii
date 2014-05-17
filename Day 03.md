ART 342 - Day 3
=======================================

1. Positioning Presentation
2. Media Queries
3. Group Discussions about Project 1
4. Wireframes/Sketchboards



PREP
---------------------------------------
- Look up who did a good job on HW
- Load up sites
- Post responsive demo files [Responsive Demo Files (Empty)](http://teaching.thomhines.com/resources/responsive_template_empty.zip), [Responsive Demo Files (Complete)](http://teaching.thomhines.com/resources/responsive_template_complete.zip)
- Print out [Sketchboards](http://www.adaptivepath.com/uploads/archive/images/publications/essays/sketchboard/ap_multipage_sketchboard_template_example.pdf)


CLASS
---------------------------------------


### QUIZ
- What is a 'clip' in Coda?
- What are the steps necessary to make a CSS framework like 960.gs or bootstrap work?
- What is the difference between a fluid grid and a responsive grid?
- Pick 2 more students to show off their sites


- Who used something other than bootstrap/960/pure?

**MAKE SURE TO POST THUMBNAILS WITH EACH POST!**






### Positioning Presentation

Great place to look at layout info: [learnlayout.com](http://learnlayout.com/)


Load Layout Demo Files [(Empty)](http://teaching.thomhines.com/resources/positioning_template_empty.zip) [(Complete)](http://teaching.thomhines.com/resources/positioning_template_complete.zip)


- Make columns border-box so you can adjust paddings on each column without breaking layout

- Add <span class="dropcap"> to first letter in .main paragraph to demo spans

- Clearfix to make floats work out properly

- Make top-right badge appear in main column, not top right of page





### Media Queries Presentation

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





### Break


### To prepare for group discussions, answer these questions in a blog post:
- What is the primary objective of your site? Do you have other goals?
- Who is your audience?
- What is the overall tone that you want to convey?
- What is the main form of interaction you want to explore? (How can you express your subject/tone through click-and-drag? scrolling? click-and-hold? hovering? hiding/revealing?)
- How can the user express him/herself within a site about your subject?
- Is there a particular environment/context that your site would be best in?


### Split into groups and talk about ideas for projects. 

Go around to each group and try to hear what students are doing.





### Wireframes/Sketchboards

Start with [Sketchboards](http://www.adaptivepath.com/ideas/sketchboards-discover-better-faster-ux-solutions).

- Multi-page boards for divergent sketching. ([Example](http://www.adaptivepath.com/uploads/archive/images/publications/essays/sketchboard/ap_multipage_sketchboard_template_example.pdf))

- Single-page boards for exploring one idea more deeply. ([Example](http://www.adaptivepath.com/uploads/archive/images/publications/essays/sketchboard/ap_singlepage_sketchboard_template_example.pdf))


- Next, higher fidelity wireframes
	[Design Better, Faster with Rapid Prototyping](http://www.smashingmagazine.com/2010/06/16/design-better-faster-with-rapid-prototyping/)


- Tools
	- [Wireframe.cc](http://wireframe.cc)
	- [Balsamiq](http://www.balsamiq.com/)
	- [http://keynotopia.com/](Keynotopia)
	- [Keynote Kung Fu](http://keynotekungfu.com/)
	- Pen and Paper 
		
- [Examples](http://speckyboy.com/2011/05/29/20-effective-examples-of-web-and-mobile-wireframe-sketches/)


**Lets take 30 minutes to start sketching this stuff.** 





HW
---------------------------------------
Nice work today, everyone! That was a long demo, but I'm glad you guys were good sports about it. If you didn't get it fully working, or if you just want to be able to look at the completed version for reference, I've included that version as well to the Resources page. Have a great evening and I'll see you Thursday!

1. **Wireframes**
	
	I would like to see at least three distinct directions of wireframes, with at least three major pages or page states per direction. These should be detailed enough and annotated to allow for someone like me to be able to be able to understand them without you having to sit there and explain them. Post them to the blog. (And if you want some good suggestions on how to make good wireframes, take special note of the suggestions presented [here](http://speckyboy.com/2011/05/29/20-effective-examples-of-web-and-mobile-wireframe-sketches/))

2. **Website Research and Analysis**

	Find one website whose ***interactions*** you like and one you don't, and write five reasons for each site on why you think they are either good or bad. Post these writings—along with screenshots illustrating your points and links to the sites—to the blog.
	