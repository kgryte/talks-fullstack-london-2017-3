# WebAssembly and the Future of the Web

> Talk for [FullStack London (2017)][fullstack-london-2017].


## Abstract

WebAssembly, a new portable compilation target for the web, promises to radically change how we build web applications. In this talk, Athan will discuss how to leverage WebAssembly for high performance numeric computing in web browsers. He will first provide an overview of WebAssembly, current implementation status, and future roadmap. He will then show how to compile native C and C++ libraries to WebAssembly and how to include these libraries within web applications. Next, he will walk through a step-by-step example which involves compiling low-level BLAS libraries to WebAssembly for high-performance linear algebra and numeric computation. And finally, he will show how web applications using WebAssembly can achieve near native speed, thus ushering in a whole new era of high performance applications for data analysis, graphics, and data visualization.


## Installation

``` bash
$ git clone https://github.com/kgryte/talks-fullstack-london-2017-3
```

and

``` bash
$ npm install
```


## Usage

From the top-level directory,

``` bash
$ python -m SimpleHTTPServer 9000
```

and, in your browser, navigate to

```
http://127.0.0.1:9000
```


---

## Copyright

Copyright &copy; 2017. Athan Reines.


[fullstack-london-2017]: https://skillsmatter.com/conferences/8264-fullstack-2017-the-conference-on-javascript-node-and-internet-of-things
