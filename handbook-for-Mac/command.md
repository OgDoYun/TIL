* 열린 포트 목록 확인하기

    sudo lsof -PiTCP -sTCP:LISTEN

* 특정 포트(3000번)의 프로세스 아이디 찾기

    sudo lsof -i :3000

* 특정 프로세스(PID) 강제 종료하기

    sudo kill -9 PID