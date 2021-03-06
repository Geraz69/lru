# LRU

[![Build Status](https://secure.travis-ci.org/jehiah/lru.png?branch=master)](http://travis-ci.org/jehiah/lru)


`LRU` is a Go library for caching arbitrary data with least-recently-used (LRU) eviction strategy and TTL support. There is also a `LRUCounter` which allows you to easily to count high cardinality lists while keeping a bounded set in memory.

Inspired by LRU code from  [larsmans](https://gist.github.com/larsmans/4638795) and [vitess](https://code.google.com/p/vitess/source/browse/go/cache/lru_cache.go)

Docs: https://godoc.org/github.com/jehiah/lru
