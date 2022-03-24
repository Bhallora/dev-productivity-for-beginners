# dev-productivity-for-beginners
This repo will act like a documentation of my journey as a jr. dev. It will contain tips and tricks to increase productivity. 
Code-editor short-cuts, extensions, mac-OS usability tips, code snippets with use cases and anything I learn on the way.



# Tips for Debugging Javascript (in local setup):
   a. If you wanna debug a DOM element use <b> "console.dir(particularVariableContainingTheDOMElement)" </b>  instead of <i>console.log()</i> as it provides formatted value of the entire DOM element. <br>
   b. Instead of using template literals i.e <b> "console.log(`This is the value ${value}`)"</b>, try using comma separation i.e <b>"console.log("This is the value", value)"</b>. This will not change the type of the "value" to a string unlike template literals.<br>
   c. If you wanna know the name of the actual variable name associated with the value in console in a more easy way: <b>"console.log({value})"</b>. The result in console will be in object format where the key will be the name of the variable. <br>
   d. For printing values of Array/Objects instead of using <b> console.log(nameOfTheArray) </b> which will print it in a single line, try using <b> console.table(nameOfTheArray)</b>, this will provide the value in table format. <br>
   e. we can use <b> console.assert(any condition) </b> this will give us whether the condition is passed or failed. Similarly we can use <b>console.error("error_message")</b> and <b> console.warn("warning_message")</b> to print error and warning message respectively in colored forms. <br>
   f. To check the time taken by a certain process suppose a function, use <b> console.time() </b> in the beginning of the process and use <b> console.timeEnd()</b> at the end of the process. This will provide the time taken for execution of that particular process. <br>
   g. Using <b> debugger; </b> statement in the code will put a break point in that particular state in the browser and thereby one can take help of the developer tool of the browser to proceed forward. Or directly use the developer tool to put breakpoint. <br>
   h. One can use the <b> run and debug </b> option of VScode to connect the code editor and browser for debugging. <br>
   i. Most importantly <b>take a chill pill and read the error messages/error line numbers carefully</b> :):):)
