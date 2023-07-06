# cloud_git
클라우드 교육 과정 중 GIT 교육 과정을 위한 저장소입니다.


 - 버전 관리: 문서 수정 시 언제 수정했는지, 무엇을 변경했는지 편리하고 구체적으로 기록   하기 위한 버전 관리 시스템

 - 백업: 원격 저장소의 github를 이용하여 git 파일을 백업

 - 협업: github를 이용하여 여러 사람이 함께 작업할 수 있도록 해결하는 기능 제공

untracked:git의 관리 대상이 아닌 상태 초기에 생성된 파일이 가지는 상태
tracked:git의 관리 대상에 해당하는 상태로 스냅샷에 포함된 파일과 add 명령으로
새로 추가한 파일이 가지는 상태

작업 전
git checkout [자기 브랜치]
git pull origin main <= main에 있는거 갖고 오기
수정하기....

작업 후
git add, commit
git push origin [자기 브랜치]
github 페이지 가서 pull request 해서 main으로 merge하기
