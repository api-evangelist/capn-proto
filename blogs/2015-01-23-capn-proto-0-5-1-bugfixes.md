---
title: 'Cap''n Proto 0.5.1: Bugfixes'
url: https://capnproto.org/news/2015-01-23-capnproto-0.5.1-bugfixes.html
date: '2015-01-23'
author: ''
feed_url: https://capnproto.org/feed.xml
---
Cap’n Proto 0.5.1 has just been released with some bug fixes: On Windows, the capnp tool would crash when it tried to generate an ID, e.g. when using capnp id or when compiling a file that was missing the file ID, because it tried to get random bytes from /dev/urandom , which of course doesn’t exist on Windows. Oops. Now it uses CryptGenRandom() . Declaring a generic method (with method-specific type parameters) inside a generic interface generated code that didn’t compile. joinPromises() didn’t work on an array of Promise<void> . Unnecessary error messages were being printed to the console when RPC clients disconnected. Sorry about the bugs. In other news, as you can see, the Cap’n Proto web site now lives at capnproto.org . Additionally, the Github repo has been moved to the Sandstorm.io organization . Both moves have left behind redirects so that old links / repository references should continue to work.
