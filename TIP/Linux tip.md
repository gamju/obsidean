현재 위치에서 디렉토리 즉 폴더 개수 세기
 ls -l | grep ^d | wc -l
현재 위치에서 파일 개수 세기
 ls -l | grep ^- | wc -l
xming 연결(to vscode)
	ubuntu server
		xming 설치
	windows client
		Remote-SSH: Open SSH Configuration File
			host
				hostname
					user
					ForwardAgent yes[추가]
					ForwardX11 yes[추가]
					ForwardX11Trusted yes[추가]
		setting.js -> terminal.integrated.env.windows
			"DISPLAY" : "127.0.0.1:0.0"



