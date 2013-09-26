Web Toolbox
===================

### Task Runners

* [grunt](http://gruntjs.com/) - JavaScript task runner

### Troubleshooting

* [node-inspector](https://npmjs.org/package/node-inspector) - Web Inspector based node debuggger
  ```node --debug your/node/program.js```

### Node Modules

* [nomnom](https://npmjs.org/package/nomnom) - Option parser with generated usage and commands
* [browserify](https://npmjs.org/package/browserify) - Browser side require() the node way

### Data Structures

* [Stream.js](http://streamjs.org/) - lazily evaluated data structure similar to arrays and linked lists that can contain infinite items.
* [RBush](https://github.com/mourner/rbush) -  a high-performance JavaScript library for 2D spatial indexing of points and rectangles, based on an optimized R-tree data structure with bulk insertion support.
* [D3 Queue](https://github.com/mbostock/queue) - Asynchronous helper library for JavaScript

### JavaScript

* [Functional.js](http://osteele.com/sources/javascript/functional/) - A library for functional programming in JavaScript
* [Chainvas.js](http://lea.verou.me/chainvas/) - Add chaining to any API

### UI

* [Pines Notify](http://pinesframework.org/pnotify) - JavaScript notifications for Bootstrap or jQuery UI.
* [toastr](https://github.com/CodeSeven/toastr) - Javascript library for non-blocking notifications. jQuery is required.
* [alertify.js](http://fabien-d.github.io/alertify.js/) - Javascript dialogs and alerts.
* [Ace Web Code Editor](http://ace.c9.io/)

### UI Effects

* [Effeckt](https://github.com/h5bp/Effeckt.css) - UI-less, performant transitions & animations
* [Nifty Modal Window Effects](http://tympanus.net/Development/ModalWindowEffects/)
* [Page Transitions](http://tympanus.net/Development/PageTransitions/)
* [PFold](http://tympanus.net/Development/PFold/index2.html) - Paper like unfolding effect
* [Kontext](http://lab.hakim.se/kontext/) - Context switch transition
* [cubi-bezier generator](http://cubic-bezier.com/)

### Style Guides

* [Github CSS Styleguide](https://github.com/styleguide/css)
* [Bootstrap HTML and CSS code guide](https://github.com/mdo/code-guide)

### Maps

* [Leaflet Marker Cluster](https://github.com/Leaflet/Leaflet.markercluster)
* [Leaflet Marker Spiderfier](https://github.com/jawj/OverlappingMarkerSpiderfier-Leaflet) - Spiderify overlapping markers in leaflet

### Curl

Post data
```
curl -X POST -d 'foo=foo&bar=bar' localhost:8080
```

Post JSON
```
curl -X POST -d '{ "foo": "foo", "bar": "bar" }' -H 'Content-Type: application/json' localhost:8080
```
