# xformers-compiled
_xformers compiled for specific graphics cards._

These wheels were build on and for Paperspace Gradient machines.

### How to Use
1. Find your graphics card model (`nvidia-smi`).
2. Get the link from the table for the correct file.
3. Do `pip install <url of .whl file>`

### Files

Go to [releases](https://github.com/Cyberes/xformers-compiled/releases) and pick the latest version for your card. Make sure to save the file as `xformers-0.0.14.dev0-cp37-cp37m-linux_x86_64.whl` or else pip will fail to install it.

|GPU Model|URL|
|-|-|
|Various other cards|`https://raw.githubusercontent.com/Cyberes/xformers-compiled/main/various/xformers-0.0.14.dev0-cp37-cp37m-linux_x86_64.whl`|
