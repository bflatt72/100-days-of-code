# 100 Days Of Code - Log

### Day 0: Sept 24, 2017 

**Today's Progress**: This is actually around 2 weeks in to my coding journey, after putting it aside for awhile a couple years ago, however I'm starting the 100 days of code as of today. I'm currently working through Shay Howe's [Learn to Code HTML and CSS](https://learn.shayhowe.com/html-css/) and while it is a tutorial I am actually building the website by hand along with the tutorial and pushing it to Github where it can be seen in it's current form at the link below. 

Things learned up to this point: 
1. Ubuntu Linux and the command line
2. Git and Github
3. Github pages
4. Sublime Text

I started working through [FreeCodeCamp](https://www.freecodecamp.org/bflatt72)a couple years ago and got pretty far into Javascript before I hit a brick wall. I am determined to soldier on and to teach myself Web Development along with my programming classes at a local community college. 

**Thoughts:** I REALLY like Shay Howe's Learn to Code HTML and CSS and am enjoying building out the Styles Conference website along with the tutorial. When I get done with it, I plan to branch it and re factor the website using Flexbox and another one with CSS grids and then again with Bootstrap. 

**Link to work:**  [Styles Conference](https://bflatt72.github.io/projects/shayhowe/)

### Day 1: September 25, 2017

**Today's Progress**: Last night I finished up Shay Howe's Learn HTML/CSS tutorial- Beginner. It took me a total of about a week working through it and building out the site as I went. I did it all by hand and did not use copy and paste except for large paragraphs and color codes. The website he has you build is very detailed which is good but I did not add every single speaker as there were over a dozen. I only added a few speakers and the entire schedule. 

This evening, after learning a little about Flexbox I decided I'd take the website I built with Shay Howe and change some of the layout to flexbox instead of inline-block and commenting out the spaces and using floats. I didn't do this to the entire site but I did it to the teaser section of main page and to the register page. Pretty cool. I did this after creating another branch called flex-box and I pushed that up to Github so that I now have two branches there, the master branch which is the original site built with Shay and the edited site I used Flexbox on. After learning some more Flexbox and then CSS Grid layouts I may edit it again using a Grid layout. 

Watched Flexbox youtube tutorial vids by The Net Ninja and then re worked the links in the nav and footer on the Shay Howe website from before. Pushed it up to flex-box branch on Github. 

**Link(s) to work**: [Styles Conference](https://bflatt72.github.io/projects/shayhowe/) this is the github page for the master branch. 

You can look at the code as follows:

1. [master branch](https://github.com/bflatt72/projects/tree/master/shayhowe)
2. [Flexbox branch](https://github.com/bflatt72/projects/tree/flex-box/shayhowe)

Over the last couple days I've also been working on teaching myself keyboard shortcuts for Sublime text editor and I installed some packages. 


### Day 2: Sept 27, Wednesday

Watched a really great conference talk by Morten Rand-Hendriksen entitled [CSS Grid Changes Everything](https://www.youtube.com/watch?v=txZq7Laz7_4)

Via that talk I was introduced to a few other resources for learning CSS Grid layouts: 

1. [Grid by Example - by Rachel Andrew](https://gridbyexample.com) - The definitive guide according to Morten
2. [MDN CSS Grid Layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout)
3. [CSS Tricks A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

Again, the Youtube videos by The Net Ninja are really great too and he just started one on CSS Grid. I think he just finished the 4th video. 

I then wrote a blog entry on my personal Jekyll blog on Github Pages entitled [Learning CSS Flexbox and Progress Update](https://bflatt72.github.io/posts/2017/09/26/Learning-CSS-Flexbox.html). I noticed that my tags don't work and I found an article about how to fix that in my Jekyll _layout folder and by creating a _plugins folder but I could not get it to work. I used the exact same code [Charlie Park](http://charliepark.org/tags-in-jekyll/) used but it just will not work. The tags are there on my posts but they don't do anything. 

I then started the video tutorials on Flexbox by Wes Bos [What the Flexbox](https://flexbox.io) which was really cool because even though the first 13 vidoes were review, he then went into setting up Gulp for automating the task of autoprefixing vendor prefixes which I'm not even sure still needs to be done for Flexbox but I figured it was a good way to get started learning Gulp, which is something I had heard about before. I had to install node and then Gulp both globally and locally and then install gulp autoprefixer. Pretty cool how that works. 

Gonna call it a night, but starting tomorrow I will be starting the code alongs with Wes and then I'm gonna start the front end development projects on FreeCodeCamp and redo a Google home page project I did a couple years ago for the Odin Project and then it's on to Javascript. 



### Day 3 Sept 28, 2017 My Birthday Thursday

Worked on 3 code along modules of Wes Bos's What the Flexbox. Pretty cool stuff. 

I then began work on my own personal webpage and I did some stuff but damn if I still don't feel as if I'm just hacking shit together instead of fully understanding what I'm doing. I used Shay Howe's site I built there as a guide and kind of a template but I made it my own. Will continue to work on it. 

**Link to Work: [Flatt Dev](https://bflatt72.github.io/projects/personal-webpage/)


### Day 4 Sept 29, 2017 Day after my Birthday

Worked on my website filling out inner pages with funny placeholder text. 

**Link to Work: [Flatt Dev](https://bflatt72.github.io/projects/personal-webpage/)

### Day 5 Sept 30, 2017 2 days after my Birthday

Refactored my Google home page from the Odin Project using Flexbox. 

**Link to Work: [Google Home Page](bflatt72.github.io/projects/google-homepage)

### Day 6 Oct 1, 2017 

Played around with normalize.css switching it out in a couple of my projects for the Meyer reset. Was wondering why Shay Howe's website he has you build has an entire section of CSS Styling typography to include all headers and then realized it's because the Meyer reset he used wipes all the styling away to zero. Seems silly to do all of that. Learned about normalize.css and how it doesn't do a full reset of all HTML elements but mainly just fixes bugs and ensures cross browser uniformity. Put it in the Shay Howe website and it put a border around the form on the register page and around the google map. Easy enough to remove. On my personal webpage I didn't notice any changes with normalize. On the Google home page clone project it did push my nav up to the top corner, guessing because it sets all margins to zero. Easy enough to fix. I also like the fact that normalize is fully documented in code. 

**Link to Work: Same as above just with normalize and took typology section out of Shay Howe since not needed. 

### Day 7 Oct 2, 2017

Made website for CITC1301 class using HTML/CSS. Had to talk about our hobbies and interests and the page had to include several photos, links and at least one ul or ol list.

**Link to work: [CITC1301](https://bflatt72.github.io/projects/CITC1301)
Code at [CITC1301](https://github.com/bflatt72/projects/tree/master/CITC1301)
