#Why Currying

The goal of this workshop is to learn concept and create a function to apply curry in JavaScript.

Currying is the technique of translating the evaluation of a function that takes multiple arguments (or a tuple of arguments) into evaluating a sequence of functions, each with a single argument. The number of arguments or operands that the function takes is also known as arity /ˈærᵻti/ of a function.

JavaScript has functional capabilities, but currying isn’t built in by default (at least not till the time of writing.. :)).
Installation & Update

''$ npm install -g currying-workshopper''

Some npm installations require use of sudo in the above command. Recommend to instead reinstall node/npm so you don't need sudo.
Usage Instructions
1. Selecting a problem to work on

Once the workshop is installed, run curry to print a menu where you can select a problem to work on.

$ curry

You are advised to complete them in order, as later problems will build on skills developed by solving previous problems.
2. Writing your solution

Once you have selected a problem, the workshop will remember which problem you are working on. Using your preferred editor, simply create a file to write your solution in.
3. Testing your solution

Use the workshop's run command to point the workshop at your solution file. Your solution will loaded and passed the problem input. This usually won't perform any validation, it will only show the program output.

$ curry run mysolution.js

4. Verifying your solution

Your solution will be verified against the output of the 'official' solution. If all of the output matches, then you have successfully solved the problem!

$ curry verify mysolution.js
