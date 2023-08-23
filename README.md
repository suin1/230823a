## 230823 ##

1. 로컬 저장소 생성
 - `code(git init)`
2. README.md 파일 생성<br>
 - touch README.md
 - git add .<br>
 - git commit -m "내용"

3. 온라인 저장소 생성
 - git remote add origin https://주소

4. README.md 파일 온라인 저장소에 업로드
 - - git push -u origin main
  
## github에서 내려받기 ##
``$ git pull origin main``

1. clone : 로컬에 저장소가 없는 경우.
   저장소 자체를 복사
2. pull : 로컬에 연결된 저장소 있는 경우.
   저장소 안에있는 파일 내려받기
