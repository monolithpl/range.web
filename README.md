# range web
Highlight most frequently used English words in texts. Adaptation of Paul Nation's Range vocabulary profiler for the web. Perfect for building vocabulary awareness in ESL students. Analyze your text for high frequency lexis [here](http://monolithpl.github.io/range.web/)

### features
- highlights and lists high frequency lexis from each of the top 10'000 most frequent words in a given text
- incorporates Paul Nation's [BNC/COCA word family lists](http://www.victoria.ac.nz/lals/about/staff/paul-nation)
- very fast lookups using a slightly modified version of [Steve Hanov's succinct bit string trie implementation](http://www.hanovsolutions.com/trie/Bits.js)
- fully client-side and portable - works offline, too!
- zero framework rubbish - pure vanilla javascript with zero overhead - tiny code with zero external dependencies
- responsive mobile-first layout

### demo
[check it out here](http://monolithpl.github.io/range.web/)

### further reading
- [Paul Nation's webpage](http://www.victoria.ac.nz/lals/about/staff/paul-nation)
- [BNC/COCA word family lists README](http://www.victoria.ac.nz/lals/about/staff/publications/paul-nation/Information-on-the-BNC_COCA-word-family-lists.pdf)
- [Some Research Uses Of Vocabprofile (VP)](http://www.lextutor.ca/vp/research.html)

### implementation details
Read more about performance-first string lookups in javascript using trie-s here:
- [Succinct Data Structures: Cramming 80,000 words into a Javascript file](http://stevehanov.ca/blog/index.php?id=120)
- [John Resig's Revised JavaScript Dictionary Search](http://ejohn.org/blog/revised-javascript-dictionary-search/)

MIT License

Copyright 2016 Wiktor Jakubczyc
