[[Container 복사]]
[[Container 전송]]

Container 삭제
docker rm [**컨테이너**id]
Container 진입
docker exec -it 컨테이너id "bin/bash"

docker run --gpus all -t -i -v /data/home/jooyoung/projects/01_card_detection:/mnt --name card_detect 730572d0c0dd

743fa36ee363