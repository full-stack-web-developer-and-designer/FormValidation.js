# JavaScript Client-side Form Validation
This is the repository for **JavaScript** form validation, when a form is submitted. 
This form has 4 input fileds: *username, email, password* and *confirm password.*
Also they have two different styles for the inputs: *success* and *error* - both showing the different states of messages that the inputs can have.


For validation to work you need to these things correctly: 
* In all of the inputs you need to input something. 
* For username input, your username needs to be correctly written, allowed just letters a-z + letters čćđšž. This has been done and verified correctly using Regex
* For email input, your email needs to be correctly written (for example: contact@mirnesglamocic.com). This has been done and verified correctly, also using Regex
* For last two inputs, password and confirm password, the password you have entered in the first input called "password", you need to retype also in "confirm password"
## How do you know if it worked?
* If you have done everything correctly, your inputs on submit will change border-color to green with checkmark that everything is done correctly. Otherwise, your inputs will change border-color to red with exclamation mark that there have some errors.
##
[PREVIEW](https://full-stack-web-developer-and-designer.github.io/FormValidation.js/)

