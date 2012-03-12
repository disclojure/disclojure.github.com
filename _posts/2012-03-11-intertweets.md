---
layout: post
title: Event streams, Leiningen2 preview, Clojars crypto and music composition
intertweets:
-
 tweet: >
  Fuck, I may have to learn clojure now to embrace this awesomeness
 author: splittingfield
 url: http://aphyr.github.com/riemann/
 comment: >
  ... and this awesomeness is no other than Riemann, an event
  aggregator and visualizer for distributed systems, which includes a
  stream processing language.
-
 tweet: > 
  This is it, ladies and gents: Leiningen 2 preview1 is out
 author: technomancy
 url: https://groups.google.com/forum/?fromgroups#!topic/clojure/jRRR9JlppNQ
 comment: >
  The new Leiningen 2 is big improvement over lein 1, making it much
  more powerful, usable and embeddable than ever. I personally can't
  wait until I can ditch the last pom.xml file.
-
 tweet: >
  Do you maintain a Clojure library? If so please log into the Clojars
  web UI to re-hash your password 
 author: technomancy 
 url: https://groups.google.com/forum/?fromgroups#!topic/clojure/Xg1I0rgt85s
 comment: > 
  This is a PSA: Clojars has moved its password encription algorithm
  to to something safer (bcrypt) and is asking everyone to
  log in so that the password gets rehashed. The trigger for this
  change was the recent [leakage](https://gist.github.com/2001456) of
  [node.js npm repository](http://search.npmjs.org/)'s password hashes
  and salts. For node.js package authors this is pretty
  upsetting since their
  passwords can be cracked somewhat easily, given the weak crypto
  used by the repo. Notice that the old passwords in clojars will be
  deleted soon and you'll need to request a new if you don't log soon!
-
 tweet: >
  I'm working on a tool to help myself compose music, in Clojure. Check it out 
 author: dmansen
 url: https://github.com/dmansen/composition-assistant
 comment: >
  This must be useful in conjunction with [Overtone](http://overtone.github.com/)!
---

