---
layout: post
title: >
 ClojureScript+Noir template, Lamina rewrite, debuggers rejoice
 and @chouser at MostlyLazy
intertweets: 
-
 tweet: >
  by popular request, there is now a lein-newnew template for noir
  #ClojureScript projects
 author: ibdknox
 url: https://github.com/ibdknox/cljs-template
 comment: >
  With this lein plugin you can create the skeleton of a noir web
  application with all the necessary configuration to also compile
  ClojureScript, all bundled up.
-
 tweet: >
  wherein our heroes discuss the upcoming version of Lamina
 author: ztellman
 url: http://ideolalia.com/110624930
 comment: >
  Zach Tellman started a clean room implementation of the event
  processing library [lamina](https://github.com/ztellman/lamina) that
  is both cleaner and one and two orders of magnitude faster according
  to benchmarks. This speed comes at the cost of some changed
  semantics.
-
 tweet: >
  JVM (and Ruby) Language Popularity - Google, Tiobe, SO, GitHub"
 author: DZone
 url: http://java.dzone.com/articles/jvm-and-ruby-language
 comment: >
  These comparisons come almost every week, this time with somewhat of
  a twist:" When considering which JVM language (other than Java) to
  use, popularity can’t really be a factor. That’s good."
-
 tweet: >
  Huzzah! #Clojure gets disable-locals-clearing. Clojure debuggers
  everywhere rejoice! Thank you, @richhickey 
 author: 0x1B
 url: https://github.com/clojure/clojure/commit/4036c7720949cb21ccf53c5c7c54ed1daaff2fda
 comment: >
  The reason some people are so excited about this patch is that
  currently the Clojure compiler nulls locals when it determines they
  will no longer be used, and this is a problem for debuggers, as when
  debugging you might want to know what the value was for that local,
  long after it has been cleared. This patch in Clojure 1.4 will allow
  you to disable this clearing in the compiler.
-
 tweet: >
  Mostly λazy Episode 0.0.5: @chouser at Clojure Conj 2011
 author: cemerick
 url: http://mostlylazy.com/2012/03/13/episode-0-0-5-chris-houser-at-clojure-conj-2011/
 comment: >
  The beginnings of Clojure, macros for Scala, the original
  ClojureScript and more.
---
