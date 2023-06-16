# pico-redis

A tiny reimplentation of [Redis](https://redis.io/)

>**Note:** This is a very naive implementation, the database is just a non-sharded hashmap.

## Running the code

Make sure you have [Rust installed](https://rustup.rs/) and run:

```sh
$ cargo run
  ...
```

## Supported Commands

- [PING](https://redis.io/commands/ping/)
- [ECHO](https://redis.io/commands/echo/)
- [SET](https://redis.io/commands/set/)
- [GET](https://redis.io/commands/get/)

## Possible Future stuff

There's a lot of room for optimizations with stuff like [LSM-trees](https://en.wikipedia.org/wiki/Log-structured_merge-tree) but I don't yet have the time to learn how to implement them.
