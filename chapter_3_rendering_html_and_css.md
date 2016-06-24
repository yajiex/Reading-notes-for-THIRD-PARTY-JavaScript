# Chapter 3: Rendering HTML and CSS
* CSS files always load asynchronously when injected dynamically via JavaScript, so you won't run the risk of blocking other files
* Both the `type` and `rel` attributes must be present in order for them to function correctly in all browsers.
* Calling `document.close()` inside the iframe after you're done rendering forces the `onload` event to fire

