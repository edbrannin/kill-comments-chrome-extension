TODO: a Chrome extension to remove Comment Sections with a button.

(Last time I looked for a good one, I didn't like how any of them worked.)

Based on my Bookmarklet:

```
javascript:(typeof(jQuery) === 'undefined' ? $ : jQuery)('footer, #disqus_thread, footer, #comments, .comments, #below_fold_content, #subwrap, .comment').remove();
```

References:
* https://developer.chrome.com/extensions/declarativeContent
* https://developer.chrome.com/extensions/api_index
* https://developer.chrome.com/extensions/activeTab
* https://developer.chrome.com/extensions/devtools_inspectedWindow
* https://medium.freecodecamp.org/building-chrome-extensions-in-react-parcel-79d0240dd58f
