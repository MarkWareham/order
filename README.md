 # Usage

This will not work when page is opened from filesystem, due to modern browser security settings.  Files need to be hosted on a web server to run in browser.

## Notes

- The line items are pulled via js from the included json file. 
- The payment form requires submission by ajax because it's within a pop up. This ensures consitency of user journey (pop up closes rather than page change)

## Assumptions

- I expect the page to be included via a templating system, so headers, footer, styling etc are not included, and assumed to be out of scope 
- Given time constraints data validation has not been included.
- Back end knows how much to take for payment due to serving up line items
- Security is of no concern here (e.g. PCI compliance) it's just to demo code. 

 