## NOTICE
This is a clone of the J2V8 repository.
NOTICE: prebuild directory contains precompiled binaries for J2V8 with NodeJS for Android. 

BUILD TIME: 20210805 01:21 AM (Asia/Shanghai) (GMT+8)

J2V8
====

![Build Status](https://github.com/eclipsesource/J2V8/workflows/Build%20J2V8/badge.svg)
[![Maven Central](https://img.shields.io/maven-central/v/com.eclipsesource.j2v8/j2v8.svg)](http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22com.eclipsesource.j2v8%22)

J2V8 is a set of Java bindings for V8. J2V8 focuses on performance and tight integration with V8. It also takes a 'primitive first' approach, meaning that if a value can be accessed as a primitive, then it should be. This forces a more static type system between the JS and Java code, but it also improves the performance since intermediate Objects are not created.

We developed J2V8 as a high performance engine for our multi-platform mobile toolkit [tabris.js](https://tabrisjs.com) and it is a great choice for executing JavaScript on Android devices.

Building J2V8
=============
Building J2V8 requires building both the native parts and the Java library (.jar/.aar file). To build the native parts we first build V8 as a monolithic library and then statically link J2V8 to that. The Java parts are built with maven/gradle.

J2V8 uses a cross-platform, cross-compiling build-system written in Python.

For any further build instructions & details please read [BUILDING.md](BUILDING.md)

Tutorials
==========
 * [Getting Started With J2V8](https://eclipsesource.com/blogs/tutorials/getting-started-with-j2v8/)
 * [Registering Java Callbacks with J2V8](http://eclipsesource.com/blogs/2015/06/06/registering-java-callbacks-with-j2v8/)
 * [Implementing WebWorkers with J2V8](http://eclipsesource.com/blogs/2015/05/28/implementing-webworkers-with-j2v8/)
 * [Multithreaded JavaScript with J2V8](http://eclipsesource.com/blogs/2015/05/12/multithreaded-javascript-with-j2v8/)
 * [Using J2V8 with Heroku](http://eclipsesource.com/blogs/2015/06/04/using-j2v8-with-heroku/)

Articles
========
 * [Announcing J2V8 4](http://eclipsesource.com/blogs/2016/07/20/announcing-j2v8-4/)
 * [Running Node.js on the JVM](http://eclipsesource.com/blogs/2016/07/20/running-node-js-on-the-jvm/)
 * [Shipping J2V8 as an AAR](http://eclipsesource.com/blogs/2015/11/04/shipping-j2v8-as-an-aar/)
 * [Announcing J2V8 3.0](http://eclipsesource.com/blogs/2015/07/08/j2v8-3-0-released/)
 * [J2V8 2.2 New and Noteworthy](http://eclipsesource.com/blogs/2015/04/23/j2v8-2-2-new-and-noteworthy/)
 * [Announcing J2V8 2.0](http://eclipsesource.com/blogs/2015/02/25/announcing-j2v8-2-0/)
 * [Highly Efficient Java & JavaScript Integration](http://eclipsesource.com/blogs/2014/11/17/highly-efficient-java-javascript-integration/)
 * [React.js SSR with J2V8](https://ebaytech.berlin/react-js-server-side-rendering-with-j2v8-b9ced07888fb)

Presentations
=============
 * [J2V8 A Highly Efficient JS Runtime For Java](https://www.eclipsecon.org/na2015/session/j2v8-highly-efficient-js-runtime-java)
 * [Running JavaScript Efficiently in a Java World](http://www.slideshare.net/irbull/enter-js)

Other Resources
===============
Here is a list of articles I've written on J2V8 [http://eclipsesource.com/blogs/tag/j2v8/](http://eclipsesource.com/blogs/tag/j2v8/).

Who is using J2V8?
========

Here are some projects that use J2V8:
* [tabris.js](https://tabrisjs.com)
* [tern.java](https://github.com/angelozerr/tern.java)
* [PlantUML](http://plantuml.com/)
* [jooby](http://jooby.org/doc/assets)
* [Alicorn](http://alicorn.io)

License
=====
The code is published under the terms of the [Eclipse Public License, version 1.0](http://www.eclipse.org/legal/epl-v10.html).
