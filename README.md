<!-- Heading ---->
# About Top
: 실시간으로 CPU 사용률을 체크해주는 도구. 리눅스를 사용하는 서버의 성능이나 현재 돌아가고 있는 상황을 볼 때 사용.

![image](https://github.com/janmangdong/hello/assets/133829891/4c7d6136-bb7b-4ca3-941a-ad6678d0ba27)

Top 프로그램 내용 : 
* 13:47:52 : 현재 서버의 시간
* 9 days, 5:24 : 켜져있는 시간
* 3 users : 유저
* load average : 실행/대기 중인 프로세스 수
* Tasks : 프로세스 수
* %us : 유저에서 사용하는 CPU 비중
* %sy : 시스템에서 사용하는 CPU 비중
* %id : 유휴 상태의 CPU 비중
* %wa : CPU idle 상태인 비중
* KiB Mem, swap :  각 메모리 상태 정보
* PID : 프로세스 ID
* USER : 프로세스 실행시킨 사용자
* PRI : 프로세스 우선순위
* NI : 일의 nice value값
* VIRT : 가상 메모리 사용량
* RES : 현재 페이지 크기
* SHR : 분할된 페이지에 의해 사용된 메모리를 나눈 메모리 총합
* S : 프로세스 상태
* %CPU : CPU 사용률
* %MEM : 메모리 사용률
* COMMAND : 실행된 명령어


Top 명령어 :
* shift + p : CPU 사용률이 높은 순서로 표시
* shift + m : 메모리 사용률이 높은 순서로 표시
* shift + t : 프로세스가 돌아가는 순서로 표시
* a : 메모리 사용량에 따라 나열
* b : Batch 모드 작동
* d : 지연 시간 간격
* h : 도움말
* H : 스레드 토글
* i : 유휴 프로세스 토글
* m : VIRT/USED 토글
* M : 메모리 유닛 탐지
* n : 반복 횟수 제한
* s : 보안 모드 작동
* S : 누적 시간 모드 토글
* u, U : 사용자별 모니터링
* Page down : 프로세스의 다음페이지 목록
* Page up : 프로세스의 이전페이지 목록

# About Ps
: process status의 줄임말로 현재 실행중인 프로세스 목록과 상태를 보여줌.

Ps 명령어 :
* $ ps -ef : 모든 프로세스를 풀 포맷으로 출력
* $ ps -ef | grep '이름': '이름'의 프로세스 작동 확인 (실행 유저, 프로세스 ID, 부모 프로세스 FID, CPU 사용량, 시작 시간, 프로세스 제어 위치, 작동 시간, 명령어 출력)
*  $ ps aux : 실행중인 모든 프로세스 확인
*  $ ps auxf : 실행중인 프로세스 트리구조로 확인
*  $ ps auxfww : 실행중인 프로세스 트리구조로 나타냄 + 실행중인 모든  
