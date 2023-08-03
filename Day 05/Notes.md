## Still dont understand how to make something magically appear and disapper in your project?

### Don't worry we got you. Also its not magic, its just css and Javascript :)

1. First, create a div element in HTML with a class name to represent the toast message. For example:

   ![Day5-Step1-cheatcode](https://github.com/Shees-Ali/Cheat-Sheet-resources-for-DFE/blob/main/Day%205/Day%205%20-%20Step%201%20-%20cheatcode.png?raw=true)
   
2. Style the toast message using CSS, including positioning, background color, font size, and other design elements. Pay special attention to scale in css properties because it is what we use to make the magic happen. 

   ![Day5-Step2-cheatcode](https://github.com/Shees-Ali/Cheat-Sheet-resources-for-DFE/blob/main/Day%205/Day%205%20-%20Step%202%20-%20cheatcode.png?raw=true)

3. Next, create a JavaScript function to show the toast message. This function should add a class of 'active' to the toast message div to make it visible on the page. You need to use some sort of event selector to trigger this function.  

   ![Day5-Step3-cheatcode](https://github.com/Shees-Ali/Cheat-Sheet-resources-for-DFE/blob/main/Day%205/Day%205%20-%20Step%203%20-%20cheatcode.png?raw=true)

4. Similar process can be used to remove the toast message by using 'classList.remove' on buttonclick or alternatively you can also set the toast message to close automatically using the following code snippet:

  ![Day5-Step4-cheatcode](https://github.com/Shees-Ali/Cheat-Sheet-resources-for-DFE/blob/main/Day%205/Day%205%20-%20Step%204%20-%20cheatcode.png?raw=true)
