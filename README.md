# html-element-scraper
Asynchronous Javascript Function

Currently browser-based (doesn't work locally/server-side)

## What does it do?
Fetches page contents from a URL, then uses DOM operations to retrieve the value of specific elements

## How do I use it?
1. Run the code in the browser console
2. Wait for prompt and enter URL
3. Wait for prompt and enter the Element ID's separated by comma
4. The value of those elements will be printed to the page



## Plans for future updates
- Accept other identifiers, like class (or possibly mimic CSS selectors)
- Improved I/O
  - currently relies on browser prompts
  - Use Node.JS to run server side
  - Accept inputs from other programs/terminal

## What Javascript methods are used?
[DomParser.parseFromString()](https://developer.mozilla.org/en-US/docs/Web/API/DOMParser/parseFromString)

[Document.getElementById()](https://developer.mozilla.org/en-US/docs/Web/API/Document/getElementById)

[Document.write()](https://developer.mozilla.org/en-US/docs/Web/API/Document/write)

[fetch()](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch)

## References
https://developer.mozilla.org/en-US/docs/Glossary/IIFE

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function
