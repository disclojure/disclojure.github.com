---
layout: post
title: URL lib, parallel core.logic, the cljs compiler deconstructed,
 learning clojure, and cljs-clj bi-di comm via http.
intertweets:
-
 tweet: >
  Urly, our #clojure library that unifies URL/URI parsing and
  manipulation, got many improvements recently 
 author: ClojureWerkz
 url: https://github.com/michaelklishin/urly/blob/master/ChangeLog.md
 comment: >
  Deals with relative URLs, something that the Java counterpart
  doesn't do.
-
 tweet: >
  Parallel logic programming
 author: jimduey
 url: http://www.clojure.net/2012/03/26/Messin-with-core.logic/
 comment: >
  Make core.logic scale to multiple processors via Java 7's fork-join
  parallel programming facilities.
-
 tweet: >
  Emblogginated: "Compiling Clojure to JavaScript, pt. 3 - The Himera
  Model" 
 author: fogus
 url: http://blog.fogus.me/2012/03/27/compiling-clojure-to-javascript-pt-3-the-himera-model/
 comment: >
  If you deconstruct a compiler you end up with a bunch of modules
  organized in a pipeline. Who cares where these modules are executed,
  rigth? They could be anywhere. They could be in the cloud! So here,
  Himera, provides compilation as a service. But in all reality, you
  can do a lot more with it. There is even a [podcaset
  interview](http://thinkrelevance.com/blog/2012/03/28/thinkrelevance-the-podcast-episode-008-michael-fogus)
  for this event.
-
 tweet: >
  The Newbie's Guide to Learning Clojure
 author: hnfirehose
 url: http://www.elangocheran.com/blog/2012/03/the-newbies-guide-learning-clojure/
 comment: >
  Every now and then we get a blog post with the latest and greatest
  resources for learning Clojure. This is the latest of these blog
  posts. Keep them coming -- every 6 months or so.
-
 tweet: >
  Lazy-seqs From Database With Clojure Korma
 author: paulosuzart
 url: http://paulosuzart.github.com/blog/2012/03/27/lazy-seqs-from-database-with-clojure-korma/
 comment: >
  Migrate 900K db entries from MySQL to Postgress with Korma, a few
  minutes of coding, and lazy sequences. 
-
 tweet: >
  Released: clj-browserchannel-demo - cross-browser, bi-directional
  communication in #clojurescript & #clojure app 
 author: thegeez
 url: https://github.com/thegeez/clj-browserchannel-demo
 comment: >
  Cross browser, bi-directional communication between ClojureScript
  and Clojure with
  [BrowserChannel](http://closure-library.googlecode.com/svn-history/r144/docs/closure_goog_net_browserchannel.js.html).
  "A BrowserChannel simulates a bidirectional socket over HTTP. It is
  the basis of the Gmail Chat IM connections to the server".  
---