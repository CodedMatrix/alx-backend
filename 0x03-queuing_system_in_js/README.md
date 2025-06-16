# Queueing System In JavaScript

This project contains tasks for learning to create a queueing system in JavaScript.

## Tasks To Complete

+ [x] 0. **Install a redis instance**
  + Download, extract, and compile the latest stable Redis version (higher than 5.0.7 - [https://redis.io/download](https://redis.io/download)):
    ```powershell
    wget http://download.redis.io/releases/redis-6.0.10.tar.gz
    tar xzf redis-6.0.10.tar.gz
    cd redis-6.0.10
    make MALLOC=libc # for Linux systems
    # make MALLOC=jemalloc # for Mac OS X systems
    