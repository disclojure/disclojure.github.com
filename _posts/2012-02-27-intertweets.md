---
layout: post
title: Solr, LLVM, Distributed memoize, futuristic IDE in cljs, aaaand, Datomic!
intertweets:
-
 tweet: >
  0.1a (first) release of Icarus, Solr API for Clojure. Simple
  expression of complex queries, query composition, etc. 
 author: matt_deboard
 url: https://github.com/mattdeboard/Icarus
 comment: >
  [Apache Solr](http://lucene.apache.org/solr/) is a search engine
  built on top of [Apache Lucene](http://lucene.apache.org), an
  indexing and search library. This clojure wrapper lets you build
  queries 'the clojure way'.
-
 tweet: LLVM Clojure Bindings
 author: HNTweets
 url: https://github.com/jasonjckn/llvm-clojure-bindings
 comment: >
  Jason Jackson is experimenting with Clojure and
  [llvm](http://llvm.org/), a "is a collection of modular and reusable
  compiler and toolchain technologies". Currently compiling a toy
  language with Clojure, generating an llvm-based executable... first
  step from dynamic calls to C code? Clojure-llvm?!?!
-
 tweet: Distributed caching and memoization with Immutant
 author: jcrossley3
 url: http://immutant.org/news/2012/02/27/caching/
 comment: >
  [Immutant](http://immutant.org) is an application server for Clojure
  apps build on top of [JBoss AS7](http://www.jboss.org/as7). JBoss
  AS7 comes with [Infinispan](http://www.jboss.org/infinispan), a
  distributed data grid. This article is about using this data grid to
  perform caching and memoization in clojure. 
-
 tweet: >
  I built a #ClojureScript implementation of Bret Victor's
  (@worrydream) live-editable game. :D 
 author: ibdknox
 url:
  http://www.chris-granger.com/2012/02/26/connecting-to-your-creation/ 
 comment: >
  A few days ago this talk, [Inventing on
  Principle](http://vimeo.com/36579366), came out. Part of 
  the talk discussed futuristic development environments.
  Inspired by this, Chris Granger created one of such environments in
  ClojureScript. Since I can't really describe it, you should just go
  ahead and watch the video, making sure you have something soft under
  your jaw, as it'll drop. Hard. 
-
 tweet: Datomic
 author: richhickey
 url: 
 comment: >
  And with this tweet, and [this other one](https://twitter.com/#!/richhickey/status/174307533043937280),
  Rich Hickey is taking a page of Steve Jobs's book and creating tons
  of expectation: we know he
  is going to announce something at
  [Clojure/West](http://clojurewest.org) in less than 3 weeks, and now
  he drops this bomb. People quickly found [this](http://datomic.com),
  and later @da5ids did some research and [look at what he
  found!](https://skitch.com/tbatchelli/8fm34/http-tess2.uspto.gov-bin-showfield-f-docandstate-4010-ckutar.2.1).
  So now we have reasons to believe that "datomic" is some online
  database as a service.
---