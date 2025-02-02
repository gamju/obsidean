1. 현재 버전 확인
	1. wsl -l -v
		1. ex) Ubuntu-22.04 Ubuntu-22.04----
2. 내보내기
	1. wsl --export Ubuntu-22.04D:\ubuntu.tar
3. 기존 버전 해제
	1. wsl --unregister Ubuntu
4. 배포판 가져오기
	1. wsl --import Ubuntu D:\WSL\Ubuntu D:\ubuntu.tar