---
layout: post
title: WebApp Client Library for Android released
---

Android-WebApp is a library to build webapps for Android. Creating an Activity
that is a webapp is as easy as extending a library class and writing a
one-liner method to set the home page. Everything else that is needed is
handled transparently by the library, but it can be fully customized when
needed by just overriding any methods.

Making this code into a library makes it easy to write webapp clients without
duplicating code, and future improvements in the library will reflect on the
clients by just rebuilding them against the new library version.

Currently, the library handles connection errors, lifecycle events, screen
rotation, remembering the last visited page, persistent cookies, openning some
URLs in an external browser and changing the User Agent String. Future planned
improvements are persistent caching of CSS/JS resources and menu integration.

Check it out at GitHub: [android-webapp](https://github.com/berarma/android-webapp/)
