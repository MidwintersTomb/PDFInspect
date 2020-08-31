# PDFInspect

Nothing fancy here, just a basic inspector of PDF files for embedded content (JS, URI, etc) that I threw together after having to do it manually more than once.

Runs cat and strings, as some files throw a binary error when using cat.  Results write out to file in the same path as the file inspected.

Syntax:
./pdfinspect.sh /path/to/filename
