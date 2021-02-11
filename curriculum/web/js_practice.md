# JS practice problems

- Sign up for a [CodeSandbox account](https://codesandbox.io/signin) with your GitHub account.
- Your starter code contains an HTML page, and stylesheet.
- This has a new folder structure more like what you would see in real life. There is a *css* folder that has your main stylesheet, *styles.css* as well as a *normalize.css* to make sure the styles render consistently in all browsers. You'll also find an *img* folder with two images, and your JavaScript file, *script.js*, is in the *js* folder.

In this practice problem, you will practice linking your JS file to your HTML file, then change the `style` and `innerText` properties with `querySelector()`


### Let's get started  
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