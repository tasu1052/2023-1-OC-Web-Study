복습
commit 하면 unmodified로 돌아감 -> commit 한 순간 그게 기준이 되기 때문
add 명령어 -> staging area로 작업 결과 넘김
staging area->쌓아두는 역할
repository-remote and loca

remote repository 
ex)git hub

clone 외부 레포지토리에서 받아올 때 사용
fetch 변경점 확인할 때 사용


Branch
->포인터
head가 master를 가르키는데 내가 보이는 화면을 가르킨다?
가장 마지막 커밋을 가르키는 포인터 

$git checkout ______->분기가 갈라진 부분들을 볼 수 있음(_____브랜치로 옮겨 감)
$git branch _______->______이름의 브랜치를 만든다
$git branch->현재 만들어진 branch를 다 볼 수 있다

merge->병합
fast forward 전략?
변화라는 건 기준이 있다
새로운 커밋이 생긴다

conflict->충돌

$git status-> 현재 상황보기(중요)
$git stash->변경 사항들 쌓아두기 지금까지 작업 중 커밋 못한거 스택에 임시보관

깃 플로우->branch 관리하는 하나의전략
develope->메인 branch
깃허브 커밋 메세지 컨벤션?

