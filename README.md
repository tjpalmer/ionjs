Why?
- I often care about web dev.
- I can technically already compile ion to c to asmjs/wasm.
- But sometimes just plain js is better.

The intent is not to go to asmjs but rather to individually allocate array
buffers on `malloc`, and `free` is a no op.
Maybe can even optimize to plain objects in some cases.
