#W3C DOM Events#

**IN PROGRESS**

Provides the useful W3C DOM **`Event`** and **`EventTarget`** interfaces as well as few others like `EventListener`, `CustomEvent`, and `DocumentEvent`.

Node.js EventEmitter is nice but is not standard and do not handle events exactly y the same way. This package first is realized in order to provide make some W3C / WHATWG standard APIs available on the server but can also be useful for any library / framework interested in providing APIs using standard JS Events.

It will be used by the upcoming [html5-eventsource](http://github.com/AMorgaut/html5-eventsource) (broken link)

See also: [w3c-domcore-errors](http://github.com/AMorgaut/w3c-domcore-errors)


##Requirements##

Only one:

* CommonJS Module support

This package is writen in pure JS and should then be usable from any CommonJS compliant JavaScript platform like **[node.js](nodejs.org)**, or **[TeaJS](https://code.google.com/p/teajs/)**. It is currently developed using the **[WakandaDB](http://wakandadb.org)** SSJS platform.## License (MIT License) ##Copyright (c) 2013 Alexandre MorgautPermission is hereby granted, free of charge, to any person obtaining a copyof this software and associated documentation files (the "Software"), to dealin the Software without restriction, including without limitation the rightsto use, copy, modify, merge, publish, distribute, sublicense, and/or sellcopies of the Software, and to permit persons to whom the Software isfurnished to do so, subject to the following conditions:The above copyright notice and this permission notice shall be included inall copies or substantial portions of the Software.THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS ORIMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THEAUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHERLIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS INTHE SOFTWARE.