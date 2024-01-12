## 스타트캠프(3일간)
### 1일차

chat_GPT (Generative Pre-trained Transformer)

zero shot lerning

few shot lerning

**API** (application programming interface)—인증key를 통해 받아옴(요구안하는 무료도 존재)

구글검색과 gen_ai의 차이점은 이미 존재하던 정보를 보여주는것과 기존의 정보를 바탕으로 새로 만들어낸 것이다.(아는지 모르는지는 모름)

할루시네이션(사실인지 위조인지 잘 모르는 생성물) —> 검증해야함

html : 정적(static), 자바 등 : (dynamic)

---

### 2일차

**Markdown** : 일반 텍스트로 문서를 작성하는 방법(텍스트와 코드를 함께 문서화하기위해서…)

(.md)

Codeblock              : 오직 코드만

Inline Code Block   : 글 사이에 코드 있는 경우

문법 : https://www.markdownguide.org/basic-syntax/

표만들기 : https://www.tablesgenerator.com/markdown_tables

**GUI** (Graphical User Interface)  : 보여지는 화면을 마우스 딸깍

**CLI** (Command Line Interface) : 명령어를 통해서 사용자외 컴퓨터가 상호 작용하는 방식

`$ touch prac2.txt`  : prac2라는 이름의 텍스트 생성!

GUI보다 Cli가 더 싸서 많이 쓴다

cli는 영구적이고 즉각적이다(gui와 다르게)

**명령어**

touch : 파일 생성

pwd : 현재 작업중인 디렉토리 확인( print working)

cd : 현재 작업중인 디렉토리 변경(change directory)

start : 폴더/파일을 열기

rm : remove (rm -r :  옵션으로 디렉토리 삭제)

. : 현재 작업중인 디렉토리 의미

.. : 현재 작업중인 디렉토리의 상위 디렉토리 의미

mkdir : make directory

ls : 현재 작업중인 디렉토리 내부 파일 확인(list) (ls -a : all 이라는 옵션으로 숨긴거 까지 다 나옴 )

init → add → commit



절대경로 : 원점 좌표로부터 목적 지점까지 모든 경로를 전부 작성한것  

/c/Users/SSAFY/Desktop/cli_prac

상대경로 : 현재 작업하고 있는 디렉토리 기준으로 계산된 상대적 위치

ssafy/Desktop

**Git**  (분산 버전 관리 시스템)

버전관리 : 이전 버전으로부터 변화점을 기록해 둔것

분산식 : 버전을 여러개의 복제된 저장소에 저장 및 관리

장점 : 중앙에 의존하지 않고  동시에 여러 작업 수행 가능

중앙 집중식 : 버전은 중앙에 저장하고 중앙서버에서 가져와서 다시 중앙에 업로드

git의 역할 :  코드의 버전을 관리 → 개발 과정을 파악가능

git 메뉴얼 : https://git-scm.com/book/ko/v2

git의 3가지 영역 : Working directory, Staging Area, Repository

Working directory : 실제작업중인 파일이 저장되는 디렉토리

Staging Area : 변경된 파일 중, 다음 버전 포함시킬 파일을 선택적으로 추가하거나 제외하는 중간 준비 영역

Repository : 버전이력과 파일들이 영구적으로 저장되는 영역

git init : 로컬 저장소 (초기화) ⇒git의 버전관리를 시작할 디렉토리에서 진행

git add : 변경사항을  스토리지에 추가

git commit : Staging Area 에 있는 파일들을 저장소에 기록⇒해당시점의 버전을 생성하고 변경이력을 남기는것

---

### 3일차

리모트 저장소(remote repsitory,원격저장소): 코드와 버전관리 이력을 온라인상에 저장하는 공간을 말한다.

git remote add 로 연결시킨다(원격과 로컬을)

git clone : 로컬에 없을때 원격저장소에서 전체 복제하여 온다 —>git init 포함이므로 따로 안해 됨

→ 레포이름이 폴더 명이 된다

git push : 로컬에서 원격으로 보낸다  (ex: git push orgin master)

git pull : 원격에서 로컬로 가져온다

gitignore : 특정 파일이나 디렉토리의 변경사항은 추적하지 않도록 설정 

1.    .gitignore파일 생성
2.   a 와 b이름을 가진 텍스트 파일 생성
3.  gitignore에 a작성

gitignore 주의사항  : 이미 git의 관리를 받은 파일은 나중에 gitignore에 작성해도 적용되지 않음

gitignore 쓸 내용 추천 사이트 : https://www.toptal.com/developers/gitignore/

TIL(Today I Learned) : 내가 학습한 것을 마크다운을 통해서 기록하여 문서화