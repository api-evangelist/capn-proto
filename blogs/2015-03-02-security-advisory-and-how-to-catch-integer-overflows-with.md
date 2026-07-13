---
title: "Security Advisory -- And how to catch integer overflows with template metaprogramming"
url: "/news/2015-03-02-security-advisory-and-integer-overflow-protection.html"
date: "2015-03-02"
feed_url: "https://capnproto.org/feed.xml"
---
As the installation page has always stated, I do not yet recommend using Cap’n Proto’s C++ library for handling possibly-malicious input, and will not recommend it until it undergoes a formal security review. That said, security is obviously a high priority for the project. The security of Cap’n Proto is in fact essential to the security of Sandstorm.io , Cap’n Proto’s parent project, in which sandboxed apps communicate with each other and the platform via Cap’n Proto RPC.
