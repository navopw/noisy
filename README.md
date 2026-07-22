# noisy

> A procedural noise-map generator with a Swing GUI. Generate value noise maps with configurable interpolation.

Noisy lets you generate 2D noise maps visually, choose between interpolation methods, and export the results. Built as a Java desktop application using Swing.

![screenshot](http://i.imgur.com/8SlS8Oi.png)

**Note: This project is no longer actively maintained, but still works in its current state.**

## Features

- **Value Noise algorithm** — Generate smooth 2D noise maps
- **Interpolation methods** — Choose how noise values are blended:
  - Linear interpolation
  - Cosine interpolation
- **Configurable resolution** — Adjust the output map size (16–2048)
- **Swing GUI** — Native look and feel on any platform

## Prerequisites

- Java 8 or later

## Installation

Download the latest release from the [releases page](https://github.com/navopw/noisy/releases).

## Usage

1. Download and run the `.jar` file:

```bash
java -jar noisy.jar
```

2. Select a noise algorithm from the dropdown
3. Select an interpolation method
4. Set the desired resolution
5. Click generate to create the noise map

## Special thanks

- [@Masy](https://github.com/Masy) for helping code the noise algorithms

## Bugs or suggestions?

[Create an issue](https://github.com/navopw/noisy/issues/new)

## License (MIT)

Copyright © 2017 [navopw](https://github.com/navopw)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
