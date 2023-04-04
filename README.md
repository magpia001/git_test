# git_test
git 테스트 저장소

## README.md 설명
- 작성 문법은 markdown 문법을 따른다.

## test1.txt
- 새로 깃 테스트 한다

## test2.txt
- git commit 수정하기 실습 기록

## commit message 수정 방법
- commit 메지시 확인
  - 전체 확인 : `git log` 
  - 메시지만 확인 : `git log --oneline`

- 수정 명령: local 저장소에 있을 경우
  - 가장 최근 commit 메시지 수정
<pre>
  git commit --amend
</pre>
  - vi 에디터가 실행, commit message가 있음
  - 메시지 수정
    - 편집모드로 변경
      - 커서 이동
      - 편집모드로 변경
      - 수정
      - 키보드 esc 키
      - :wq  ->  엔터키 수행

  - git log로 확인하기
    `git log --oneline`
