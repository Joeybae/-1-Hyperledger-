# 하이퍼레져 앱 만들기 실습 1일차 - 환경 구축

Hyperledger fabcar 예제

Hyperledger 예제를 실행하기 위해서 먼저 개발환경을 구축합니다.

<Mac버전>

1. 터미널(Terminal) 실행

2. brew 설치 : ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)" < /dev/null 2> /dev/null

3. curl 설치 (터미널에 명령어 입력) : brew install curl

4. curl 버전확인 (터미널에 명령어 입력) : curl --version

5. 맥버전 Docker Desktop 설치 : https://docs.docker.com/docker-for-mac/install/ 로 들어가서 Docker Desktop Version 설치

6. docker 버전확인 (터미널에 명령어 입력) : docker version

7. docker-compose 설치와 버전확인 (터미널에 명령어 입력) : docker-compose version

8. Node 설치 (터미널에 명령어 입력) : brew install node@8

9. Golang 설치 : https://golang.org/dl/에서 Mac 버전 설치

10. Golang 버전확인 (터미널에 명령어 입력) : go version

11. Gedit 설치 : brew install gedit

12. Go PATH 설정 : 터미널에 gedit ~/. profile 명령어를 입력해서 창을 열고, 1) export GOPATH=$HOME/go, 2) export PATH=$PATH:/usr/local/go/bin:$GOPATH/bin 을 추가해준다.

13. Python 2.7.16 설치 : https://www.python.org/downloads/mac-osx/ 에서 2.7.16 버전 설치

14. Python 버전확인 (터미널에 명령어 입력) : python --version

15. Git 설치 (터미널에 명령어 입력) : brew install git

16. Hyperledger 예제 설치 : sudo curl -sSL http://bit.ly/2ysbOFE | bash -s 1.4.1

17. Hyperledger 경로 설정 : 터미널에 gedit ~/. profile 명령어를 입력해서 창을 열고, export PATH=$PATH:/usr/local/go/bin:$GOPATH/bin:~/fabric-samples/bin; 입력

에러가 없으면 Hyperledger 예제 사용을 위한 환경 구축 완료.
