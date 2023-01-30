To run this site you'll need:
- Ruby v2.5.0 or higher
    - (using Ruby v3.0.0 or higher will mean you also need to add webrick to dependencies)
- RubyGems
- GCC and Make
- (See this link for more https://jekyllrb.com/docs/installation/#requirements )

Run `bundle exec jekyll serve` in the terminal (in the /docs file) to run site locally, then go to localhost:4000 to access it.

---

To edit this site, simply make a new .html file in /docs.
At the very top, before any HTML, include the lines:
```--- 
layout: default 
title: [pagename] 
---
```
This makes sure the Jekyll theme will work
