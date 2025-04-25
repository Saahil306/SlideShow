# SlideShow

Creating a slideshow in JavaScript is all about breaking down the larger goal into smaller, manageable tasks. Download the index.html, styles.css, and slideshow.js files, and follow the steps below. Complete and test each step before moving on to the next.

1. Use CSS to stack all images on top of one another instead of placing them vertically.

2. Only the first image should be visible. Use CSS to hide all other images.

3. In slideshow.js, create a variable called current and set it to 0. This will track the currently displayed image. It should cycle from 0 to 3, then back to 0 (since there are four images).

4. Create a variable called total and set it to 4, representing the total number of images.

5. Add a click event listener to the “Next” button. For now, simply console.log("next") to verify the button works.

6. Inside the "Next" button's click event, increment the current variable by 1. Use console.log() to confirm the value updates.

7. Add an if statement to reset current to 0 if it goes beyond 3.

8. Within the same event, hide all images and display only the one corresponding to the current index.

9. Repeat steps 5 through 8 for the “Previous” button, but this time decrement the current variable.

10. Use JavaScript’s setInterval() function to automatically change the image every 5 seconds.


## Repo Resources

* [Visual Studio Code](https://code.visualstudio.com/)

<br>
<a href="https://codeadam.ca">
<img src="https://cdn.codeadam.ca/images@1.0.0/codeadam-logo-coloured-horizontal.png" width="200">
</a>