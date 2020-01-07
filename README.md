# testPrj 
 정렬방식:
연관성 - 등록일
근무형태
정규직
(16)
인턴
(2)
아르바이트
(2)
신입공채
(1)
우대 조건
장애인 우대
이력서를 등록하세요 - 수천개의 공고에 손쉽게 지원하세요
1페이지 결과 32건

[Search & Clova] NLP 기술 개발 인턴
네이버
대한민국
등) • 웹 프레임워크 및 라이브러리를 통한 개발 경험 있으신 분 (node.js, docker, Django 등) [채용하고 싶은 사람] • 주어진 문제에 대하여 책임감을 가지고 끈기있게 도전하는 분 • 적극적인 자세로...
27일 전·스크랩·더보기
## Prerequistic
### hostname 
* master is hadoop master
*example
```
sudo -i
echo "111.111.111.111 master" >> /etc/hosts
```
### Keyfile
* keyfile name : mykey.pem
```
$ ls
do.sh hive_empdept.sh mykey.pem
```

## install
```
git clone https://github.com//LeeYeongAh/testPrj.git
cd testPrj
scp ~/mykey.pem ./
. do.sh
```
## Result
```
~
~
Time taken: 10.641 seconds, Fetched: 3 row(s)
Query ID = hadoop_20200107044953_150bf150-630e-4171-bec2-6a9664a12e27
Total jobs = 1
Launching Job 1 out of 1
Status: Running (Executing on YARN cluster with App id application_1578363143699_0010)

Map 1: 0(+1)/1	Reducer 2: 0/1	Reducer 3: 0/1
Map 1: 1/1	Reducer 2: 0/1	Reducer 3: 0/1
Map 1: 1/1	Reducer 2: 1/1	Reducer 3: 0(+1)/1
Map 1: 1/1	Reducer 2: 1/1	Reducer 3: 1/1
OK
20	2518.75
10	2916.6666666666665
Time taken: 1.127 seconds, Fetched: 2 row(s)
OK
dept
emp
Time taken: 0.018 seconds, Fetched: 2 row(s)
```

