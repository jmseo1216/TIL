# 240419 studied git command 

## How to start
- github 에서 {폴더이름} 저장소를 만든다.
- dev 디렉토리에서 git clone {repo-addr}   (이때 여기서 github에서 https에서 복사한 내용}
- vi로 작성
- git status 로 확인.  (이때 빨간색글씨)
- git add {README.md}.  (준비완료, 접시에 추가)
- git commit  
   - commit : 동작하는 최소단위(ex method)를 올려야한다 .(습관들이기)
   - 실행시 vi가 뜨는데 제목, 내용을 잘 적어야함       
      - Conventional Commits 규칙을 유의해서 적어야함 
      - ex) 제목=> {prefix} : {description} , 내용=> {body}작업내용 상세 기술 
### Conventional Commits
- commit의 제목은 commit을 설명하는 문장형이 아닌 구나 절의 형태로 작성
- importanceofcapitalize `Importance of Capitalize`
- prefix 꼭 달기
  - feat: 기능 개발 관련          - build: 빌드 작업관련
  - fix: 오류 개선 혹은 버그 패치 - ci: Continuous Integration 관련
  - docs: 문서화 작업.            - chore: 패키지 매니저, 스크립트 등
  - test: test 관련.              - style: 코드 포매팅 관련
  - conf: 환경설정 관련 

## README.md 작성요령
- How to Start
- Installation
- Features 
- 위 3항목은 잘 적어야한다.

## .gitignore  (환경설정) : 특정 파일이나 디렉토리를 추적하지 않도록 명시하기 위한 파일 
   - (https://gitignore.io/) 에서 쉽게 복사붙여넣기로 설정가능 

## github blog - Hexo 만들기      
