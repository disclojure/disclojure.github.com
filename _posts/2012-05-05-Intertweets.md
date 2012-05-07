---
layout: post
title: NS browser, Robot DSL, nREPL over HTTP, contention in
 multimethods, and poor performance of Clojure in Hacker News
intertweets:
-
 tweet: >
  The "It starts to look like a real App" release, 1.2.0, of the
  Clojure Namespace Browser (clj-ns-browser)  
 author: fs42 
 url: https://github.com/franks42/clj-ns-browser
 comment: >
  Clojure-ns-browser is a nice way to explore Clojure and all the
  clojure libraries. It let's you quickly jump from documentation, to
  sources and to usage examples. It is a
  [Swing](http://en.wikipedia.org/wiki/Swing_(Java)) application built 
  with [Seesaw](https://github.com/daveray/seesaw)
-
 tweet: >
  Clojure Robot DSL
 author: ajlopez
 url: http://david-mcneil.com/post/17044248397/clojure-robot-dsl
 comment: >
  Ah, nice! A DSL for building Robot controlling software to control
  [Lego Mindstorms](http://mindstorms.lego.com/en-us/Default.aspx) and
  [Arduino](http://www.arduino.cc/) robots. Clojure already controls the
  server, 
  the broswer, the client... now Robots. This is one seriosly cool DSL
  that generates code that can be understood by the cited platforms.
-
 tweet: >
  Debug Clojure Web Apps over HTTP
 author: hnfirehose
 url: https://devcenter.heroku.com/articles/debugging-clojure
 comment: >
  This article describes how to REPL-in to remotely running services
  where direct TCP connections are not possible, or more speficically,
  Heroku. Using
  [drawbar](https://github.com/cemerick/drawbridge), a
  HTTP transport for [nRepl](https://github.com/clojure/tools.nrepl),
  you can open a REPL in an already runnign webapp. I have heard this
  technique has been used to fix satellites or other space ships.
  Probably not HTTP though.
-
 tweet: >
  This is what it looks like if you have a hot multimethod in
  multithreaded code. Red means waiting for a lock. 
 author: hiredman
 url: http://yfrog.com/kg2tikp
 comment: >
  As with hot peppers, red is not good news. And there is a lot of red
  in this picture. Contention!
-
 tweet: >
  Hackers love #python :-) (chart)
 author: andreas_io
 url: http://hntrends.jerodsanto.net/?q=ruby,+python,+haskell,+clojure,+scala
 comment: >
  This is a chart plotting the times Clojure appears in [Hacker
  News](http://news.ycombinator.com) (HN) posts, compared to Ruby, Python,
  Haskell and Scala. NHacker News is a place where entrepreneurs hang
  out. Two things seem clear from this graph: Clojure has taken quite a
  dive since mid-2010, and HN is talking less and less about
  programming in aggregate.
---
