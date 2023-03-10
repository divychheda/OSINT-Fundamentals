## Different Search Engines to try:
Google - https://www.google.com/

Google Advanced Search - https://www.google.com/advanced_search

Google Search Guide - http://www.googleguide.com/print/adv_op_ref.pdf

Bing - https://www.bing.com/

Bing Search Guide - https://www.bruceclay.com/blog/bing-google-advanced-search-operators/

Yandex - https://yandex.com/

DuckDuckGo - https://duckduckgo.com/

DuckDuckGo Search Guide - https://help.duckduckgo.com/duckduckgo-help-pages/results/syntax/

Baidu - http://www.baidu.com/ (For asian int.)

## Note:
- Google normally does a much better job. Sometimes, for image search, Yandex is good too (russian based).

## Google dorks
- If you only want to get results from a particular website use:
```
wgu calc site:reddit.com
```
- If you want ANDing of two query terms (similarly can use any other conditional operators):
```
wgu AND calc site:reddit.com
```
- If you want terms in a fixed order:
```
"wgu calc" site:reddit.com
```
- Can also use the wildcard:
```
"heath adams" the * mentor 
```
- Search for specific filetypes (pdf, xlsx, docx etc):
```
password site:tesla.com filetype:pdf    (this searches for the word password in all the pdfs under teslas website / domain)
```
- Search while excluding keywords:
```
"heath adams" -thecybermentor  (search for heath but exclude all results that also contain thecybermentor)
```
- You can also exclude subdomains
```
site:tesla.com -www -forums  ( this excludes www.tesla.com and forums.tesla.com from the search results )
```
- Can also search intext, intitle or inurl etc specifically:
```
"heath adams" intext:password   (returns docs which contain heath adams anywhere but theword password in their text body)
```
- Can do all of the above and more in google advanced search.
