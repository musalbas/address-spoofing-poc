This is a modification of a proof-of-concept of a chrome address spoofing flaw published by David Leo (david.leo () deusen co uk) on the [Full Disclosure mailing list](http://seclists.org/fulldisclosure/2015/Jun/108).

**(According to the [original publication](http://seclists.org/fulldisclosure/2015/Jun/108), this was reported to Google but they regarded it as a non-vulnerability.)**

This version spoofs the HTTPS version of facebook.com. Surprisingly, it even shows the certificate in green:

![](https://raw.githubusercontent.com/musalbas/address-spoofing-poc/master/screenshot.png)

You can try a [live demo](http://musalbas.github.io/address-spoofing-poc/) but note that you may have to try it a few times for it to work. There's a connection timing condition involved. However if you clone the repo locally, it should work 100% of the time.
