# Chapter 4: Communicating with the server
* HTML script elements are waived from SOP checks
* Even though your code is loaded from a different origin, your code executes in the context of the publisher's website—and is subject to the SOP constraints placed on that document.
* JSONP. Being restricted to GET requests means a number of limitations. For starters, the amount of data you can submit to the server is limited to the browser's maximum URL size
* JSONP lacks error handling. If the script is successfully injected, your callback gets called, but if not, nothing happens. This means you can't detect cases where a JSONP request has finished with a 404, 500, or any other server error.
* 

