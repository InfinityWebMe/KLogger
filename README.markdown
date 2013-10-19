# KLogger: A Simple Logging Class For PHP

## About

KLogger is an easy-to-use logging class for PHP. It supports standard log levels
like debug, info, warn, error, and fatal. Additionally, it isn't naive about
file permissions (which is expected).

## Basic Usage

    $log = new KLogger('/var/log/'); # Specify the log directory
    $log->logInfo('Returned a million search results'); //Prints to the log file
    $log->logFatal('Oh dear.'); //Prints to the log file
    $log->logInfo('Here is an object', $obj); //Prints to the log file with a dump of the object

## Special Thanks

Special thanks to original author:

[Kenny Katzgrau](https://github.com/katzgrau) 

Special thanks to all contributors, which right now includes three people:

[Tim Kinnane](http://twitter.com/etherealtim)
[Brian Fenton](http://github.com/fentie)
[Cameron Will](https://github.com/cwill747)

## License

The MIT License

Copyright (c) 2013

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
