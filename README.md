# Writing algorithms in Rust and using them in Node.js

This code is based on Second State's tutorials. You can find detailed instructions here: https://www.secondstate.io/articles/getting-started-with-rust-function/

Currently two algorithms are implemented, checking whether a number is prime and getting nth Fibonacci term. 

## Comparing performance via a web interface

This is not intended to be a truly scientific test of performance, but you can compare the Rust algorithm with its equivalent Javascript version by calling them via the web interface.(uses JQuery to make AJAX requests to the Node.js Express server) The benchmark makes use of Node.js's performance hooks: https://nodejs.org/api/perf_hooks.html, rounded to two decimal places.
Example:![Web interface example](./benchmark.png?raw=true "Screenshot")

## Algorithms 

- [x] Checking primality
- [x] Getting nth Fibonacci term
- [ ] Factorial
- [ ] Array sort
- [ ] String manipulation/parsing
- [ ] Nested JSON parsing