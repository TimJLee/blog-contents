# blog-contents
벨로그 글 기고를 위한 글 미리 작성하기 - 일주일에 2번 기고하기(화,토)

## 2020-05-22
서머코딩 대비 문제풀이 과정 기록
## 2020-05-14
전체탐색 개념 공부 기록
## 2020-05-12
프로그래머스 > 해시 > 베스트앨범 문제 풀이 과정 기록, 회고
## 2020-05-11
프로그래머스 > 해시 > 위장 문제 풀이 과정 기록
## 2020-05-09
전화번호 목록에서 String sort 원리 학습 기록, 스마일게이트 수료증 올리기, 해시문제 하나 더 풀기
## 2020-05-08
전화번호 목록 다른 풀이 학습, 러닝일지 기록(복귀 6일차)
## 2020-05-07
프로그래머스 - 전화번호 목록 해결 방식 기록
## 2020-05-06
프로그래머스 - 완주하지 못한 선수 문제풀이 방식 기록
## 2020-05-05
러닝일지 기록 - 복귀 5일차
## 2020-05-04
러닝일지 기록 - 복귀 4일차
## 2020-05-03
알고리즘 C++ -> JAVA 로 바꾸면서 고민했던 내용과 java hashmap, sort 등 학습 글 기고
## 2020-05-02
CI/CD 관련 글 기고
## 2020-04-30
캡스톤+한이음 프로젝트에서 사용할 Kafka MQ 개념에 대한 공부내용 기고 완료
## 2020-04-29
Nosql vs Rdbms 비교글 & 프로젝트적용 후기 기고 완료
## 2020-04-28
티스토리로 블로그 이관완료
에드센스 신청완료
RSS등록, 인덱스 신청 등 작업완료
## 2020-04-27
더 나은 개발자가 되기까지 글 기고 완료
gitignore 관련 글 기고 완료
## 2020-04-23
.gitignore 관련 글 미리 작성
.gitignore 가 적용되지 않을 때 해결법 & 최상위 디렉토리 이외에 어떤 디렉토리 안에 있던 간에 해당 파일 무시하는 방법
```
**/*.docs    -- 모든 디렉토리(실험결과 최상위 디렉토리도 포함임.) 아래 .docs 확장자 파일 커밋에서 제외
*.docs       -- 최상위 디렉토리 아래 .docs 확장자 파일 커밋에서 제외
name.py      -- 최상위 디렉토리 아래 name.py 파일 커밋에서 제외
data/        -- data 디렉토리 커밋에서 제외

-- 특수 케이스 : private/data 디렉토리를 커밋에서 제외하되, 그 안에 .public 확장자 파일은 커밋에 추가하고 싶을 때
private/data/**
!private/data/*.public

```
.gitignore가 제대로 작동되지 않아서 ignore처리된 파일이 자꾸 changes에 나올때가 있다.
=> git의 캐시가 문제가 되는거라 아래 명령어로 캐시 내용을 전부 삭제후 다시 add All해서 커밋하면 된다.
```
git rm -r --cached .
git add .
git commit -m "Fix: fix untracked files"
```
참고자료 : https://nesoy.github.io/articles/2017-01/Git-Ignore 처럼 작성하기... 깔끔하게
## 2020-04-22
서버개발캠프 회고록(RDBMS vs NOSQL 기술 선택) 기고

## 2020-04-20
DFS & BFS 스택,큐 로 이해하기 글 기고
