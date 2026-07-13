---
title: "Cap'n Proto 0.5.1: Bugfixes"
url: "/news/2015-01-23-capnproto-0.5.1-bugfixes.html"
date: "2015-01-23"
feed_url: "https://capnproto.org/feed.xml"
---
Cap’n Proto 0.5.1 has just been released with some bug fixes: On Windows, the capnp tool would crash when it tried to generate an ID, e.g. when using capnp id or when compiling a file that was missing the file ID, because it tried to get random bytes from /dev/urandom , which of course doesn’t exist on Windows. Oops.
