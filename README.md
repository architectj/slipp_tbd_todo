
[참고사항]
- 각자의 Repository 설정 
    - fork to My Github Account 
    - local 
        - mkdir repo
        - cd repo
        - git init
        - git config user.email "email"
        - git config user.name "user"
        - git pull https://user:password@github.com/name/repo.git master
        - git remote add upstream https://github.com/slippStudy/slipp_tbd_todo
- github 본인의 레포지토리 
    - 이슈 생성
    - git branch -b "branch_name" ( "DDB-1_컴퍼넌트_Collector_구현"과 같이 이슈 아이디와 이슈 이름"  )
    - 수정 작업 이후 
    - git add . 
    - git commit -m "변경 내용 #이슈번호"
    - git push 

- 브랜치와 master merge 
    - 본인의 master 에서 작업한 이슈의 브랜치와 command 를 통해 merge 하여 push 하는 방법
    - github 에서 Pull Request 를 통해서 merge 하는 방법  

- upstream 에서 읽어오기 
    -  git fetch upstream 
- 본인의 로컬 저장소와 upstream 의 저장소 merge
    - git checkout master
    - git merge upstream/master
    - git push ( 본인의 remote github 반영 )