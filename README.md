# cuda

Docker images with CUDA

Available versions:
```
FROM shvid/cuda:11.0-cudnn8-devel-cp36-ubuntu18.04
FROM shvid/cuda:10.2-devel-cp36-ubuntu18.04
FROM shvid/cuda:10.2-runtime-cp36-ubuntu18.04
```

# Run

```
docker run -it --rm --runtime=nvidia shvid/cuda:11.0-cudnn8-devel-cp36-ubuntu18.04 nvidia-smi
docker run -it --rm --runtime=nvidia shvid/cuda:10.2-devel-cp36-ubuntu18.04 nvidia-smi
docker run -it --rm --runtime=nvidia shvid/cuda:10.2-runtime-cp36-ubuntu18.04 nvidia-smi
```
