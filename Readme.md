
# Multithreaded Rust Webserver

This was a simple implementation of a multithreaded webserver using just the rust standard library.

It implements a couple basic components of a webserver such as 
- A connection handler
- A thread pool
- Threads disconnected on server termination
- Workers that wait to receive jobs



## Run Locally

Clone the project

```bash
  https://github.com/jk1551/rust-webserver
```

Go to the project directory

```bash
  cd rust-webserver
```

Start the server

```bash
  cargo run
```

View a page

```bash
  http://localhost:7878
```
