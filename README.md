lp-input
=========

lp-input is a custom "fake input" to search users, hashtags by ajax and to 
format the content by using ordinary div#editable. Works like twitter, facebook,
slack, etc. 

This custom element works with FF (37), Chrome (42), Opera (27) and partially with
Safari (8) or browsers that supports Web API as [Range](https://developer.mozilla.org/en/docs/Web/API/Range), [Selection](https://developer.mozilla.org/en-US/docs/Web/API/Selection).

Usage
======

```
      <div id="editable" contenteditable="true"></div>  
      <lp-input target="editable" mentionsURL="https://example.com/users.json">
      </lp-input>
```


