WebRTC Example
==============

A WecRTC webcam loop-back server example based on https://github.com/feross/simple-peer and https://github.com/shanet/WebRTC-Example

Usage

Simple-peer is used on the client and server. The signaling server uses Node.js and `ws` and can be started as such:

```
$ npm install
$ npm start
```

With the server running, open a recent version of Firefox, Chrome, or Safari and visit `https://localhost:8443`.

* Note the HTTPS! There is no redirect from HTTP to HTTPS.
* Some browsers or OSs may not allow the webcam to be used by multiple pages at once. You may need to use two different browsers or machines.

## TLS

Recent versions of Chrome require secure websockets for WebRTC. Thus, this example utilizes HTTPS. Included is a self-signed certificate that must be accepted in the browser for the example to work.

## License

The MIT License (MIT)

Copyright (c) 2014 Shane Tully

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
