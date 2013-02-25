# todo-cljs

A port of the JavaScript TODOs app to ClojureScript, copied from http://todomvc.com/vanilla-examples/vanillajs/

Includes the template and CSS by Sindre Sorhus

## Usage

```
$ lein deps
$ lein cljsbuild once
$ cd resources/public
$ python -m SimpleHTTPServer 8888
```

then open `http://0.0.0.0:8888/` in your browser to visit the application.

## License

Copyright © 2013 Denis Fuenzalida

Distributed under the Eclipse Public License, the same as Clojure.
