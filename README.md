# Data streamer for the browser

Simple tool to stream web-based textual files and monitor them in given frequencies.

## To Install

Simply copy **index.html** into a directory that is being served via http or https.

## To Use

1. Assuming that the URL to the directory where **index.html** was installed is **https://example.com/dir/**,
2. Call **https://example.com/dir/?source=filename*&interval=duration**, where ***filename*** is a text resource (file or otherwise) accessible via http(s), and ***interval*** is the number of milliseconds to wait before each refresh
3. That's it!
