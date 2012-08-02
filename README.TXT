ang2html -- a hackish Angband Character Sheet to HTML converter

Marks up the character sheet with <span>s, <a name>s, and other HTML.
Relies on external CSS to prettify the output. Uses regexes wantonly.

Usage:
    ./ang2html < MyCharDump.txt > MyCharDump.html

    (and copy ang2html-stock.css to the destination, as well!)


TODO:

+ command line options
    + output barren html
    + reference alternate stylesheet
    + specify input and output files
+ drained stats not handled correctly
+ properly colorize 3rd column trait values
+ make an initial pass to get name, drained exp, 3rd column trait values
+ parse options section


MIT License:

Copyright (c) 2012 Brian "Beej Jorgensen" Hall <beej@beej.us>

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

-- 
For Tom.

