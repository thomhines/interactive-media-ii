Day 16
=======================================

1. Discuss Product Websites Ideas
3. Group Discussions about Project 2


PREP
---------------------------------------



CLASS
---------------------------------------

### CSS Animations and Animated SVGs

#### CSS Animations
- [CSS Tricks](https://css-tricks.com/almanac/properties/a/animation/)

First, move the whole SVG around using CSS Animations

	svg {
		-webkit-animation: zoomit 3s alternate infinite;
	}
	
	
	
	@-webkit-keyframes zoomit {
	    0% { 
		    background: #faa;
		    margin: 0;
		    
		    width: 200px;
		    height: 200px;
		}
		25% {
			margin: 200px;
		}
	    100% { 
			background: #ffa;
			margin: 100px;
			width: 400px;
			height: 400px;
		}
	}



#### SVG Animations
- [Jenkov](http://tutorials.jenkov.com/svg/svg-animation.html)
- [CSS Tricks](https://css-tricks.com/guide-svg-animations-smil/)

Next, move individual parts by adding closing tags to SVG elements and then adding <animate> and <animateTransform> tags




### Google Analytics & SEO

Setting up Google Analytics

SEO
- Well structured HTML
- Clear titles
- Keywords in titles
- Human Readable URLs
- Basically make everything good enough that you could hand it to a person to read and understand quickly


### Setting Up Hosting

- Why do you need it?
	- Portfolio
	- Product site
	- blog
	- combo

- Where to go
	- CMS
		- Squarespace
		- Virb
		- Cargo
	
	- Types of hosting plans
		- shared
		- dedicated
		- cloud
			- Rackspace
			- Amazon Web Services
	- Top hosting plans 
		- [Lifehackers picks](http://lifehacker.com/5911651/five-best-web-hosting-companies)
		- [NearlyFreeSpeech](https://www.nearlyfreespeech.net/)
		- [Site5](http://site5.com)
		
- What to look for
	- PHP (preferably support for ver. 5.3 or better)
	- MySQL
	- Bandwidth
	- Space
	- Domains
	- Server load
	- Price
	- Extras? 1-click installs, python, ruby on rails, SSH

- Signing Up

- [cPanel](http://backstage.site5.com/) (I use [Site5](http://www.site5.com/))
	- Email Accounts
	- FTP Accounts
	- MySQL Databases
	- Addon Domains
	- Subdomains




	

### Work Session


HW
---------------------------------------

1. **Finish Designs**

	Finish the designs for *all* of your pages. Don't start coding your site until you've collected all of your content and designed every detail. Yes, you may change your mind later in the process, but the more you decide in Photoshop/Illustrator, the easier it will be to make your site work the first time. Similarly, if you don't have your layout or interactions nailed down yet, you might consider doing another round of wireframes, too! Whatever you do, post it to the blog and beef up your process grade.

	
2. **Annotated Comps**

	You can either do this on your computer or by printing out your comps and scanning them in (my preferred way, since it is faster), and post them to the blog. Remember, you want to mark up these three things:
	
	- Details such as font, font size, colors, margins, paddings, etc. 
	
	- Define related sections of your site. For instance, group your header info together, and if your main content area has a box inside of it with three text elements and two images, put a div around it to keep them all together.
	
	- Start to label what elements/classes you will use for each section and element (eg. "h1", "header", ".sidebar"). The more you do now, the easier it will be to start coding.

	
3. **Code**

	This isn't required for next class, but if you have a solid and complete design and a bit of extra time, feel free to start making your HTML/CSS. If you want, you can use the HTML template I posted to the Resources page on the blog to get you started.



### Useful Links
- Google Guide to better search results
- Plugins for SEO