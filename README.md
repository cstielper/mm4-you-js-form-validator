# MM4 You Javascript Form Validator
Version: 1.0

This javascript validator requires valid HTML markup, and assignment of two variables in the javascript file to function. It has no dependencies. Currently, it checks for empty values on fields that are marked as required, and "valid" email addresses on input[type="email"] using a regular expression (whether the email field is required or not).

This has been tested in IE10+, IE Edge, Chrome 53+, Firefox 48+, Mobile Safari 5.1+, Android 4.0

This demo is set up to validate one form on the page, but additional forms can be validated by adding the two required variables as well as an additional event listener at the end of the script for each form you want to add.

## HTML Form Instructions:
Markup your form(s). Add a class of "required" to form elements (input, textarea, select, email, radio, etc.) that are required form fields in order to submit the form. Add the "data-error-label" attribute to create an error name. This is the name that will be displayed to the user when their submission fails validation. Add an html element with a class of "msg-box" in your form to display the form errors. In this demo, it is a "div".

## Javascript Instructions:
You will need to enter two variables:

1. "errorClass" - The CSS class that you are using to style errors in the DOM.
2. "form" - The "name" attribute of the form that you would like to validate.

No further edits are necessary. After declaring your variables, you should minify "mm4-you-validate.js" and use that in your HTML markup. Commenting has been added throughout the unminified version of the script for explanation of functionality.
