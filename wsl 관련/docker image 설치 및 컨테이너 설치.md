
docker pull tensorflow/tensorflow:2.9.0-gpu

```
docker run --volume /mnt/h/ubuntu_project:/Project --name tf_gpu_290 --gpus all -d -p 8888:8888 tensorflow/tensorflow:2.9.0-gpu
```

docker run --volume /mnt/h/ubuntu_project:/Project --name tf_gpu_290 --gpus all -d -t tensorflow/tensorflow:2.9.0-gpu

-t 옵션이 중요(안꺼지게)