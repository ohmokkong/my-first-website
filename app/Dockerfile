# Python 이미지를 기반으로 컨테이너 생성
FROM python:3.9-slim

# 작업 디렉토리 설정
WORKDIR /app

# 현재 디렉토리의 파일들을 컨테이너의 작업 디렉토리로 복사
COPY . .

# 애플리케이션 실행
CMD ["python", "app.py"]
