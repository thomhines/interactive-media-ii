ART 342 - Day 6
=======================================

1. jQuery functions lesson
2. Programming Basics presentation
4. Annotated Comps
5. Work Session


PREP
---------------------------------------
- Create HTML/JS/JQUERY combo for demonstrating JS
- Load up http://www.codecademy.com/tracks/javascript
- Post Objectives Questionnaire to blog


CLASS
---------------------------------------
### Quiz

- What was one of the design considerations we have to make when it comes to mobile design? What do we have to change from the desktop version to optimize a site for mobile? (Design for smaller screens, simplify navigation, prioritize content, minimize user input, design for intermittent connectivity)

- What are some of the things that jQuery plugins can do?
	- What are your favorites?
- How do we use them?




### Lesson on more jQuery functions

[CodePen](http://codepen.io/thomhines/pen/BJytq)

Add this to JS:

#### addClass()

	$('li').click(function() {
		$(this).addClass('selected');
	});

- .addClass, .removeClass, .toggleClass
	- Change style with class
	- Create click triggers for items with new class name to show new functionality

#### hover()

	$('.hoverbox').hover(function() {
		$(this).html('OVER!');
	}, function() {
		$(this).html('OUT!');
	});

#### animate()
On .animatebox:

- .css

		$(".animatebox").css('width', '70px');

- .animate

		$(".animatebox").animate({
	    	width: "70%",
			opacity: 0.4,
			fontSize: '50px',
			marginLeft: '100px'
		}, 1500 );

### val()
 
	$('.submit').click(function() {
		alert("Hello, " + $('.name').val() + "!");
	});


### Programming Basics Presentation
From Keynote file


### - BREAK -



	
	
### Annotated Comps
Demonstrate the value of annotating comps and what to note: 

1. First: fonts, sizes, margins, padding, colors, etc.
2. Second: Pick which items are which tags
3. Last: Layout possible divs and sections with names (.sidebar, .meta-info, etc.)


### Work Session





HW
---------------------------------------
Probably just one or two more hardcore demos for the rest of the term! Otherwise, we'll be spending time designing, refining, and learning little things here and there. You guys are doing great! Have a wonderful weekend, and I'll see you all next week!

1. **Annotated Comps**

	If you didn't make one or finish yours, make or finish your annotated comp. Then either take a screen shot or a photo of it, and post it to the blog.


2. **HTML & CSS**

	It may seem daunting, but try to have *all* of your HTML done by next class. Sure, you may need to add illustrations or text, but for now, put in placeholder content and get the basic structure of your site complete. After that, get going on your CSS and do your best to get as much done by next week as you can. DON'T start on your javascript until you've got your HTML and CSS done. Start off with the easy stuff and work you're way up from there. Trust me, it'll make your life a lot easier.


3. **ExTrA CrEdiT!!!**
	
	Go through the [Code(A)cademy Javascript](http://www.codecademy.com/tracks/javascript) "Introduction to Javascript" track (ie. "Getting Started with Programming" and "Project: Choose Your Own Adventure!" exercises). In order to get credit, post a screen shot of your completed tasks (like I demonstrated in the attached photo) to the blog! This isn't required, but trust me, it's worth the time. You have until class one week from today to finish this for credit, but you can do it anytime for the priceless benefits of learning and growing.