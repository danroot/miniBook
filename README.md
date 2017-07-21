miniBook
===

Welcome!

This is a compression challenge for Web developers.

The goal is to compress the following text: [ws.txt](http://xem.github.io/miniBook/example/index.html),<br>
containing the complete work of William Shakespeare,<br>
based on the version hosted on [Project Gutenberg](http://www.gutenberg.org/ebooks/100).

This text is encoded in UTF-8 and has a size of 5,444,554 bytes.<br>
All line breaks are in the form "\r\n".<br>
All characters are in ASCII.

**Rules**

- Fork this repo.
- Copy the "example" folder and rename the copy with your Github username.
- Your folder contains a file called index.html, containing a &lt;xmp> HTML tag followed by all the content of ws.txt.
- You can create other text and/or binary files at your convenience.
- Compress your file as much as you can without altering the output.
- You can use HTML & JS only, no PHP.
- You can use HTML entities to replace any characters.
- The decompression must be performed entirely in the browser, without any user input, and use a reasonable amount of time (<30 min) and memory (<4GB) on a modern computer.
- You CAN use gzip (or concurrent) compression algorithms, other charsets than UTF-8, binary packing, neural network...
- You CAN use temporary elements (text, canvas...), but need to remove them from the DOM afterwards.
- You can NOT perform network queries or read any file that's not present in your folder.
- You can NOT use any browser extension, or the built-in spellchecker.
- Your score is the total size, in bytes, of the file(s) present in your folder.
- Open a merge request to appear in the leaderboard.

**Leaderboard**

(soon!)
