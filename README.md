# This repository is a website
(or more specifically, the "docs" folder is a website)

This is an example of an old-school, but still quite useful class of website -- a static website. These are the simplest class of websites available: A folder structure on a computer is mapped directly to the URL stucture. No dynamic behavior is supported, and changes to content are only made by directly editing files.

## Advantages to this type of website:

* Easy to make
  * "shortest" tech-stack. html/css/js
  * very little "magic" (index.html is default page for a folder)
* Easy to host
  * Many low-to-no setup, free hosting options
    * [Github pages](https://pages.github.com/)
	* [Many Others[(https://graygrids.com/free-static-html-hosting-providers/)
  * Easy to test/debug locally: [https://developer.mozilla.org/en-US/docs/Learn/Common_questions/set_up_a_local_testing_server#running_a_simple_local_http_server](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/set_up_a_local_testing_server#running_a_simple_local_http_server)
* Simplicity brings focus
  * This is a great way to practice core web technologies: HTML / CSS / JS 
  * Tech stack is too "dumb" to "hide" the source of an issue

## Starting the server
Strating this server is easy. 

* In the docs folder run `python3 -m http.server 1337`
* Then go to [http://localhost:1337](http://localhost:1337) in your browser
* Server is now running locally -- to "share" (temporarily) look at services like [ngrok](https://canvas.umn.edu/courses/217951/pages/ngrok.com)
