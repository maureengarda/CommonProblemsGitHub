# Help! My program runs in Processing but not on GitHub
Some common problems that could cause your program not to work on the web are:
- Naming a variable with the same name as a function
- Naming two variables with the same name
- Naming a function or a variable with a name that is already used in Processing
- Using an image as an argument in `background()`
- Leaving the debugging tools `System.out.println()` or `System.out.print()` in your finished program
- Using decimals for x and y coordinates
- Integer division
- Extra semi-colons
- The name of the .pde file doesn't match the name in the canvas id tag in index.html

To display our AP Java programs on the web, we're using [processing.js](http://processingjs.org/). Not all Processing functions are compatible with processing.js. You can check [this list](http://processingjs.org/reference/) to see if you are using a function that isn't supported. 

Looking for error messages can also provide clues to the problem. You can find the error messages for your webpage by opening the *web console* or *javascript console* in your browser. To open the console in Chrome, press the F12 key. To open the console in Firefox, use Ctrl + Shift + J.
