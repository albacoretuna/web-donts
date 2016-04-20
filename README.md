# WEB-donts
Things I don't like to do when I'm developing on the Web, written for future me. 

## JS-DON'TS

### Don't Forget to Cache AJAX calls
Check the network tab, if you see millions of XHR calls, there's a chance you can cache and reues some of them, instead of making a new call everytime. Check this article if you don't know how: https://gosukiwi.svbtle.com/the-right-way-of-caching-ajax-requests-with-jquery

### Don't pollute Global Environment 
If you start writing JavaScript inside a script tag right away, you're messing with the global scope. So if you use a name already used for your variables or functions, someone's code will break properly. 
