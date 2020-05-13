---
layout: default
title: About
---

# Introduction

SimpleVFS it's a fork from [D-GameVFS](https://github.com/kiith-sa/D-GameVFS) that updates to the latest changes of the 
language, and attempt to polish and finish the previous works.

D:GameVFS, and by extension SimpleVFS, is a minimalist open source virtual file system library for the
D programming language oriented at game developers.

Provided functionality is very basic - files and directories can be created,
read and written, but not deleted. There are no security features - e.g.
SimpleVFS can't handle a situation when a file it's working with is deleted
outside the program. Only files in a physical file system are supported at the
moment. There is no archive support right now.

# Features

* File system independent, easy to use API for file/directory manipulation.
* No external dependencies.
* Seamless access to multiple directories as if they were a single directory.
* Easy to extend with custom file system backend.
* There is no support for ZIP or similar archive formats at the moment.
* There is no support for deleting files/directories, and none is planned.
* There are no security features and none are planned.

# License

D:GameVFS is released under the terms of the
[Boost Software License 1.0](http://www.boost.org/LICENSE_1_0.txt).
This license allows you to use the source code in your own projects, open source
or proprietary, and to modify it to suit your needs. However, in source
distributions, you have to preserve the license headers in the source code and
the accompanying license file.

Full text of the license can be found in file ``LICENSE_1_0.txt`` and is also
displayed here:

    Boost Software License - Version 1.0 - August 17th, 2003

    Permission is hereby granted, free of charge, to any person or organization
    obtaining a copy of the software and accompanying documentation covered by
    this license (the "Software") to use, reproduce, display, distribute,
    execute, and transmit the Software, and to prepare derivative works of the
    Software, and to permit third-parties to whom the Software is furnished to
    do so, all subject to the following:

    The copyright notices in the Software and this entire statement, including
    the above license grant, this restriction and the following disclaimer,
    must be included in all copies of the Software, in whole or in part, and
    all derivative works of the Software, unless such copies or derivative
    works are solely in the form of machine-executable object code generated by
    a source language processor.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE, TITLE AND NON-INFRINGEMENT. IN NO EVENT
    SHALL THE COPYRIGHT HOLDERS OR ANYONE DISTRIBUTING THE SOFTWARE BE LIABLE
    FOR ANY DAMAGES OR OTHER LIABILITY, WHETHER IN CONTRACT, TORT OR OTHERWISE,
    ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
    DEALINGS IN THE SOFTWARE.


# Credits

D:GameVFS was created by Ferdinand Majerech aka Kiith-Sa kiithsacmp[AT]gmail.com .

SimpleVFS was a fork created by Luis Panadero Guardeño aka Zardoz luis.panadero[AT]gmail.com .

The API was inspired the VFS API of the
[Tango library](http://www.dsource.org/projects/tango/).

D:GameVFS was created using Vim and DMD on Debian, Ubuntu and Linux Mint as a VFS
library in the [D programming language](http://www.d-programming-language.org).