# Python

## 가상환경 
1. 가상환경 생성
`python -m venv venv` 
하나의 파이썬 환경 복제본을 만듦. 

2. 가상환경 활성화
```bash
# windows
source venv/Scripts/activate

# linux / macOS
source venv/bin/activate
```

3. 비활성화
```bash
deactivate
```

*pip 빠르게 프로그램을 설치 
*전역 / 가상환경
*ex.특정 프로젝트 내에서만 프로그램을 설치할 때 가상에서 프로그램을 설치 

4. 가상환경에서 프로그램 설치
```bash
pip install jupyterlab 
```

5. 설치된 목록 확인 & jupyterlab 접속
```bash
pip list
jupyterlab
```