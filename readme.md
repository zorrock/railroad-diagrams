# Purpose

- Define a grammar using a "functional representation"
- Display the railroad diagrams of a grammar
- Display an EBNF textual representation of this grammar
- Validate expressions written for this grammar
- Tag associated tokens with corresponding grammar chunks
- Transform an EBNF grammar into a SRFB grammar format (railroad grammar)
- Validate expressions compliant with the above EBNF grammar

# Where to start

You can

- Test it [there](https://rawgit.com/gbrault/railroad-diagrams/gh-pages/live/live.html)
- Browse documentation [here](https://github.com/gbrault/railroad-diagrams/blob/gh-pages/live/doc/readme.md)

# History

I have started with [tabakins](https://github.com/tabatkins/railroad-diagrams) railroad-diagrams fork, but a lot evolutions took place then, not only one can display svg railroad graphs but can 

- generate the validator
- validate (is the sentence well formed or not)
- get the "compiled" result: which part of the sentence is what?
