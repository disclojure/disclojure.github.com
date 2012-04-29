---
layout: post
title: TCO for Clojure, Equality in Emacs, Python-py using IFn,
 sneaky-throws, and ClojureWerkz.org is up!
intertweets: 
-
 tweet: >
  I just posted the code for Dan Friedman's and my work on Clojure TCO here
 author: long_way_down
 url: https://github.com/cjfrisz/clojure-tco
 comment: >
  This is a library that provides optimized tail calls to Clojure
  without having to call 'recur'. It's a source-to-source compiler and
  for now it only supports a small subset of Clojure. There is also a
  [blog post](http://www.chrisfrisz.com/blog/?p=220) with more details
  and the video of a recent presentation of this project.
-
 tweet: >
  In which we plot an escape from the quagmire of equality (Clojure and Emacs)
 author: Exotz
 url: http://technomancy.us/159
 comment: >
  An interesting discussion about Emacs Lisp, being based on
  mutability, makes things like equality very hard, and what are the
  possible solutions (none of them easy)
-
 tweet: >
  This is a good read, Clojure's IFn vs. Python's __call__ 
 author: swannodette
 url: http://clojure-py.blogspot.com/2012/04/ifn-vs-call.html
 comment: >
  It's easy to see where the writer of the article is going when the
  article starts with "Those who don't understand the work of Rich
  Hickey are doomed to reinvent it, poorly". And indeed, the author of
  clojure-py initially implemented functions differently than
  Clojure-jvm because Python has a way of making objects callable,
  which Java does't provide. Well, it turns out that using 
  IFn (which is used in Clojure-jvm) not only makes the compiler code
  simpler, it also makes it faster.
-
 tweet: >
  Sneakily throwing checked exceptions
 author: philandstuff
 url: http://rhebus.posterous.com/sneakily-throwing-checked-exceptions
 comment: >
  It used to be that in Clojure [checked exceptions would be turned
  into RuntimeExceptions](http://dev.clojure.org/jira/browse/CLJ-855),
  and thus information was lost. This is not the case anymore in 1.4,
  and this article explains the implementation of sneaky-throws, used
  in 1.4 for this purpose.
-
 tweet: >
  Our site is finally up! clojurewerks.org
 author: ClojureWerkz
 url: http://clojurewerkz.org/
 comment: >
  The guys at ClojureWerkz have been producing new Clojure libraries
  at a high pace. You can now find them all in one single place.
---

