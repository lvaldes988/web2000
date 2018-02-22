1. How do we measure the length of the critical rendering path? (10 pts)  
    2. The number of actions the browser must take (eg run js, build cssom, build dom, etc) in order to fully load and render your page  
    
2. What are the events in the Timeline pane which show the DOM being built, the CSSOM being built, and the render tree being built? (10 pts)  
    1. Parse HTML, Parse CSS, Layout  
    

3. What is the render tree? (10 pts)
    1. is the union of the cssom and the dom combined


4. What are three things you can do in order to speed up a website's load time? (10 pts)  
    1.loaad javascript at the en d of the body
    2.load javascript as async if posible
    3.inline css styling
    4.use comprassion for your images
    5.minify your js and css or use a bundler(webpack,browsify)

5. What is the name of the Google tool you can use to see a list of things you can do to improve your page's load speed? (10 pts)  
    yu can test your website speed with think with google 
    pagespeed insight
    
6. What is the purpose of including multiple `<source>` elements within a single `<video>` element?
    so you can modify each video individually without afecting the others


7. Use webpack to bundle all the files in the following project: https://github.com/Swolebrain/connect4  
  Setup Steps:
    1. Fork the project by going to the above link and clicking "Fork" near the top right of the screen
    2. The project will now have a copy in your own github page. Clone it from there.
    3. In your computer, initialize this folder as a node project.
    4. Install webpack, webpack dev server, and make sure they are saved as development dependencies in package.json
    5. Split out the code from the createTable function and the isLegitEdge function into separate files. **Make sure each function has its own file.**
    6. Back in your main file, require/import the contents of your two new files
    7. Create an npm script to use webpack to fire the dev server and create a javascript bundle (one single file containing all your JS).
    8. Do anything else you need to do in order to get the bundle working and test your site.
    9. Before submitting, ensure your code is bundled into one file.
    10. Commit and push to github
    11. Upload the game to yourname.fvi-grad.com

8. Bonus points: Produce a minified bundle for the exercise above using an uglify plugin.
