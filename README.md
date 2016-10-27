! Cairo Graphics Library

Version 1.6

Author: Roman Miro, Ivan Denisov, Dmitriy Solomennikov

!! Overview

Cairo is a 2D vector graphics library with support for multiple output, like: screen, file, memory, printing devices. This subsystem gives you an OOP wrapper for constructing your own components.

Cairo subsystem consists of interface definitions of native Cairo API plus:

* CairoModels -	definitions of basic types, abstract classes
* CairoSurfaces - 	definitions of classes for different kinds of renderers
* CairoTexts - 	definitions of classes for text rendering facilities
* CairoUtil - 	different helper procedures

Cairo subsystem comes with demo programs which you can find in Cairo/Mod/Demos.

!! License

This library is free software; you can redistribute it and/ormodify it under the terms of the GNU Lesser General PublicLicense as published by the Free Software Foundation; eitherversion 2.1 of the License, or (at your option) any later version.This library is distributed in the hope that it will be useful,but WITHOUT ANY WARRANTY; without even the implied warranty ofMERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
See the GNU Lesser General Public License  for more details.

!! Installation

To use this binding some DLLs are required:

* libcairo-2.dll
* freetype6.dll
* libexpat-1.dll
* libfontconfig-1.dll
* libpixman-1-0.dll
* libpng12-0.dll
* zlib1.dll


You can find them in Windows distribution of Inkscape 32-bit: http://inkscape.org/download/windows

