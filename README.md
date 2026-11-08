# Coffee remote

A small single-page web app for a family xBloom Studio coffee machine whose front panel is broken. It connects over Web Bluetooth (Chrome on Android, Windows or macOS) and sends one saved pour-over recipe, with live progress, pause and stop.

It only talks to a machine within Bluetooth range, after the user picks it in Chrome's device chooser.

## Third-party notice

The Bluetooth protocol code (frame format, CRC, recipe blob and firmware consistency gate) is a JavaScript port of [xbloom-py](https://github.com/Alshekhi/xbloom-py).

```
MIT License

Copyright (c) 2026 Mansour Alshekhi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

Not affiliated with xBloom.
