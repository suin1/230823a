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

## clone과 pull 특징 ##
1. clone : 로컬에 저장소가 없는 경우.
   저장소 자체를 복사
2. pull : 로컬에 연결된 저장소 있는 경우.
   저장소 안에있는 파일 내려받기

## 충돌(conglict)시 해결방법 ##
_ 충돌 이유 _
하나의 문서가 온라인과 로컬에서 각각 수적이 일어났기 때문
_ 해결 _
1.pull을 이용하여 온라인 저장소에 로컬로 파일 내려받기

2.받은 로컬 저장소의 문서를 수정후 commit push