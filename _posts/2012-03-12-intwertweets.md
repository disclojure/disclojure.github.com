---
layout: post
title: Clojure compiled to Scheme compiled to binary, and calling
 Clojure from Java
intertweets:
-
 tweet: > 
  thanks to @takeoutweight's minor mods of the ClojureScript compiler
  we can now compile Clojure to Scheme and then to C. 
 author: swannodette
 url: https://github.com/takeoutweight/clojure-scheme
 comment: > 
  This is a fork of the ClojureScript compiler that generates Scheme
  that can later be compiled to binary. In the supplied example,
  fibonacci, this binary is already faster than clojure, and that's
  not even counting the clojure startup time! 
-
 tweet: >
  Clojure’s Java interop in Java
 author: yueliufeeds
 url: http://blog.japila.pl/2012/03/clojures-java-interop-in-java/
 comment: >
  It is sometimes hard to find examples for calling Clojure code from
  Java, so thanks!
---