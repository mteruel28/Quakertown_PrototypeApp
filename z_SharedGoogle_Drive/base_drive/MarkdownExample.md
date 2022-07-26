# Main Heading equivalent to h1

A block of text separated by blank lines defines a paragraph

## Two hashes defines an h2 or 2nd level heading

### an h3 heading

* list item
* list item

This is a paragraph with the setup for a hyperlink [Visible link Text](http://url.to.link.to). some more text!

The main thing with a lot of the elements is make sure you use blank lines to separate the blocks so they can be identified and formatted correctly.

The file extension should be md if you are relying on an in-browser markdown converter, but if you are converting things later with pandoc, the file can just use a .txt file extension

Once pandoc is installed, you can convert markdown files to html fragments with something like "pandoc -o file.html file.txt" which takes the txt file and outputs it as html code.  That specific line does html fragment conversion so it won't have the <html><head><body> style tags surrounding everything.  There is a command to generate those, but I dont remember it off the top of my head.  It is in the documentation for pandoc.