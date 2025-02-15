
docker pull tensorflow/tensorflow:2.9.0-gpu

```
docker run --volume /mnt/h/ubuntu_project:/Project --name tf_gpu_290 --gpus all -d -p 8888:8888 tensorflow/tensorflow:2.9.0-gpu
```

docker run --volume /mnt/h/ubuntu_project:/Project --name tf_gpu_290 --gpus all -d -t tensorflow/tensorflow:2.9.0-gpu


docker run -e PULSE_SERVER=host.docker.internal -v /tmp/.X11-unix:/tmp/.X11-unix -v /mnt/h/ubuntu_project:/Project --device /dev/snd tensorflow/tensorflow:2.9.0-gpu --name tf_gpu_290_sound_device --gpus all

-t 옵션이 중요(안꺼지게)