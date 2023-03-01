

# Build info.

 - built using A100 80GB machine
 - **docker** image used for building `nvcr.io/nvidia/tensorrt:22.10-py3`
 - compiled for all cuda architectures.



# How to run using this:


if `demo.py` is a script which builds a tensorrt engine then do following to build it using plugins for optimization

```bash

LD_PRELOAD path/to/libnvinfer_plugin.so  python3 demo.py   args1 args2
```
