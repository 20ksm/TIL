## 앵커 링크

- [헤더적기](#헤더적기)
- [코드블럭](#코드블럭)
- [네이버](https://www.naver.com)

---

# 헤더1
## 헤더2
### 헤더3
#### 헤더4
##### 작게
###### 더 작게

헤더가 아닌 글씨

---

# ordered 리스트
1. 엔터를 눌러보세요
2. 탭을 눌러보세요
   1. 탭을 누르면 2-1번
3. 3번

# unordered 리스트
* -기호 또는 +기호 또는 *기호 상관없습니다
* 엔터
- 대시
+ +도 가능

# 체크 리스트 만들기

- [x] 당근
- [ ] 양파
- [ ] 마늘


# 코드 블럭 ---> 왜 많이 쓸까?
프로그래밍 언어마다 다른 가독성으로 표시해 준다.

```python
def func(a, b):
  return a + b

a, b = int(input())
c = func(a, b)
print(c)
```

# 링크 url 걸기
[네이버](https://www.naver.com)

# 이미지 걸기
![고양이](https://cdn.dailyvet.co.kr/wp-content/uploads/2024/05/15231647/20240515ceva_experts4.jpg)
![사례1: 고양이("%20"->x)](https://cdn.dailyvet.co.kr/wp%20content/uploads/2024/05/15231647/20240515ceva_experts4.jpg) 
![강아지](https://www.tipperarycoco.ie/sites/default/files/styles/localgov_535x302/public/2024-04/Happy%20dog.jpg?itok=uhdQ2Z1G)
![스크린샷](./스크린샷%202025-07-16%20152254.png)
![사례2: 스크린샷("-"->x)](./스크린샷-2025-07-16-152254.png)

주소 띄어쓰기는 **"%20"** 또는 **"-"** -> 그냥 자동완성하자

**웹에서 가져온** *고양이 사진*의 경우 **-** 사용, **컴퓨터에 저장**된 *스크린샷*의 경우 **%20** 사용

---
  - 상세
    - 마크다운(Markdown)에서 주소에 공백을 표현할 때 %20과 하이픈(-)은 다른 의미로 사용됩니다. %20은 URL 인코딩 방식에서 공백을 나타내는 코드이고, 하이픈(-)은 주로 링크나 파일명 등에서 단어를 구분하는 역할을 합니다.

    - %20 (URL 인코딩): URL에서는 공백 문자가 허용되지 않기 때문에, 공백 대신 %20으로 인코딩하여 사용합니다. 예를 들어, "My Documents" 라는 폴더 경로는 URL에서 "%20"을 사용하여 "My%20Documents" 와 같이 표현됩니다. 
    - 하이픈 (-): 하이픈은 주로 파일명, 폴더명, 링크 제목 등에서 단어를 구분하는 데 사용됩니다. 예를 들어, "my-first-post" 와 같이 단어 사이에 하이픈을 넣어 가독성을 높입니다. 마크다운에서 # 기호와 함께 사용하여 문서 내부 링크를 만들 때도 하이픈으로 단어를 구분합니다. 
  
    - 차이점 요약: %20는 URL에서 공백을 표현하기 위한 인코딩 방식입니다. 하이픈(-)은 주로 단어 구분이나 링크, 파일명 등에서 사용됩니다.
  

# 글꼴 굵게 표시

__굵은 글씨__
중간에 **굵은 글씨**를 넣기

# 기울기

_기울기 글씨_

중간에 *기울기 글씨*를 넣게

# 굵게 및 기울임

___굵게 및 기울임___

중간에 ***굵게 및 기울임***을 넣기

# 취소선
~~박보검~~

# 수평선
---

# 참고
[공식문서](https://www.markdownguide.org/basic-syntax/)




---
# GitHub Guide

GUI : 그래픽 유저 인터페이스
TUI : 텍스트 >> CLI : Command Line Interface

interface : 대상을 제어하는 수단 (ex 리모컨) 

========================================

Window OS의 Interface
GUI : Windows Shell
CLI : cmd(명령프롬프트), Power Shell

Linux OS의 Interface
GUI : GNOME
CLI : bash

왜 굳이 bash를 쓸까??
bash가 편해서 ---> Tab키 자동완성

Git을 다룰때 Interface
GUI : Github Desktop, 소스트리
CLI : git bash

결론 : GUI, CLI 둘다 쓸수는 있어야하지만 우리는 CLI를 쓸겁니다.

GUI의 장점 : 그래프 같은 복잡한 분석 보기 편하다
CLI의 장점 : 빠르다(Commit 명령어 3~4초면 끝)

====================================================

리눅스는 항상 HOME 디렉토리에서 시작 : ~
. : 현재 디렉토리
cd ~ : 홈 디렉토리
cd .. : 상위 디렉토리
cd - : 뒤로가기

touch : 파일생성
mkdir : 폴더생성
start : 파일 열기
rm : 파일 삭제
rm -rf : 폴더 삭제
cp : 복사

절대경로
~/Desktop/test/python/

상대경로(현재 티렉토리를 기준)
cd ./python
cd ../python2

=======================================================

python.org ---> python 설치 ---> 3.11.9
인터프리터

extension??
너 IDE 뭐써??
vscode는 IDE일까??
vscode는 텍스트 에디터 : 여기에 extension을 추가해서 마치 IDE처럼 쓴다.

IDE
Python : Pycharm, jupyter notebook
C : Visual Studio
Java : IntelliJ

node.js ---> 런타임
js 백엔드 프레임워크 ---> express.js 

====================================================================

Markdown : 로직 X 
README.md에 활용
: 내가 공부한내용, 프로젝트에 대한 간단한 설명(가독성, 편의성)

============================================================

### git init  : git 시작 (로컬 저장소 생성)
### rm -rf .git : git 삭제(git 종료)

### git add . : staging area에 변경사항 올리기
### git status : staging area의 작업 파일 확인

### git config --global user.email "이메일주소"
### git config --global user.name "이름"
### git config --global -l

### git commit -m "메시지명" : repository에(staging area의 변경사항을)올리기
### git log : repository 작업 파일 확인 (커밋 이력 확인)

===================================================

참고자료 

git commit --amend : vim 에디터가 열린다

수정 후(커서 위치를 확인 후 과감하게 타이핑)

ecs -> :q -> 저장하지 않고 종료
ecs -> :q! -> 저장하지 않고 강제 종료
ecs -> :wq -> 저장하고 종료

git : 분산 버전 관리 시스템

git : 로컬저장소 // github : 원격저장소

git init : git 시작

git config --global [user.name](http://user.name/) "이름"
git config --global user.email "이메일"

git add . : staging area에 올리기
git status : staging area의 작업 파일 확인

git commit -m "메시지명" : repository에 올리기
git log : 커밋 이력을 확인

### git remote add origin url : 로컬 저장소와 원격저장소를 연결(origin은 별칭)
### git remote -v : remote 목록 확인

git push origin +master : 가장 최근에 commit 되어있던 것을 강제로 push
(origin:별칭, master:branch명, +:강제로 진행)

==================================================

Q) clone과 pull의 차이점이 뭘까??
A) 새로운 환경에서 처음 다운로드 : clone

명령어 : git clone url

Q) clone을 받으면 remote를 할 필요가 있을까?
A) remote를 할 필요가 없다.

Q) clone과 pull의 차이?
A) 한번 clone을 받고 그 이후에는 pull로 진행

명령어 : git pull origin +master

==================================================

자리 옮긴후

1. git clonfig --global -l 확인
[user.name](http://user.name/), user.email 확인
2. 제어판 -> 사용자 계정 -> window 자격 증명 -> github, gitlab 삭제

=================================================

Q) .gitignore 파일은 왜 만들까?
A) 수 백개의 파일을 일일이 git add 하기에는 불편하기 때문에
.gitignore파일을 만들면 편하다

용량이 매우 크거나, 보안상 문제가 있거나, 청구 결제 관련된 파일들을
add 하지 않기 위해 .gitignore파일을 만든다(staging area에 올리지 않기 위해)

방법 : .gitignore 파일 생성 -> add 하지 않을 파일명이나 폴더명 작성하고 저장

---

commit 메시지 수정하기

명령어 : git commit --amend

vim에디터에서 수정하고
esc -> :q! : 저장하지 않고 강제 종료
esc -> :wq! : 강제 저장하고 종료

====================================

git revert : 특정 commit을 없었던 일로 만들기

a.txt 만들고 commit
b.txt 만들고 commit
c.txt 만들고 commit

git log -> 해시값 전체 복사(ctrl + shift + c), 붙여넣기(shift + insert)

명령어 :
git revert 해시값 : 이 특정 커밋을 없었던 일로 만든다.
vim 에디터 -> esc -> :wq

==========================================

### git reset : 특정 commit으로 되돌리기

### git reflog : 이전 과거 commit 기록들을 모두 볼 수 있음

### 명령어 : git reset --hard HEAD@{번호}