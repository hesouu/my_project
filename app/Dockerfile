# 1. 기본이미지
from python:3.14.0-slim

# 2. 작업디렉토리 지정
WORKDIR /app

# 3. requirements.txt 복사
COPY ./requirements.txt .

# 4. requirements.txt 설치 명령 진행
RUN pip install -r requirements.txt

# 5. 원본소스(main.py) 복사
COPY main.py .
# COPY . . -> Docker ignore(필터링)을 작성해야함 (통상 많이 쓰는 방식)

# 6. 서버가동 => 도커 컴포즈로 이관, 여기서는 생략됨

