# Learning WebAssembly

Resources about WebAssembly programming and ecosystem.

## Resources

### Introduction

- [WebAssembly](https://webassembly.org/)
- [The world’s easiest introduction to WebAssembly](https://medium.com/free-code-camp/webassembly-with-golang-is-fun-b243c0e34f02)
- [What is WebAssembly? The next-generation web platform explained](https://www.infoworld.com/article/3291780/what-is-webassembly-the-next-generation-web-platform-explained.html)
- [WebAssembly SF: WebAssembly's post-MVP Future](https://www.youtube.com/watch?v=VsYL4Z9sRec)
- [WebAssembly Reference Manual](https://github.com/sunfishcode/wasm-reference-manual/blob/master/WebAssembly.md)
- [WebAssembly Is Fast: A Real-World Benchmark of WebAssembly vs. ES6](https://medium.com/@torch2424/webassembly-is-fast-a-real-world-benchmark-of-webassembly-vs-es6-d85a23f8e193)
- [Awesome Wasm Languages](https://github.com/appcypher/awesome-wasm-langs) A curated list of languages that compile directly to or have their VMs in WebAssembly
- [Lys](https://lys-lang.dev/) A language that compiles to WebAssembly
- [What’s next for WebAssembly portable code](https://www.infoworld.com/article/3217704/whats-new-with-webassembly-portable-code.html)
- [8 projects that give WebAssembly a lift](https://www.infoworld.com/article/3139400/8-projects-that-give-webassembly-a-lift.html)
- [WebAssembly Weekly](https://wasmweekly.news/)
- [Is WebAssembly the Web GUI Future?](https://insights.dice.com/2019/02/28/webassembly-web-gui-future/)
- [Benchmarking WebAssembly Runtimes](https://medium.com/wasmer/benchmarking-webassembly-runtimes-18497ce0d76e)


### Tutorials

- [Programming using Web Assembly](https://medium.com/@alexc73/programming-using-web-assembly-c4c73a4e09a9) Drawing pixel graphics on an HTML canvas
- [WebAssembly for Javascript Developers, by Aaron Turner](https://www.youtube.com/watch?v=ZlL1nduatZQ)
- [Loading and running WebAssembly code](https://developer.mozilla.org/en-US/docs/WebAssembly/Loading_and_running)
- [WebAssembly Troubles part 1: WebAssembly Is Not a Stack Machine](http://troubles.md/posts/wasm-is-not-a-stack-machine/)
- [WebAssembly Troubles part 2: Why Do We Need the Relooper Algorithm, Again?](http://troubles.md/posts/why-do-we-need-the-relooper-algorithm-again/)
- [WebAssembly Troubles part 3: What About Alloca?](http://troubles.md/posts/the-stack-is-not-the-stack/)
- [WebAssembly Troubles part 4: Microwasm](http://troubles.md/posts/microwasm/)

### Compiling WebAssembly

- [A WebAssembly Compiler tale](https://medium.com/wasmer/a-webassembly-compiler-tale-9ef37aa3b537)How we abstracted our API to be independent of the IR, allowing Wasmer to support multiple compiler backends
- [Wag](https://github.com/tsavola/wag) WebAssembly compiler implemented in Go
- [Solving the structured control flow problem once and for all](https://medium.com/leaningtech/solving-the-structured-control-flow-problem-once-and-for-all-5123117b1ee2) Cheerp, a C++ to JavaScript and WebAssembly compiler based on LLVM

### WebAssembly and LLVM

- [LLVM 8 shines on WebAssembly, machine learning workloads](https://www.infoworld.com/article/3376156/llvm-8-shines-on-webassembly-machine-learning-workloads.html)

### WebAssembly and Go

- [Learning Golang through WebAssembly - Part 1, Introduction and setup](https://www.aaron-powell.com/posts/2019-02-04-golang-wasm-1-introduction/)
- [Learning Golang through WebAssembly - Part 2, Writing your first piece of Go](https://www.aaron-powell.com/posts/2019-02-05-golang-wasm-2-writing-go/)
- [Learning Golang through WebAssembly - Part 3, Interacting with JavaScript from Go](https://www.aaron-powell.com/posts/2019-02-06-golang-wasm-3-interacting-with-js-from-go/)
- [Learning Golang through WebAssembly - Part 4, Sending a Response to JavaScript](https://www.aaron-powell.com/posts/2019-02-07-golang-wasm-4-response-to-javascript/)
- [Learning Golang through WebAssembly - Part 5, Compiling With Webpack](https://www.aaron-powell.com/posts/2019-02-08-golang-wasm-5-compiling-with-webpack/)
- [Learning Golang through WebAssembly - Part 6, Go, WASM, TypeScript and React](https://www.aaron-powell.com/posts/2019-02-12-golang-wasm-6-typescript-react/)

### WebAssembly and Rust

- [WebAssembly and Rust: A Web Love Story](https://github.com/raphamorim/wasm-and-rust)
- [Learn Rust and WebAssembly](Learn Rust and WebAssembly)
- [Yew: Rust framework for building client web apps](https://github.com/DenisKolodin/yew)
- [This Week in Rust and WebAssembly 11](https://rustwasm.github.io/2019/02/21/this-week-in-rust-and-wasm-011.html)
- [Plasma gets Rust-y: Another WebAssembly Experiment](https://dev.to/jeremylikness/plasma-gets-rust-y-another-webassembly-experiment-10d2) Building a plasma canvas effect using Wasm compiled from Rust
- [A Rust + WebAssembly Pitch Detector](https://alesgenova.github.io/pitch-detection-app/)
- [Compiler Explorer](https://rust.godbolt.org/)
- [Woz](https://woz.sh/) Woz is a WebAssembly progressive web app (PWA) toolchain for building and deploying performant mobile apps with Rust

### WebAssembly and C/C++

- [Cheerp 2.0 released — the most powerful Cheerp yet](https://medium.com/leaningtech/cheerp-2-0-release-880f249a5677) C/C++ to WebAssembly/JavaScript compiler
- [Compiling C to WebAssembly using clang/LLVM and WASI](https://00f.net/2019/04/07/compiling-to-webassembly-with-llvm-and-clang/)

### Online Demos

- [wat2wasm demo](https://webassembly.github.io/wabt/demo/wat2wasm/)
- [WebAssembly F# Compiler](https://tryfsharp.fsbolero.io/)

### Tools

- [Mozilla Extends WebAssembly Beyond the Browser with WASI](https://thenewstack.io/mozilla-extends-webassembly-beyond-the-browser-with-wasi/)
- [Mozilla tries to do Java as it should have been – with a WASI spec for all devices, computers, operating systems](https://www.theregister.co.uk/2019/03/29/mozilla_wasi_spec/) One binary to rule them all
- [npm and WASM: how can we help?, Laurie Voss of npm](https://www.youtube.com/watch?v=iRV4VemBMzc)
- [Standardizing WASI: A system interface to run WebAssembly outside the web](https://hacks.mozilla.org/2019/03/standardizing-wasi-a-webassembly-system-interface/)
- [Announcing Lucet: Fastly’s native WebAssembly compiler and runtime](https://www.fastly.com/blog/announcing-lucet-fastly-native-webassembly-compiler-runtime)
- [WebAssembly Terminal User Interface (TUI) debugger](https://github.com/Sable/wabt-debugger-tui)
- [CT-Wasm: Type-Driven Secure Cryptography for the Web Ecosystem](https://arxiv.org/abs/1808.01348)
- [Perspective](https://perspective.finos.org/) Streaming Analytics via WebAssembly
- [K framework and WebAssembly ⇒ KWasm](https://www.youtube.com/watch?v=V6tOYuneMqo)
- [Lucet](https://gist.github.com/jedisct1/8ce91d746e09c913ee0d0f33b0ba7981)Run WebAssembly files like standard executable files on Linux, using Lucet

### Examples

- [How We Used WebAssembly To Speed Up Our Web App By 20X (Case Study)](https://www.smashingmagazine.com/2019/04/webassembly-speed-web-app/)
- [Replacing a hot path in your app's JavaScript with WebAssembly](https://developers.google.com/web/updates/2019/02/hotpath-with-wasm)
- [Using AlchemyVM to create a simple Tic-Tac-Toe game](https://medium.com/@elixiumnetwork/using-waspvm-to-create-a-simple-tic-tac-toe-game-a993ca9d6289)
- [How to build a crypto isomorphic library with Javascript and WebAssembly](https://medium.com/cubbit/how-to-build-a-crypto-isomorphic-library-with-javascript-and-webassembly-6fc7aa708437)
- [php-ext-wasm: Migrating from wasmi to Wasmer](https://medium.com/wasmer/php-ext-wasm-migrating-from-wasmi-to-wasmer-4d1014f41c88)
- [Porting Games to the Web with WebAssembly](https://medium.com/@robaboukhalil/porting-games-to-the-web-with-webassembly-70d598e1a3ec) How to port an Asteroids game from C to WebAssembly
- [Benchmarking WebAssembly using libsodium](https://00f.net/2019/04/09/benchmarking-webassembly-using-libsodium/)

### WebAssembly and Blockchain

- [Wasm on the Blockchain: The Lesser Evil](http://troubles.md/posts/why-wasm/)
- [Ewasm Gas Cost](https://ewasm.readthedocs.io/en/mkdocs/determining_wasm_gas_costs/)
- [The Explosive Implications of Tron’s Move to WebAssembly](https://u.today/the-explosive-implications-of-trons-move-to-webassembly)
- [Some Ewasm Updates](https://drive.google.com/file/d/1CRc0qBQTebNKw7NRZXzxbHovrigW0bqf/view)

### To Review

https://speed.wasmer.io/
