---
title: ""
---

future-app
==========

An android app built using clojureScript and React-native. An example of
react-native navigation based on
[cljs-react-navigation](https://github.com/seantempesta/cljs-react-navigation) a
library that unify all `cljs` `react-navigation` libraries under a shared code
base. Rigth now, ilt only includes `Reagent/Re-Frame.`

Dependencies
------------

 

Clojurescript

 

`[org.clojure/clojure "1.9.0-alpha16"]
[org.clojure/clojurescript "1.9.542"]
[cljs-react-navigation "0.1.0"]                            [binaryage/devtools
"0.9.2"]                            [reagent "0.6.1"]
`

`[re-frame "0.9.2"]`

 

Javascript

 

`"react-native": "0.42.0", `

`"react-navigation": "0.1.0"`

 

Plugins

 

`[lein-cljsbuild "1.1.4"]             `

`[lein-figwheel "0.5.10"]`

 
-

Do this first
-------------

 

Install all the `dependencies` needs by the project

`re-natal deps`

 

Run the project
---------------

 

For development :

`re-natal use-android-device avd|real|genymotion`

`re-natal use-figwheel`

`lein figwheel android`

 

Open another windows an run this command :

`re-natal run-android`

 

 

License
-------

Copyright © 2017 FIXME

Distributed under the Eclipse Public License either version 1.0 or (at your
option) any later version.
