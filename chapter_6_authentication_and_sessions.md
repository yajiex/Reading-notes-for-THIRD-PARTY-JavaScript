# Chapter 6: Authentication and Sessions
* Cookies that are written or sent inside an iframe whose domain differs from the parent document domain are also considered third-party.
* Browser would disable localStorage when third-party cookies are disabled.
* Setting cookies in new windows opened by your third-party application, whereupon those cookies are considered to be first-party.
* Basically, be aware of the `secure` flag when setting cookies, and use it for cookies that should only be transmitted over HTTPS.
* 

