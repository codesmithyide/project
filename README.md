# CodeSmithy Project Documentation

CodeSmithy is an IDE in very early stages of development. It is currently
only really useful to me for my own projects.

This repository contains the project documentation.


## Contents

- [Bootstrap](https://github.com/codesmithyide/Bootstrap): The scripts to build the CodeSmithy IDE from scratch.

- [BuildFiles](https://github.com/codesmithyide/build-files): code to read and update build files.

  [![codesmithyide](https://circleci.com/gh/codesmithyide/build-files.svg?style=shield)](https://circleci.com/gh/codesmithyide/build-files)

- [BuildToolchains](https://github.com/codesmithyide/build-toolchains): code to compile and link code using different toolchains.

  [![codesmithyide](https://circleci.com/gh/codesmithyide/build-toolchains.svg?style=shield)](https://circleci.com/gh/codesmithyide/build-toolchains)

- [CodeSmithy](https://github.com/codesmithyide/codesmithy): The code for the IDE.

  [![codesmithyide](https://circleci.com/gh/codesmithyide/codesmithy.svg?style=shield)](https://circleci.com/gh/codesmithyide/codesmithy)

- [ContentPlatform](https://github.com/codesmithyide/content-platform): the CodeSmithy content platform.

  [![codesmithyide](https://circleci.com/gh/codesmithyide/content-platform.svg?style=shield)](https://circleci.com/gh/codesmithyide/content-platform)

- [Doxygen](https://github.com/codesmithyide/doxygen): tools to work with Doxygen.

  [![codesmithyide](https://circleci.com/gh/codesmithyide/doxygen.svg?style=shield)](https://circleci.com/gh/codesmithyide/doxygen)

- [UMLWebWidget](https://github.com/codesmithyide/UMLWebWidget): A jQuery widget to display UML diagrams.

- [VersionControl](https://github.com/codesmithyide/version-control): code to interact with version control systems.

  [![codesmithyide](https://circleci.com/gh/codesmithyide/version-control.svg?style=shield)](https://circleci.com/gh/codesmithyide/version-control)


## Installation

### Installing the CodeSmithy components

The following build order can be used to build the projects from scratch:

1. build-toolchains
1. build-files
1. version-control
1. codesmithy/core
1. codesmithy/cli


## Support

None.


## License

Copyright (c) 2015-2024 Xavier Leclercq

Permission is hereby granted, free of charge, to any person obtaining a
copy of this software and associated documentation files (the "Software"),
to deal in the Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL
THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS
IN THE SOFTWARE.
