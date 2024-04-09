
# DynamicTagLoader

If you want to see what parameters your tracking setup records and you cannot use browser or development console, because you want to check this on a mobile device, this simple interface helps you.

Dynamic Tag Library Loader is a simple JavaScript interface that takes the URL to a tag manager, like Adobe Launch, and implements it to the current website. It contains a couple of event listeners that will listen on:
- XHTML Requests (XHR)
- image tags (so called tracking pixels)
- script tags
- any other fetch approaches of external resources

The outgoing URL will be recorded and all GET-Paramaters will be displayed in the frontend. 

This site also saves the initial tag manager URL to a cookie to reload it the next time you get to the site. 
