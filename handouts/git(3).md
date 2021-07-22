---
marp: true
---

# git, github 실전

## NKLCB

---

<!--
paginate: true
theme: default
size: 16:9
footer : 네카라쿠배 git,  Wooyoung Choi, 2021
-->

## frontend-1st Feedback

- 제목만 존재하는 커밋
 -> 짧더라도 커밋단위에 대한 설명을
- 제목이 불친절한 커밋
 -> 클릭을 안해도 어떤 내용일지 알 수 있는 충분한 요약설명
- 큰 커밋단위
 -> 수업내용의 경우 수업 진행단위 별로 잘라 커밋
- 브랜치에 대한 적극적 활용에 대한 아쉬움
 -> 수업 모듈별로 브랜치를 나누어 작성한 뒤, 해당 브랜치 push까지

---

## Simple project with git

### Stopwatch

- 시, 분, 초, 밀리초 가 표현되어야 한다.
- 00:00:00.0 의 형태
- lap 버튼으로 lap 기능을 구현해야 한다.(특정시점 저장 기능)
- 새로고침 시 모든 정보가 리셋되어야 한다
- start 버튼은 동작 후 stop/resume 버튼으로 바뀌며, 누를 때마다 정지/계속 되어야 한다.
- reset 버튼을 누르면 모든 상태가 초기화 된다.(사실상 새로고침)
- 해당 페이지의 디자인은 자유롭게 구성한다.
- 추가기능 구현 환영

---

## Process

1. 팀원 구성 후 요구사항 분석 회의 진행
2. 개인 계정의 repo를 생성하여 진행(collaboration)
3. 각자의 역할은 기술단위가 아닌 기능단위로 정함
4. github projects로 backlog를 만들고 구현을 시작함
5. 모든 대화는 대면이 아닌 projects와 커밋 속 conversation 으로 진행
6. git flow 적극 활용

- 기능의 동작이나 개발완료 유무는 고려사항이 아님!!!!!

<link href="https://fonts.googleapis.com/css?family=Nanum+Gothic:400,800" rel="stylesheet">
<link rel='stylesheet' href='//cdn.jsdelivr.net/npm/hack-font@3.3.0/build/web/hack-subset.css'>

<style>
h1,h2,h3,h4,h5,h6,
p,li, dd, table > * > * {
font-family: 'Nanum Gothic', Gothic;
}
span, pre {
font-family: 'Hack', monospace;
}
</style>