# Airflow Master Class

## 도커, Airflow 설치 on WSL
## WSL 도커, Airflow 실행
- sudo service docker start
- sudo docker compose up
- sudo docker compose down
- sudo docker ps
- Airflow UI: http://localhost:8080

## 파이썬 버전 확인
- sudo docker exec -it ysjung-airflow-worker-1 bash
- python -V
```
Python 3.6.15
```

## 파이썬 가상환경
- python -m venv ./venv

## Airflow 라이브러리 설치
- pip install "apache-airflow[celery]==2.10.5" --constraint "https://raw.githubusercontent.com/apache/airflow/constraints-2.10.5/constraints-3.8.txt"