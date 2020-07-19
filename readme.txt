로컬저장소 
원격저장소 = 레파지토리 

1. 첫번째 커밋하기 
1) 로컬저장소를 만들기
 명령어 : git init 
 - [.git] 폴더가 생성 
2) 첫번째 커밋하기 
 - 커밋 : 각 버젼 
 명령어 : git config --global user.email "xxx@gmail.com"
           git config --global user.name "xxx"
  - 계정 설정 
 명령어 : git add readme.txt (파일이름) 
  - 커밋에 추가할 파일 선택
 명령어 : git commit -m "설명을 쓰세요"

2. 다른 커밋으로 돌리기 
 명령어 : git log 
  - 결과 : commit 123abc..... 설명 .. (첫번째커밋)
            commit 0987,,, 설명 ..  (두번째커밋 )
  명령어 : git checkout 123abc 
   - 첫번째커밋으로 되돌아감
    - 결과 ~~ Head is now at ,,,~~ 

  명령어 : git checkout - 
  - '-'은 최신 커밋을 의미함 



3. 원격저장소에 올리기 
 1)명령어 : git remote add orgin https://주소.git 
 - remote add orgin : 로컬저장소에 원격저장소 주소를 알려줌 
 2) push 명령어로 커밋들을 원격저저ㅏㅇ소에 올린다. 
 - git push origin master 