# Pacificera's notes on implementing mlperf

## Target
My worksation is an amd AMD Ryzen 9 3900X (24) @ 4.000GHz with a Nvidia rtx2700 super with 8GB of vram.

## Image segmentation
Tried this out and stopped with the following cuda memory error from pytorch:
`RuntimeError: CUDA out of memory. Tried to allocate 1024.00 MiB (GPU 0; 7.77 GiB total capacity; 5.95 GiB already allocated; 103.06 MiB free; 6.02 GiB reserved in total by PyTorch)`

