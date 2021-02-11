# JS practice problems

- Sign up for a <a href="https://codesandbox.io/signin" target="blank">CodeSandbox account</a> with your GitHub account.
- Your starter code contains an HTML page, and stylesheet.
- This has a new folder structure more like what you would see in real life. There is a *css* folder that has your main stylesheet, *styles.css* as well as a *normalize.css* to make sure the styles render consistently in all browsers. You'll also find an *img* folder with two images, and your JavaScript file, *script.js*, is in the *js* folder.

---

### JS Practice 0  
In this practice problem, you will practice linking your JS file to your HTML file, then change the `style` and `innerText` properties with `querySelector()`


#### Let's get started  
1. Fork the <a href="https://codesandbox.io/s/js-practice0-starter-cghl8" target="blank">starter code</a> and rename it to take off the word *starter*, then save it.
2. Navigate to the index.html file. In the `<head>`, link the JavaScript doc. Make sure to include the `defer` attribute so the JavaScript will load after the browser has finished loading the HTML file.
3. Save your sandbox, and then make sure your JavaScript file is correctly connected. You can check by writing a comment in your script.js file, like `console.log("Hi!");`. If the connection works, you should see the message in the console. If not, make sure you've added the correct file path: "js/script.js". (Note: You may need to refresh your browser to make sure that the link is working.)
4. In your script.js file, declare a variable called `mainTitle`.
5. In the value, use `querySelector()` to select the `h1` element.
5. Run `console.log()` to make sure the value is correct. In the console, you should see “<h1>JavaScript, our Magical Friend ✨ </h1>.” If not, check to make sure that you accessed the document before `querySelector()`. Also, be sure the `h1` inside `querySelector()` has quotation marks around it.
6. Now use the `innerText` property to change `mainTitle` to say "Yay, JavaScript!!".
7. Declare a variable called body to select the `body` element. You can use `console.log()` to make sure you've successfully selected the `body` element.
8. Change the background color of body to "coral".
10. When finished, save your sandbox and submit the link in the Teams assignment.

---

### JS Practice 1  
In this problem, you will get more practice manipulating the DOM. You'll also use `innerHTML` to add a span element to style a word in a heading. Then you will use the src attribute to change an image.

#### Let's get started  
1. Fork and rename the sandbox you used in the previous practice above, changing the name to *JS-practice1*.
2. In the script.js file, delete or comment out the JavaScript you wrote previously.
3. Declare a variable called `firstListItem`. In the value, select the first list item in the unordered list.
4. Use `console.log()` to make sure you selected `firstListItem`. In the console, you should see "<li>Build websites and web applications</li>". You can comment out the `console.log()` once you've verified that the correct elements were selected.
5. Change the border color of your `firstListItem` to #fbb32f. Don’t forget to camelCase the CSS property!
6. Create a variable called `moreReasons` and select the "more-reasons" class. Log out the `moreReasons` variable to ensure you’ve grabbed an `h3` element with the "more-reasons" class.
7. Change the font size of `moreReasons` to 2.5em.
8. Declare a variable called `whyJS` and select the first `h3` element with the text of "Why learn JavaScript?". Use `console.log()` to make sure you selected the correct `h3` element.
9. Use the `innerHTML` property to add a `<span>` with a class of "highlight" that will apply a background color behind the word "JavaScript". Hint: You'll want to surround the value with single quotation marks because double quotation marks must surround the class name to work in HTML and CSS.
10. Save your sandbox and view the h3 element. Right now, there's no highlighting because the "highlight" class doesn't have any style in the styles.css file. To make sure the span was applied correctly, log out `whyJS` to verify that it exists.
11. Let's add some style to the "highlight" class. Declare a variable called `highlight` to select the "highlight" class. Add a yellow background color like #ffff82.
12. Save the sandbox and you should see the word "JavaScript" highlighted now. Woot!
13. Now let's switch out the image. Declare a variable called `mainImage` and use it to select the first image. The parent element of the first image has a class of "js-image". As usual, use `console.log()` to ensure you've selected the right element.
14. Use the `src` attribute to change the image to js-code.png. Don't forget to add the file path!
15. Use the `alt` attribute to create a new image description, like "JavaScript code example".
16. Save your sandbox and paste the link in the Teams assignment.