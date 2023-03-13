## root in CSS

- The root in CSS refers to the top-level element of the HTML document, which is represented by the :root pseudo-class.
* You can use the root element to define global CSS variables (also known as custom properties), which can be used throughout your stylesheet.
+ To define a global CSS variable using the root element, use the following syntax:
  ![Day8-Img1-Cheatsheet](https://github.com/Shees-Ali/Cheat-Sheet-resources-for-DFE/blob/main/Day%208/Day8-%20Img1%20-%20cheatcode.png?raw=true)
  
  where variable-name is the name of your variable, and value is the value you want to assign to it.
- You can then use your global CSS variable anywhere in your stylesheet using the var() function, like this:
  ![Day8-Img2-Cheatsheet](https://github.com/Shees-Ali/Cheat-Sheet-resources-for-DFE/blob/main/Day%208/Day8-Img2-%20cheatcode.png?raw=true)
* Using global CSS variables with the root element can make your stylesheet more flexible and easier to maintain. For example, you could define a color scheme using global variables for your brand colors, and then easily update the colors across your entire site by changing the values of the variables.
+ In addition to global CSS variables, you can also set other properties for the root element, such as font-size or background-color, which will apply to the entire document.
- It's important to note that the root element is not the same as the HTML body element. The root element applies to the entire document, while the body element only applies to the body of the document.
