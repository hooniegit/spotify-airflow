# spotify-airflow
Airflow를 통해 spotify-api 레포지토리의 FastAPI를 스케줄링하는 로직을 포함하고 있습니다.

# before start
ubuntu 환경에서 docker container을 실행시키기 위해서 docker 설치가 필요합니다.<br>
설치 가이드는 공식 document(https://docs.docker.com/engine/install/ubuntu) 를 참조하였습니다.

# Container 실행
``` bash
# 레포지토리 최상위 디렉토리에서 실행
$ docker compose up -d
```