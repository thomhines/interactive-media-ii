ART 342 - Day 7
=======================================

1. Parallax Demo
4. Work Session

PREP
---------------------------------------
- Load up links

- Link to Parallax Example Site files on blog

- [Non-Completed Parallax Demo Files](http://teaching.thomhines.com/resources/parallax_empty.zip)
- [Completed Parallax Demo Files](http://teaching.thomhines.com/resources/parallax_complete.zip)



CLASS
---------------------------------------





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


### Work Session



HW
---------------------------------------
1. **Refine Design**
	
	Take care of any last minute changes you have to make. Really, you should be done with this, but I know how designers are, so just do what you can to wrap things up. THERE SHOULD BE NO SIGNIFICANT CHANGES. Take a deep breath, hit Save, and move on.

2. **Finish HTML and Basic CSS**
	
	All of your HTML should be done, and enough CSS that your site looks recognizable. If there are some things that are broken or some obscure styles that aren't in place, no biggie, but you want to be as close to done as you can be. Upload your work-in-progress site and post a link to the blog.

2. **Begin Working With Javascript**
	
	Don't wait for next class to get started playing with your interactions. Set up your .js file, load up jQuery, and try getting the hang of all the plugins you might want to use. No doubt people will run into problems so better to run into them sooner rather than later!