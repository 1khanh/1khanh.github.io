---
layout: essay
type: essay
title: "Bootstrap 5 made me cry"
# All dates must be YYYY-MM-DD format!
date: 2022-10-06
published: true
labels:
  - UI Frameworks
---

## Bootstrap Bootcamp
At this point in ICS314, I have come to learn that everything we are learning is really difficult since it is very new to me but in return, it is also very helpful when it comes to coding. Bootstrap 5 especially has been very difficult because I had a hard time differentiating between normal HTML/CSS and incorporating Bootstrap 5. As reflected in my other assignments this past week with IslandSnow and the recreation of a Spotify Album as my chosen website, I did not complete it with much success as I underestimated the learning curve that came with Bootstrap 5 and I heavily relied more on raw HTML and CSS to design the websites.

## Difference Between My .css Files
For example, here is the style.css file from the Spotify Album Recreation.
```
body {
  margin: 0px;
  width: 100%;
}

.fixed {
  position: fixed;
  top: 0;
  z-index: 2;
}

/* The sidebar menu */
.sidenav {
  height: 100%; /* Full-height: remove this if you want "auto" height */
  width: 227px; /* Set the width of the sidebar */
  position: fixed; /* Fixed Sidebar (stay in place on scroll) */
  z-index: 2; /* Stay on top */
  top: 0; /* Stay at the top */
  left: 0;
  background-color: #111; /* Black */
  overflow-x: hidden; /* Disable horizontal scroll */
  padding-top: 11px;
  padding-left: 15px;
  font-family: 'Circular std';
  font-weight: bold;
}

/* The navigation menu links */
.sidenav a {
  padding: 6px 8px 6px 16px;
  text-decoration: none;
  font-size: 14px;
  color: #818181;
  display: block;
}

/* When you mouse over the navigation links, change their color */
.sidenav a:hover {
  color: #f1f1f1;
}

/* Style page content */
.main {
  margin-left: 160px; /* Same as the width of the sidebar */
  padding: 0px 10px;
}

@media screen and (max-height: 450px) {
  .sidenav {padding-top: 15px;}
  .sidenav a {font-size: 18px;}
}

i1 {
  font-size: 25px;
}

i {
  font-size: 23px;
}

.footer {
  position: fixed;
  left: 0;
  bottom: 0;
  width: 100%;
  background-image: url("footer-img.PNG");
  color: white;
  z-index: 3;
  /*position: bottom;*/
  word-wrap: normal;
}

button {
  font-family: "Circular std";
  font-size: 15px;
  color: black;
  letter-spacing: .5px;
  line-height: 15px;
  border: 2px solid white;
  border-radius: 40px;
  background: white;
  transition: all 0.3s ease 0s;
  padding: 15px 30px 25px 30px;
  position: absolute;
  right: 1.5%;
  top: 17%;
  bottom: 20%;
}

button1, a1 {
  font-family: "Circular std";
  font-size: 15px;
  color: black;
  /*letter-spacing: .5px;*/
  /*line-height: 15px;*/
  /*border: 2px solid white;*/
  /*border-radius: 40px;*/
  /*background: white;*/
  /*transition: all 0.3s ease 0s;*/
  /*padding: 10px 10px 10px 10px;*/
  /*position: absolute;*/
  /*right: 1.5%;*/
  /*top: 0%;*/
  /*bottom: 1px;*/
  z-index: 100;
}
/*.topbar {*/
/*  background-color: rgba(84,36,62,255);*/
/*  z-index: 1;*/
/*  height: 65px;*/
/*  color: white;*/
/*}*/

.round-button {
  border-radius: 50%;
  border-color: black;
  z-index: 3;
}

main {
  background-image: url("whatif.PNG");
}
```
This is just way too much compared to my style.css for this week's timed WOD that we did in class shown below.
```
#topMenu {
  background-color: #017574;
  color: white;
  padding-bottom: 10px;
}

li.nav-item.nav-link {
  color: white;
}

#footerMenu {
  background-color: #017574;
  color: white;
  padding-bottom: 10px;
}

#newID {
  background-color: #8E8579;
  color: white;
}
```

## I Love Bootstrap
As you can see, there is such a vast difference between the two that shows using Bootstrap 5 to format and style the HTML code is a valuable resource to use. Literally, it turned over 100 lines of code to around 20 lines. I would say the return for investment on using Bootstrap for me is not worth it as it led to a lot of frustration but as I get more familiar with it, I would say that it wouldn't even be a question on if it was worth it or not. Overall, I would like to get better at Bootstrap 5 just because of learning more about frontend development and seeing how many cool websites and designs that can be created.
