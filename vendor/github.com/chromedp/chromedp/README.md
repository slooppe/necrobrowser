# About chromedp [![GoDoc][1]][2] [![Build Status][3]][4]

Package chromedp is a faster, simpler way to drive browsers supporting the
[Chrome DevTools Protocol][5] in Go using the without external dependencies
(like Selenium or PhantomJS).

## Installing

Install in the usual Go way:

	go get -u github.com/chromedp/chromedp

## Examples

Refer to the [GoDoc page][7] for the documentation and examples. The
[examples][6] repository contains more complex scenarios.

## Resources

* [chromedp: A New Way to Drive the Web][8] - GopherCon SG 2017 talk
* [Chrome DevTools Protocol][5] - Chrome DevTools Protocol Domain documentation
* [chromedp examples][6] - various `chromedp` examples
* [`github.com/chromedp/cdproto`][9] - GoDoc listing for the CDP domains used by `chromedp`
* [`github.com/chromedp/cdproto-gen`][10] - tool used to generate `cdproto`
* [`github.com/chromedp/chromedp-proxy`][11] - a simple CDP proxy for logging CDP clients and browsers

[1]: https://godoc.org/github.com/chromedp/chromedp?status.svg
[2]: https://godoc.org/github.com/chromedp/chromedp
[3]: https://travis-ci.org/chromedp/chromedp.svg
[4]: https://travis-ci.org/chromedp/chromedp
[5]: https://chromedevtools.github.io/devtools-protocol/
[6]: https://github.com/chromedp/examples
[7]: https://godoc.org/github.com/chromedp/chromedp
[8]: https://www.youtube.com/watch?v=_7pWCg94sKw
[9]: https://godoc.org/github.com/chromedp/cdproto
[10]: https://github.com/chromedp/cdproto-gen
[11]: https://github.com/chromedp/chromedp-proxy
