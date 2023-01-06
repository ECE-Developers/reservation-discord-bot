# Reservation Discord Bot

## Description

서울시립대학교 전자전기컴퓨터공학부 학실 예약 서비스의 discord bot을 담당하는 레포지토리입니다.

## Installation

- 해당 프로그램은 python3를 사용하기 때문에 pip3 및 python3의 설치가 필요합니다.
- pip3: 22.3.1
- python3: 3.10.5

Checking Version
```bash
$ pip3 --version
$ python3 --version
```
## .env Setting

1. 해당 디렉토리에 .env 라는 이름의 파일 생성
2. .env.example에 있는 내용을 복사
3. 환경 변수에 해당하는 값 설정

## Local Setting ( MAC )

```bash
# 로컬로 프로젝트 파일 복사
$ git clone https://github.com/ece-developers/reservation-discord-bot

# 디렉토리 이동
$ cd reservation-discord-bot

# python3 가상환경 구축
$ python3 -m venv venv 

# python3 가상환경 실행
$ source venv/bin/activate

# python3 패키지 실행
$ pip install -r requirements.txt

# 실행
$ python3 main.py
```

## Available Script

### 실행 

```bash
$ python3 main.py
```

- local 환경에서 디스코드 봇을 실행시킵니다.

### 가상환경 종료

```bash
$ deactivate 
```

- 가상환경을 종료합니다.