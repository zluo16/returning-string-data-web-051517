# Returning String Data

## Objectives

  * Return plain strings as HTTP responses
  * Undertand that the internet is just returning Strings!
  * Replace a Div with String returned

## Outline

  * Remind them that the Internet is just returning strings. nothing else
  * HTML is one format, which is agreed upon by all browsers, but we technically can just return a string
  * In this repo is a blog application
  * Create a new GET route at `/post/:id/body` This will be used to just return the body of the post as a plain string
  * Walk them through writing the controller to do this
  * Hit the location with a browser, look it's just text!
  * Now modify the index page to just show the first two sentences of a post with a button to "show more".
  * When user clicks show more it doe the ajax request and replaces the inner html.
  * **cliff hanger** what if we wanted all of the data? what if we wanted show the `show` page without any page refresh? Doing multiple requests to `/post/:id/body` and `/post/:id/title` etc.. would be annoying. THERE MUST BE A BETTER WAY
