---
layout: post
title: clj <-> cljs transorms, a repl everywhere, cljs couchDB views,
 and groovy using the STM
intertweets:
-
 tweet: >
  crazy awesome idea, use core.logic for bidirectional Clojure,
  ClojureScript source transformation
 author: swannodette
 url: https://github.com/jonase/kibit/pull/20
 comment: >
  "I'm putting together a tool that uses
  [kibit](https://github.com/jonase/kibit) for rewriting Clojure 
  code into ClojureScript". This is quite a promissing beggining for a
  github ticket...
-
 tweet: >
  Full featured browser based REPL interface to #Clojure app deployed
  on Heroku 
 author: zoka
 url: http://noirmon.herokuapp.com/ringmon/monview.html
 comment: >
  Give a try to this public instance of
  [RingMon](https://github.com/zoka/ringMon/): a ring middleware 
  that injects a page with a
  [nREPL](https://github.com/clojure/tools.nrepl) client to your
  application so you can access the REPL while the application is
  live. 
-
 tweet: >
  First release of clutch-clojurescript: use ClojureScript to write
  views for @CouchDB or @Cloudant
 author: cemerick
 url: https://github.com/clojure-clutch/clutch-clojurescript
 comment: >
  With [clutch](https://github.com/clojure-clutch/clutch) you are able
  to create CouchDB views with Clojure, 
  but doing so requires adding clojure and clutch to some init file in
  CouchDB. This is just not possible in hosted environments like
  [cloudant](http://cloudant.com). Since CouchDB has native support for JavaScript views,
  ClojureScript comes to the rescue providing a non-intrusive way of
  using clojure within CouchDB.
-
 tweet: >
  Jim Kirkwood has created a #groovy wrapper over #clojure #stm quite
  interesting 
 author: venkat_s
 url: https://github.com/ceenlrnjim/groovystm
 comment: >
  More uses of Clojure's STM, which seems to be a gateway drug to
  Clojure ;)
---
