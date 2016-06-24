# Chapter 2: Distributing and loading your application
* For starters, window and undefined are two objects that you'll likely use repeatedly in your code. When they're declared as local variables like this, a JavaScript minifier can shorten their variable names to help reduce the script's file size. But if they're referenced as global variables, those references can't be renamed and shortened. `undefined` isn't explicitly passed to the function. There's a benefit to aliasing undefined like this. If the original object has been modified by code elsewhere in the current execution environment, it won't affect your code, because you're using a local alias that has the original, untouched value.
      var Stork = (function(window, undefined) {
          // 
      })(window);
* The jQuery authors have been kind enough to provide a helper function called noConflict that allows you to reassign the global jQuery object ($) to another variable.
      var Stork = Stork || {};
      Stork.$ = Stork.jQuery = jQuery.noConflict(true);
* The fragment identifier is the last part of the URL, and includes everything that comes after the hash (#) character. It's traditionally used to identify a portion of a document, and unlike the query string, isn't sent to the server by the browser.
* 

