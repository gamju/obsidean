https://velog.io/@suhongkim98/%EC%88%98%EB%8F%99%EC%9C%BC%EB%A1%9C-%EB%8F%84%EC%BB%A4-%EC%9D%B4%EB%AF%B8%EC%A7%80-%EB%8B%A4%EB%A5%B8-%EC%9B%90%EA%B2%A9-%EC%84%9C%EB%B2%84%EB%A1%9C-%EC%98%AE%EA%B8%B0%EA%B8%B0

docker save 이미지명 > 파일명.tar
scp -i {원격pem파일} {보내고자하는_파일.tar} {원격서버_계정명}@{원격서버IP}:{파일이_저장될_원격서버에서의_경로}
docker load -i 파일명.tar
docker image ls