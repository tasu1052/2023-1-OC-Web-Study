git add
작업 디렉토리 상에 있는 변경 내용을 스테이징 영역에 추가하기 위해 사용하는 명령어
git push
커밋된 변경점들을 원격 저장소에 보내기 위해 사용하는 명령어
git commit
staging 영역에 쌓은 변화들을 이름을 지어줌(버전 이력을 파일 안에 기록함.)->동료들 혹은 내가 나중에 봤을 때 알아보기 위함.
git pull과 fetch 차이점
둘 다 원격저장소의 내용을 가져오는데 사용됨. 그러나 둘은 서버와 로컬의 병합 자동처리 여부로 차이가 생김.
fetch는 가져온 변경내용이 로컬에 영향을 미치지 않고 병합하기 전 확인하는 용도로 주로 사용
pull은 가져온 변경내용을 로컬에 병합함. pull은 원격 저장소에 변경 사항이 존재하는 상황에 사용하면 충돌이 일어나며
새로 작업한 내용이 손실될 수 있음. 보통 fetch 명령어로 변경사항을 먼저 확인후 pull 사용함.

2주차 내용 정리

GIT이란?
컴퓨터 파일의 변경사항을 추적하고 여러 명의 사용자들 간에 해당 파일들의 작업을 조율하기 위한 스냅샷 스트림 기반의 분산 버전 관리 시스템
->파일의 변경 사항을 추적하고 협업 작업을 조율해주는 어떤 것

파일의 4가지 상태
Git이 아예 추적하지 않는 상태(Untracked)
추적하지만 변경이 없는 상태(Unmodified)
변경이 있는 상태(modified)
Staged 상태(Staged)

파일들은 조건에 따라 4가지 상태를 오감.


Working Directory=작업공간-> 내가 일하고 있는 공간

Staging Area=중간 저장소 느낌->코드를 쌓아놓고 보내는 곳

Repository=저장소-> 커밋을 마친 코드들은 이곳에 저장됨. Local과 remote로 나뉘는데 local은 내 컴퓨터, remote는 git이 관리하는 외부 저장소의 역할을 함.
remote repository 중 하나가 바로 github


1주차 내용정리

URI:Uniform Resource Identifier->이 안에 URL과 URN이 존재함
URL:Uniform Resource Location->위치를 나타낸 것(교촌치킨 신촌점)
URN:Uniform Resource Name->도서 출판 번호같이 고유한 이름으로 찾는 것

Resource=웹에서 식별 가능한 대상->교촌 허니콤보

URL:프로토콜 +DNS주소

프로토콜=통신규약

DNS=Domain Name System
이런 것들을 왜쓰나?
원래 복잡한 IP주소를 통해 리소스에 접근해야함. 그러나 이러한 IP주소들은 외우거나 관리하기 너무 힘들고 IP주소는 사정에 따라 바뀔 수 있다.