# front-end-system-design

A checklist for front end system design

* Requirements
    * How many users?
    * Where are users distributed?
    * What is our frame budget?
    * Do we need to support mobile?
    * Offline support?
    * Internationalization?
    * Accessibility?
    * Browser targets?
* Architecture
    * MVC
    * MVW
    * Container/Component Architecture
* Data Flow Model
    * Two Way Data Binding vs Unidirectional data flow
* Component Tree
* Design
* System Walkthrough
* Performance Patterns
    * Fast initial load time
        * App shell architecture
        * SSR
        * Caching
        * Rehydrate application state from prev. cached state
    * Assets
        * Route based code splitting
        * Minification
        * Dead code stripping
    * Network
        * Lazy vs eager loading
        * Service Worker
        * Caching API requests
    * Compute
        * WebGL
        * WebAssembly
        * WebWorkers
        * SharedArrayBuffer
    * UI
        * Optimistic UI
        * Virtual List
* Examples
    * Design a facebook messenger client
    * Design a gigapixel client
    * Design the uber client
    * Design the twitter newsfeed
    * Design the google docs client
    * Design a performance dashboard for a client side app
* Readings
    * [Facebook BigPipe](https://www.facebook.com/notes/facebook-engineering/bigpipe-pipelining-web-pages-for-high-performance/389414033919/)
    * [Making slack faster by being lazy](https://slack.engineering/making-slack-faster-by-being-lazy-88da4481baa7)
    * [Design an Image hosting platform](http://www.aosabook.org/en/distsys.html)
