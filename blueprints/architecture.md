

## Modules to implement
user <-talks with-> serving ai -give search order-> Q&A ai -creates search threads-> web crawler fetches a list of information -gives to-> content DB
user <-ask questions-> serving ai -give search order-> Q&A ai -looks into-> content DB

### Web crawler
input : given search keywords | output : list of links

### Internal link & content database
input : list of links + search keyword + user interest | output : relevant chunks of information
input : relevant chunks of information + list of links | process : save links with reverse index on keywords
input : keywords | output : links
input : keywords | output : information chunks

### voice command
voice to text
text to voice
selectable preset of voices

### Q&A ai interface
general purpose information parser
narrows down user commands and information request into executable functions
(if possible & effective)writes down new functions to parse information with user specified modular objectives (function rewrites itself if user defines result as inadequate)

### serving AI
input : user query | output : preset of command (look for info in DB, add new search topic, ...)
input : question + information chunks | output : answer
input : preset command | output : command execution confirmation or status













