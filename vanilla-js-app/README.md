This directory contains the base files for a very simple JavaScript application. The main files are:
* index.html (for writing HTML to create the bones of our application)
* app.css (for writing CSS to add styles to our application)
* script.js (for writing JavaScript to bring our application to life!)

If you are using VSCode, you should install the Live Server plugin.

![Screen Shot 2022-05-27 at 8 54 10 AM](https://user-images.githubusercontent.com/14914291/170735630-ec222add-3cc8-49fb-92be-f9f08fa91f8c.png)

Once installed, this plugin will allow us to run our app directly in the browser. To do this, run `command + shift + P` and select `Live Server: Open with Live Server`. You should see the app boot up in your browser. Any changes you make in your files will immediately show in your browser since Live Server has live reloading.

Your sandbox is now set up, feel free to experiment! Happy hacking!

When you're ready for something more structured, try walking through these steps and see what you can complete.

## Step 1 - Create a button

Let's start by using HTML and CSS to create a simple button. It should look something like this:

![Screen Shot 2022-05-27 at 9 07 37 AM](https://user-images.githubusercontent.com/14914291/170737328-13bf6070-f9f5-4a32-bc06-bf45eafc2577.png)

## Step 2 - Add click handling

Let's now add a click handler to the button so that when clicked, it prints a random number in the console.

Hints: When we say "print", we mean use `console.log`. And random numbers can be generated using `Math.random()`. 

## Step 3 - Improve click handling

Now let's make things more realistic. Instead of just printing something to the console, let's add text when the button is clicked.

To do this, we should update our click handler functionality to add a new `<p>` tag to the DOM under the button. That `<p>` tag should say `My button was clicked, here is the random number I generated: <insert random number we generated>`.

This process of "conditionally" rendering something based on user action is a common pattern in web development. In other words, our app starts with only the button, but if a certain condition is met (i.e. the button is clicked), we want to add text to the page. Some common web UI use cases of this type of logic you might be familiar with include:
* showing a modal or popup when you click on a button to confirm your user action
* clicking an "expand" icon to show additional details or instructions
* seeing button text change from 'create' to 'edit' once you've created some sort of entity

## Step 4 - Track how many times we've clicked

Now let's update our logic to also track how many times the button has been clicked. Try to figure out a way to store how many times the button has been clicked and increment the count on each click.

Once you've done that, let's add another `<p>` tag that indicates how many times we've clicked. It should say something along the lines of `The button has been clicked <insert our count here> times`.

More steps to come!
