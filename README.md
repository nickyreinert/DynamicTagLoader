
# DynamicTagLoader

If you want to see what parameters your tracking setup records and you cannot use the development console, because you want to check this on a mobile device, this simple interface helps you.

**DynamicTagLoader** is a simple interface that takes the URL of a tag manager, like Adobe Launch, and implements it to the current website. The script contains a couple of event listeners that will listen to:

- XHTML Requests (XHR)
- image tags (so called tracking pixels)
- script tags
- any other fetch request to external resources

The outgoing request will be recorded and all GET-Paramaters will be displayed in the frontend. 

This site also saves the initial tag manager URL to a cookie to reload it the next time you get to the site. 
