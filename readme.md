# xformers-compiled
_xformers compiled for specific graphics cards._

These wheels were build on and for Paperspace Gradient machines.

### How to Use
1. Find your graphics card model (`nvidia-smi`).
2. Get the link from the table for the correct file.
3. Do `pip install <url of .whl file>`

### Files
|GPU Model|URL|
|-|-|
|A4000|`https://github.com/Cyberes/xformers-compiled/releases/download/A4000-Oct-28-2022/paperspce-a4000-xformers-0.0.14.dev0-cp39-cp39-linux_x86_64.whl`<br />The `/a4000` directory is left for backwards compatibility.|
|P5000|`https://raw.githubusercontent.com/Cyberes/xformers-compiled/main/P5000/xformers-0.0.14.dev0-cp39-cp39-linux_x86_64.whl`|
|RTX 4000|`https://raw.githubusercontent.com/Cyberes/xformers-compiled/main/RTX%204000/xformers-0.0.14.dev0-cp39-cp39-linux_x86_64.whl`|
|RTX 5000|`https://raw.githubusercontent.com/Cyberes/xformers-compiled/main/RTX%205000/xformers-0.0.14.dev0-cp39-cp39-linux_x86_64.whl`|
