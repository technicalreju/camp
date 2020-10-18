CAMP is currently unmaintained; if you intend to use it, we strongly recommend to have a look at these two forks:

https://github.com/fw4spl-org/camp
Based on the original API, this fork brings modernity to the internal code (C++11, Qt5), as well as improvements to the
build files for compatibility with Debian packaging.

https://github.com/billyquith/ponder
Ponder is a new project carried by Billy Quith, that brings CAMP to a new life and a new level.
It is more a rewrite than a fork, as many things were redesigned and reimplemented from scratch.
Please prefer Ponder to CAMP: you'll get rid of Boost, you'll benefit from C++11 and you'll get good support from Billy.

-- The former CAMP team --

***

CAMP is a multi-purpose reflection library developped by Technogerma Systems France and then by Tegesoft (where the dev team has moved)
(http://www.tegesoft.com).

It provides an abstraction for most of the high-level concepts of C++:
- Classes
- Enumerations
- Properties
- Functions
- Objects
- Variables
- Abstraction
- Inheritance
- Encpasulations

By wrapping all these concepts into abstract structures, CAMP provides an extra layer of
flexibility to programs, and allow them to fully expose their data structures at runtime.

Many applications can take advantage of CAMP, in order to automate tasks which would
otherwise require a huge amount of work. For example, CAMP can be used to expose and edit
objects' attributes into a graphical user interface. It can also be used to do
automatic binding of C++ classes to script languages such as Python or Lua.
Another possible application would be the serialization of objects to XML, text or
binary formats. Or you can even combine all these examples to provide a powerful
and consistent interface for manipulating your objects outside C++ code.
