# Lowest Common Ancestor Test

## Setup

Clone this repo and open index.html in any browser. Or visit
http://natehunzaker.com/contains-bench and do the same.

## Findings

### Chrome 49

```
Depth method x 3,088,855 ops/sec ±3.50% (56 runs sampled)
Contains method x 3,295,131 ops/sec ±0.95% (58 runs sampled)
Fastest is Contains method
```

### Safari 9

```
Depth method x 1,940,537 ops/sec ±8.66% (31 runs sampled) (index.html, line 82)
Contains method x 3,980,743 ops/sec ±8.51% (33 runs sampled) (index.html, line 82)
Fastest is Contains method (index.html, line 86)
```

### Firefox 45

```
Depth method x 1,875,566 ops/sec ±1.19% (61 runs sampled)
Contains method x 5,839,094 ops/sec ±0.96% (58 runs sampled)
Fastest is Contains method
```
