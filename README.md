 A simple Chrome extension or web app that lets users save and manage a list of URLs ("leads").

Stores URLs: Users can add URLs manually via an input field or by clicking a button to save the current browser tab’s URL.

Persists Data: URLs are saved in localStorage so they persist across page reloads.

Displays URLs: The saved URLs are rendered as clickable links in a list.

Delete Functionality: Double-clicking the delete button clears all saved URLs.

Tab Button: Uses the Chrome Extensions API (chrome.tabs.query) to get the current tab’s URL and save it.

Quick start:

```
$ npm install
$ npm start
````

* Scrimba course 
