fontconfig-infinality-ultimate
==============================

This is a collection of fontconfig rules for Gentoo originally written
by bohoomil. Together with cairo and fontconfig with infinality
patches as found in main portage tree they provide a powerfull and
unique font rendering system for linux.

Besides a set of rendering rules fontconfig-infinality-ultimate
contains two predefined font replacement tables covering widely used
and de facto "standard" font families in digital world:

* infinality-ultimate-free defines free replacements for popular
  propertiary font families
* infinality-ultimate-ms uses Microsoft fonts found in corefonts
  package and other propertiary fonts.

Usage
-----

1. Disable all fontconfig rules but 52-infinality.conf using eselect
   fontconfig
2. Enable infinality-ultimate-free or infinality-ultimate-ms preset
   using eselect infinality
3. Select infinality-ultimate lcdfilter settings using eselect
   lcdfilter

For more information see original README.orig Keep in mind that most
of the installation and usage instruction are not valid for this
Gentoo package.

Authors
-------

All credit goes to bohoomil <@zoho.com> the original author of
infinality-ultimate.

This repository is a repackage of his work by Witold Piłat
<witold.pilat@gmail.com>

License
-------

The MIT License (MIT) <http://opensource.org/licenses/MIT>
Copyright (c) 2013 bohoomil

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
