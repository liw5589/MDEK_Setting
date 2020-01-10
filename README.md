# MDEK_Setting

DGIST 이상철 박사님 지능형 로봇 공학 연구실에서 실내 위치 측위 장비를 위해 하드웨어(MDEK 1001)를 세팅한 방법과 리눅스에서 그 값을 읽고 서버로 json을 전송하는 방법에 대해 설명하는 저장소 입니다.

DGIST Dr. Lee Sang-chul is a repository that explains how hardware (MDEK 1001) is set up for indoor location positioning equipment and how Linux reads its values and sends json to the server.

--------------------------------------------------------------------------------------------------------------

# 하드웨어 설정
## MDEK1001 하드웨어 설정

이 작업은 어느 운영체제에서 해도 상관이 없습니다. 윈도우 및 리눅스 모두 가능합니다. 저는 윈도우 기준으로 설명을 하겠습니다.
먼저 사용하던 MDEK1001이 아니라면 초기 설정을 해주어야합니다.
자신이 사용하는 시리얼 통신 프로그램을 사용하여 MDEK1001과 시리얼 통신 연결을 합니다. (Ex. 윈도우에서는 putty, 리눅스에서는 minicom 등등)
MDEK1001의 포트 번호를 확인하고, (윈도우는 장치 관리자로 이동하여 어느 포트로 연결되어 있는지 확인, 리눅스는 cd /dev/ 명령어를 사용해 확인)
전송률은 115200으로 설정하여 MDEK1001과 연결합니다
