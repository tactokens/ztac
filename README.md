# wasm-bellman-circuit

Here is workspace to build the circuit for anonymous transactions for tac and js bindings.

* ztac_primitives - crate for utils and crypto function
* ztac_circuit - crate for circuits
* ztac_wasm - crate for wasm bindings
* js - example, how to use js bindings

First, we need to install the dependencies (`cargo` and `npm` should be already installed):

```
cargo install wasm-pack
cd js && npm install
```

To run tests

```bash
cargo test
```


To build

``` bash
wasm-pack build ztac_wasm
``` 


To view web page with wasm in browser.

```
cd js && npm run start
```
