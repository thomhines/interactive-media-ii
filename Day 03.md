Day 3
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
- What is the tool we use in order to make a web page's style respond to different size screens?
	- Look at Farrah's site to show how you can change the background to mark different breakpoints
- How do we absolutely position one element inside of another?
- What CSS properties do we adjust the position of an absolutely positioned element in our CSS? 
	- Relatively positioned?
- How does every jQuery statement start?
- What goes in the parentheses after the '$'?
- What function do we use to hide an element on the page? (hide, fadeout, slideup)
- How can we move it to another spot in the page? (append, prepend, after, before)
- How can we affect the content of an element? (.html())
- How can we affect the styles? (.css, .height, .width)
- How can we read the value of an input?
- And lastly, how can we make it so that every time we click on an element, the last element we clicked on disappears?



**MAKE SURE TO POST THUMBNAILS WITH EACH POST!**


### jQuery plugin round-up???
- [impress.js](http://bartaz.github.io/impress.js/#/bored)
- [skrollr](http://prinzhorn.github.io/skrollr/)
- [waypoints](http://imakewebthings.com/waypoints/)
- [stellar](http://markdalgleish.com/projects/stellar.js/)
- [scrollto](http://demos.flesler.com/jquery/scrollTo/)
- [vide](http://vodkabears.github.io/vide/)
- [texttailor](http://jpntex.com/texttailor/)
- masonry





### Paralax Workshop
based on [tutsplus article](http://webdesign.tutsplus.com/tutorials/complete-websites/create-a-parallax-scrolling-website-using-stellar-js/)


- Show off [completed Parallax demo site](http://web.pdx.edu/~thines/342/parallax_complete)
- Download [non-completed Parallax demo site](http://teaching.thomhines.com/resources/parallax_empty.zip)

- Describe jQuery plugins
	- Stellar
	- scrollTo
	- waypoint
	- jQuery UI

#### Parallax 

- $(window).stellar();
	- Link to JS
	- Add `$(window).stellar()` to scripts.js
- HTML
		
		<div class="item item1" data-stellar-ratio=".6">ITEM</div>
		<div class="item item2" data-stellar-ratio=".8">ITEM</div>
		<div class="item item3" data-stellar-ratio="1.2">ITEM</div>
		<div class="item item4" data-stellar-ratio="1.4">ITEM</div>
		<div class="item item5" data-stellar-ratio="1.6">ITEM</div>	
	
#### ScrollTo
- $(window).scrollTo();
	- Link to JS
	- Add:

			$('.page2_link').click(function() {
				$(window).scrollTo('#page2', 800);
			});

#### Waypoint
- $('#page2').waypoint
	- Link to JS
	- Add: 
	
			$('#page2').waypoint(function (direction) {
				$('nav a').removeClass('selected');
				$('.page2_link').addClass('selected');
			});

	- Hide box on page2 and show it via waypoint:

			$('.fadeIn').hide();
			
			waypoint(function() {
				$('.fadeIn').fadeIn();
			}

	- Add `direction == 'down'` and `else`, so that code looks like this

			
			$('#page2').waypoint(function (direction) {
				$('nav a').removeClass('selected');
				if (direction === 'down') {
					$('.page2_link').addClass('selected');
					$('.fadeIn').fadeIn();
				} else {
					$('.page1_link').addClass('selected');
				}
			});
		
	- If scrollto isn't lining up, add offset:
	
			$(window).scrollTo('#page2', 800, {offset: 3});
			
			
			

<!--
#### jQuery UI for nav animations (optional) 
- Add jQuery UI
- update addClass, removeClass
	$('nav a').removeClass('selected', 200);


-->


### Break


### To prepare for group discussions, answer these questions in a blog post:
- What is the primary objective of your site? Do you have other goals?
- Who is your audience?
- What is the overall tone that you want to convey?
- What is the main form of interaction you want to explore? (How can you express your subject/tone through click-and-drag? scrolling? click-and-hold? hovering? hiding/revealing? typing?)
- How can the user express him/herself within a site about your subject?
- Is there a particular environment/context that your site would be best in?


### Split into groups and talk about ideas for projects. 

Go around to each group and try to hear what students are doing.





### Wireframes/Sketchboards

- [A Beginner’s Guide to Wireframing](http://webdesign.tutsplus.com/articles/a-beginners-guide-to-wireframing--webdesign-7399)

- [Wireframe Examples on Pinterest](https://www.pinterest.com/wireframes/great-wireframe-examples/)


Start with [Sketchboards](http://www.adaptivepath.com/ideas/sketchboards-discover-better-faster-ux-solutions).

- Multi-page boards for divergent sketching. ([Example](http://www.adaptivepath.com/uploads/archive/images/publications/essays/sketchboard/ap_multipage_sketchboard_template_example.pdf))

- Single-page boards for exploring one idea more deeply. ([Example](http://www.adaptivepath.com/uploads/archive/images/publications/essays/sketchboard/ap_singlepage_sketchboard_template_example.pdf))


- Tools
	- [Wireframe.cc](http://wireframe.cc)
	- [Balsamiq](http://www.balsamiq.com/)
	- [http://keynotopia.com/](Keynotopia)
	- [Keynote Kung Fu](http://keynotekungfu.com/)
	- Pen and Paper 
	- [UI Tiles](http://pixelbuddha.net/freebie/ui-tiles-website-flowcharts)
		


**Lets take 30 minutes to start sketching this stuff.** 





HW
---------------------------------------
Nice work today, everyone! You guys seem to be getting this stuff pretty easily. If you didn't get the demo fully working, or if you just want to be able to look at the completed version for reference, I've included that version as well on the Resources page. Have a great evening and I'll see you Wednesday!


1. **Add one more plugin**

	Take the site we made today in class and add one more plugin to enhance/alter the interaction of the page. It doesn't have to make sense, but at least try to get it to work.


2. **Website Research and Analysis**

	Find one website whose ***interactions*** you like and one you don't, and write five reasons for each site on why you think they are either good or bad. Try to find a site with non-standard inputs that go beyond just pointing and clicking or scrolling in a conventional way. Post these writings—along with screenshots illustrating your points and links to the sites—to the blog.


3. **Wireframes**
	
	I would like to see at least three distinct directions of wireframes, with at least five types of interactions per direction. How can you express your narrative's subject/tone through click-and-drag? scrolling? click-and-hold? hovering? hiding/revealing? typing? You don't have to use them all, but brainstorm as many *relevant* ideas as you can. Post them to the blog. 


4. **Mood Boards**
	
	I want to see at least 20 pieces of inspiration that you want to use as a jumping off point for your narrative site. These can be typography, color palettes, other sites, nice interactions, styles, images, text, whatever. Of course, post these to the blog.



### Useful Links
- [Unheap](http://www.unheap.com/) - Super great jQuery plugins repository
- [A Beginner’s Guide to Wireframing](http://webdesign.tutsplus.com/articles/a-beginners-guide-to-wireframing--webdesign-7399)
- [Wireframe Examples on Pinterest](https://www.pinterest.com/wireframes/great-wireframe-examples/)
	