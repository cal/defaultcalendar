defaultcalendar
==============

Command line tool for setting the default calendar (.ical handler) in macOS X.

Install
-------

Build it:

```
make
```

Install it into your executable path:

```
make install
```

Usage
-----

Set the default calendar with, e.g.:

```
defaultcalendar outlook
```

Running `defaultcalendar` without arguments lists available .ical handlers and shows the current setting.

How does it work?
-----------------

The code uses the [macOS Launch Services API](https://developer.apple.com/documentation/coreservices/launch_services).

License
-------

MIT
