# Rust UDP Server
Simple Rust UDP Server

## Usage

### Listen

```
$ cargo run
     Running `target/debug/rust-udp-server`
================================================================================
buffer size: 146
src address: 127.0.0.1:59489
request message: "You will never be happy if you continue to search for what happiness consists of. You will never live if you are looking for the meaning of life.\n"
================================================================================
buffer size: 55
src address: 127.0.0.1:59489
request message: "Man is the only creature who refuses to be what he is.\n"
================================================================================
buffer size: 68
src address: 127.0.0.1:59489
request message: "But in the end one needs more courage to live than to kill himself.\n"
```

### Send
```
$ nc -u 127.0.0.1 34254
You will never be happy if you continue to search for what happiness consists of. You will never live if you are looking for the meaning of life.
Man is the only creature who refuses to be what he is.
But in the end one needs more courage to live than to kill himself.
```

