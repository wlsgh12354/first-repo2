# 1. 기능
---
파일 경로를 입력 받아 해당 파일의 MDS, SHA-1 , SHA-256해시값을 계산해주는 프로그램

# 2. 사용방법
---

---(cmd)
python hash_calculator.py -f <file_path> -o <hash_algorithm>
---

옵션은 다음과 같이 사용할 수 있음

|옵션| |기능| 
|:-:| |-|
|-f| |파일 경로 입력|
|-o| |해싱 알고리즘, mds , sha-1 , sha-256 중 선택 기본값으로 모두 출력|
