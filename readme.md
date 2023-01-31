# xformers-compiled
_xformers compiled for specific graphics cards._

These wheels were build on and for Paperspace Gradient machines for use with [Engineer-of-Stuff/stable-diffusion-paperspace](https://github.com/Engineer-of-Stuff/stable-diffusion-paperspace).

Xformers was compiled without a few features to make the binary smaller and compile time shorter:
```
XFORMERS_DISABLE_FLASH_ATTN=1 NVCC_FLAGS="--use_fast_math -DXFORMERS_MEM_EFF_ATTENTION_DISABLE_BACKWARD"
```

If you get error messages talking about missing xformers modules, use the `full` version of the wheel located in the card's folder. 
### How to Use
1. Find your graphics card model (`nvidia-smi`).
2. Get the link from the table for the correct file.
3. Do `pip install <url of .whl file>`


There are also files are in the Releases section (older versions).
