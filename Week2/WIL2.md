서버와 리소스
서버: 사용자(client)에게 정보를 제공하는 컴퓨터
리소스: 서버에게 제공받는 자원

URL 과 DNS
URL: 리소스의 위치를 가리키는 문자열(주소)
DNS: IP 주소와 연결된 이름

git의 명령어 정리
working directory: 작업하는 공간
staging area: 중간에 대기하는 공간
local repository: pc 내 저장하는 공간
remote repository: 원격으로 저장하는 공간

add: working directory 에서 staging area 로 업로드-> 완성을 위해 준비한 부분이 저장된다
commit: staging area 에서 local repository로 업로드-> 완성된 부분이 저장된다
push: local repository에서 remote repository로 업로드

pull: remote repository에서 working directory 로 다운
fetch: remote repository에서 local repository 로 다운
따라서 pull 과 fetch 는 local에 얼만큼 영향을 주는지 차이가 있다. 
fetch 의 경우 local에서 확인만 할 뿐, working directory 에 영향을 주지 않는다.
따라서 수정사항을 fetch 로 확인할 경우, pc 내 파일에 수정사항이 반영되지 않는다. 
pull 의 경우 working directory 에 영향을 주므로 수정사항을 pull로 확인할 경우, pc 내 파일에 수정사항이 반영된다.