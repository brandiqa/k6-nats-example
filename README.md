# k6-nats-example

## Build

To build a `k6` binary with this extension, first ensure you have the prerequisites:

- [Go toolchain](https://go101.org/article/go-toolchain.html)
- Git

1. Install `xk6` framework for extending `k6`:

   ```shell
   go install go.k6.io/xk6/cmd/xk6@latest
   ```

2. Build the binary:

   ```shell
   xk6 build --with github.com/ydarias/xk6-nats@latest
   ```

## Run

Run a test

```shell
./k6 run folder/test.js
```
