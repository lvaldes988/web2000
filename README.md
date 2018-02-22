# WEB2000

# Homework

You will need to complete the following workshops and upload the finished version to FVI-grad.com. In all cases, you **must alter the design of the page to include your name, as well as a custom color scheme**. I suggest checking lolcolors.com for some ideas on color palettes.

DOM scripting by example: https://teamtreehouse.com/library/dom-scripting-by-example  

Object Oriented JavaScript:  
https://teamtreehouse.com/library/objectoriented-javascript

Canvas Clock tutorial:
https://www.w3schools.com/graphics/canvas_clock.asp  

# Grading

10% Attendance  
20% Homework  
30% completion of in class activities  
40% tests (20% each)  


## Day 1

Html emails. The purpose of this class is for students to understand the challenges in creating html code which is compatible with all email clients. Students will create an email-friendly html resume.  

We go through the contents of the following articles:  
http://webdesign.tutsplus.com/tutorials/what-you-should-know-about-html-email--webdesign-12908  
http://webdesign.tutsplus.com/articles/build-an-html-email-template-from-scratch--webdesign-12770  

Students will start by designing a wireframe of the html email resume they want to create, or picking a template from [this site](http://www.noupe.com/essentials/freebies-tools-templates/25-free-html-resume-templates-for-your-successful-online-job-application-82756.html). Their project will be to create an html version of this wireframe with a resume.  

We clarify that external files and fonts cannot be used in emails. Use W3 to go over web safe fonts.   http://www.tutorialspoint.com/html/html_fonts_ref.htm

Inline styles are imperative for emails so students will be shown how to use the mailchimp or inkd css inliners.  

## Day 2

Write a resume auto-emailer portal. It's supposed to post to this node endpoint. Students will create a nice form with the required fields (from, html_file_name, dest_email, subject) and post it to the route at http://fvi-grad.com:4004/resume-emailer
 
A finished resume from the previous day is required. The student will give his file to the instructor and the instructor will upload it to the server in the correct folder so that the node route picks it up.
 
Students must upload their resume emailers to their fvi-grad.com shared web space.
Sample finished resume with inline styles: http://catmiller.fvi-grad.com/Web-Resume/cathy.html
Sample resume emailing form: http://catmiller.fvi-grad.com/Web-Resume/emailForm.html (students should be encouraged to make it nicer looking)

The resume endpoint requires the following fields to be posted via req.body:
from: name of sender (Doesn't really matter, it doesn't come out in the final email),  
html_file_name: the absolute path and file name of the file. Eg /home/students/csierra/htmlemail.html  
dest_email: who you are sending it to  
subject: The email subject you want the receiver to see  

The last two should be visible form inputs, the others should be hidden. 

## Day 3

Finish resume emailer.

## Day 4 

Introduction to video and audio elements. We went through the first 3 parts of the treehouse class and made the two pages in this repo: https://github.com/Swolebrain/html5-video-and-audio-demo

## Day 5

The objective of this day is for students to understand the principles of html performance optimization. After this class, students will have learned and applied asynchronous loading of scripts, conditional resources dependent on media, optimization of images, and minification of resources. Students will be assigned a project where they will implement a simple board game. We use the Udacity course: https://www.udacity.com/course/website-performance-optimization--ud884

We need to leave students with specific resources such as how to bundle and minify CSS files using npm packages and how to bundle and minify JS files, also using npm scripts and packages (eg. webpack).

## Day 6

Quick formative assessment on html emails, video/audio elements, and website performance optimization. Then we start with a guided tutorial building a Pong game on plain canvas: https://github.com/Swolebrain/Pong

## Day 7

Finish pong game, websockets tutorial (chat).

## Days 8-11

Flappy bird. First two days are spent on following along based on [this codebase](https://github.com/Swolebrain/flappy-bird), and the third day is spent on adding student-defined features, refactoring, browserifying, deploying.

You can use this video for reference for students who miss class: https://www.youtube.com/watch?v=g1aIu2wi7Po


## Day 12
Final Exam
