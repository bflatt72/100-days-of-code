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


### Day 8 Oct 3, 2017

Completed the FCC front end project, [Build a Tribute Page](https://www.freecodecamp.org/challenges/build-a-tribute-page). My solution can be seen on Codepen at [Dr Sheldon Cooper](https://codepen.io/bflatt72/pen/zEEoWB). 

I don't really like working with codepen. Seems to be a lot more hassle than it's worth and I just much prefer working in my own local environment that I can push to Github so that's what I will be doing for all future projects. Also, not really enjoying Bootstrap all that much. Again, I prefer rolling my own CSS but maybe that's because I need to learn Bootstrap better?

98% on first Intro to Programming and Logic exam. Consisted of computer history, binary conversions and short  Assembly language program. 

### Day 9 Oct 4, 2017

Did my first git revert because I bungled a git merge creating conflicts. Did not understand what was going on at the time. Wrote a blog post about it. 

Watched JavaScript Youtube videos by [The Net Ninja](https://www.youtube.com/watch?v=qoSksQ4s_hg&list=PL4cUxeGkcC9i9Ae2D9Ee1RvylH38dKuET)

Blog post at [Git revert](https://bflatt72.github.io/posts/2017/10/03/git-merge-conflicts.html)

### Day 10 Oct 5, 2017

Set up local HTML/CSS templating files so I don't have to reinvent the wheel every time I start a new project. 

Started FCC Portfolio project locally and on Github rather than Codepen. 

[Portfolio](https://bflatt72.github.io/projects/FCCportfolio)

### Day 11 Oct 6, 2017

Worked on FCC Portfolio project. Still local, git commit but not pushed to Github. 

### Day 12 Oct 7, 2017

Took a break from hard coding to review Bootstrap. I realized if I learned it better I might not hate it so much. Watched the Net Ninja's Bootstrap 3 and 4 playlists on Youtube and did the short Bootstrap exercises on FCC.

### Day 13, Oct 8, 2017

Reviewed Bootstrap and worked on FCC portfolio project starting over using Bootstrap 4. 

[Portfolio](https://bflatt72.github.io/projects/FCCportfolio) in current state. 

### Day 14, Oct 9, 2017

FCC Portfolio. Liking the looks of it so far. Need to finish out the footer and social links and the functionality of buttons and navigation. Javascript/Jquery? All text on site is copied from example site as placeholder text. Will personalize later. 

Tweeted last 3 days as day 12 each time. Stuck in a time loop? 

### Day 15, Oct 10, 2017

Caught up on this log file. Forked and cloned [personal-goals](https://github.com/bflatt72/personal-goals) repo and started using it. Going to add and upkeep goals and lists of resources. 

Learned about bash scripts and aliases via the above personal-goals repo from [una](https://github.com/una). Added my own alias for this 100DaysofCode repo:

100-log will open the log.md file in 100-days-of-code folder
100-gh automates git add, git commit and git push to the remote repo. Pretty awesome. 

testing testing testing and testing

let's test some more


### Day 16 Oct 11, 2017

Added some JavaScript to my CITC1301 webpage. 

1. Changed background textures of sections.
2. Revert back to original background textures.
3. Show social links
4. Buttons to change profile pic
5. Buttons to show and hide lists

Link to project: [CITC1301](https://bflatt72.github.io/projects/CITC1301)


### Day 17 Oct 12, 2017

Cleaned up my HTML and CSS files in my CITC1301 class project. 

Pretty much finished the FCC Portfolio project. Just need to clean up the code and see if I can find out how to add scroll animations to the page buttons. 

Link to project: [FCC Portfolio](https://bflatt72.github.io/projects/CITC1301)

### Day 18 Oct 13, 2017

Finished the FCC Portfolio project. Very proud of myself. Took about a week and a half of coding an hour or two a day. No cheating to look at FCC's code. All done myself reverse engineering the example site. 

Link to project: [FCC Portfolio](https://bflatt72.github.io/projects/CITCy1301)

### Day 19 Oct 14, 2017

Was visiting Zach in Raleigh so didn't have a whole lot of time to do any coding, however I did read the first chapter of You Don't know JS, Up and Running. 

### Day 20 Oct 15, 2017

Changed my Jekyll blog theme to Beautiful-Jekyll. Added my portofolio page to the blog. Added another button to the portfolio to direct back to the blog. The FlattDev logo also redirects back to the blog. 

[FlattDev](https://bflatt72.github.io)

### Day 21 Oct 16, 2017

Finished reading Up and Running book, You Don't Know JS. Had a look at the book I bought awhile ago, JavaScript for Web Developers. Worked on Jquery and JavaScript modules in Free Code Camp.

### Day 22 Oct 17, 2017

Worked on Basic JavaScript on FreeCodeCamp. Got my domain name up and running. Again. Wrote a blog about it. 

[FlattDev](http://flattdev.com)

### Day 23 Oct 18, 2017

Worked on Basic JavaScript on FreeCodeCamp. Contributed to the FreeCodeCamp guide on Bootstrap Grid System - pull request #3 for Hacktoberfest. 

### Day 24 Oct 19, 2017

Worked on Basic JavaScript on FreeCodeCamp. Wrote a blog entry from journal entitled Stream of Consciousness. Contributed to the FreeCodeCamp guide on HTML A tags -- pull request #4 for Hacktoberfest. Shirt!! 

### Day 25 Oct 20, 2017

Worked on Basic JavaScript on FreeCodeCamp. If/else and switch statements. 

### Day 26, Oct 21, 2017

Worked on Basic JavaScript in FreeCodeCamp. Objects. Got caught up on Statistics course work, Confidence Intervals.

### Day 27, Oct 22, 2017

Completed Scratch project for CITC1301

[Breakout](https://scratch.mit.edu/projects/174355603/#player)

### Day 28, Oct 23, 2017

Finished Basic JavaScript and Objects in FreeCodeCamp. Started on Basic Algorithm challenges, completing Reverse a String and Factorialize a Number.
Completed Stats lab Ch 6/7 and wrote blog for CITC week 8. 

### Day 29, Oct 24, 2017

Completed through truncateStr Basic Algorithms in FreeCodeCamp. Watched JavaScript Fundamentals by Traversy Media on Youtube. 

### Day 30, Oct 25, 2017

Day 30 of challenge. Completed the Basic Algorithms but did have to cheat a lot and look at code, although I did not copy and paste. I figured I can learn this way and later can reset code and try again on my own, once I have a better handle on things. 

### Day 31, Oct 26, 2017

Read Intro and Ch 1 of Eloquent Javascript. LOVE IT!!! Very good resource. 

### Day 32, Oct 27, 2017

Ch 2 Program Structure of Eloquent JavaScript and end of Ch exercises. Did first 2 on my own, had to Google help for last one. Loop triangle, FizzBuzz and Chessboard. FizzBuzz seems quite easy for me, especially the basic solution involving a For loop and if/else statements, not sure how this questions weeds out so many prospective web developers. Chessboard confused me a bit and I had to Google for solution. 

### Day 33, Oct 28, 2017

Ch 3 Functions Eloquent JavaScript -- Very proud of myself and quite amazed. Did all 3 end of Ch exercises on my own without any help or Googling. Minimum, Recursion and countChar.