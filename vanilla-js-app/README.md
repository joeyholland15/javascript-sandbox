This directory contains the base files for a very simple JavaScript application. The main files are:
* index.html (for writing HTML to create the bones of our application)
* app.css (for writing CSS to add styles to our application)
* script.js (for writing JavaScript to bring our application to life!)

If you are using VSCode, you should install the Live Server plugin.

![Screen Shot 2022-05-27 at 8 54 10 AM](https://user-images.githubusercontent.com/14914291/170735630-ec222add-3cc8-49fb-92be-f9f08fa91f8c.png)

Once installed, this plugin will allow us to run our app directly in the browser. To do this, run `command + shift + P` and select `Live Server: Open with Live Server`. You should see the app boot up in your browser. Any changes you make in your files will immediately show in your browser since Live Server has live reloading. Your sandbox is now set up, happy hacking!

# Step 1 - Create a button

Let's start by using HTML and CSS to create a simple button. It should look something like this:

![Screen Shot 2022-05-27 at 9 07 37 AM](https://user-images.githubusercontent.com/14914291/170737328-13bf6070-f9f5-4a32-bc06-bf45eafc2577.png)

# Step 2 - Add click handling

Let's now add a click handler to the button so that when clicked, it prints a random number in the console.

Hints: When we say "print", we mean use `console.log`. And random numbers can be generated using `Math.random()`. 
