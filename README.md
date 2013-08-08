Google-Chrome-Metacritic-Search-URL-Fix
=======================================

Replaces %20 with + in URLs in order to build valid URLS for using a Metacritic search engine shortcuts in Chrome.

This extension is for anyone who wants to add Metacritic to their search engines in Chrome. If you've tried to do that before, you'll have noticed that it doesn't work if the search term contains more than one word (i.e. a space). That's because Metacritic uses weird search strings that replace the space with a "+", but Chrome assumes that a search string will replace a space with a "%20".

Its such a simple little thing, but it's very frustrating. This extension replaces the "%20" with a "+", allowing you to add Metacritic to your search engines!

This is the search URL you need: http://metacritic.com/search/all/%s/results

This builds on FearJiri's Google-Chrome-URL-Replacer-Extension. I have added a couple of lines so that it works in a modern Chrome Browser, and icons for prettiness.

If you want to install it, the extension is published at: https://chrome.google.com/webstore/detail/metacritic-search-fixer/kmhekhelpcjkempcidfnkekhnkmedpih
