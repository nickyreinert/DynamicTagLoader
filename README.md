# DynamicTagLoader
Dynamic Tag Library Loader is a simple JavaScript interface that takes the URL to a tag manager, like Adobe Launch, and implements it to the current website. It contains a couple of event listeners that will listen on:
- XHTML Requests (XHR)
- Image creations (so called tracking pixels)
- any other fetch approaches of external resources

The outgoing URL will be recorded and all GET-Paramaters will be displayed in the frontend. 

This site also saves the initial tag manager URL to a cookie to reload it the next time you get to the site. 
