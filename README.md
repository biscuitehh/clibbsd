# ClibBSD

C module map for libBSD

## How to build

### Linux

Install `libbsd-dev` using `apt-get`

`$ sudo apt-get install libbsd-dev`

## Example

```
#if os(Linux)
	import ClibBSD
#endif

let random = arc4random()
print("arc4random: \(random)")
```