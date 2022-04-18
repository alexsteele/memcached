# Memcached

This is a forked version of memcached to complete the challenge described in
Arthur O'Dwyer's blog post https://quuxplusone.github.io/blog/2022/01/06/memcached-interview/

The challenge?

```
Add a mult command to memcached

Example

set age 0 2
38
STORED
mult age 2
76
```
## Results

It took me 29min 42sec to get a working version, including checkout, compilation, code changes, and testing.
I didn't add statistics, and I left a few TODOs. Oh, and I spelled the command "mul" instead
of "mult". "mult" is just too molty, you know?

