# hello-quil

A Quil sketch designed to ... well, that part is up to you.
The base project has been created from [quil-cljs](https://github.com/quil/quil-templates) template.
Then the build process has been migrated from figwheel to shadow-cljs.

## Usage

Run `npx shadow-cljs watch app` in your terminal. Wait for a while until you see `[:app] Build completed.`. Open [localhost:3000](http://localhost:3000) in your browser.

You can use this while developing your sketch. Whenever you save your source files the browser will automatically refresh everything, providing you with quick feedback. For more information about Figwheel, check the [Figwheel repository on GitHub](https://github.com/bhauman/lein-figwheel).

## Publishing your sketch

Before you publish your sketch, run `npx shadow-cljs release app`. This will compile your code and run Google Closure Compiler with advanced optimizations. Take `resources/public/index.html` and `resources/public/js/main.js` and upload them to server of your choice.

## License

Copyright © 2023 FIXME

Distributed under the Eclipse Public License either version 1.0 or (at
your option) any later version.
