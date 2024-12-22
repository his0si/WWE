# 🌎 WWE : World Wide Ewha

## ✨ 프로젝트 소개
_**World Wide Ewha**_<br>
WWE는 2024학년도 2학기 이화여자대학교 오픈SW플랫폼 오소리팀에서 탄생한 플랫폼입니다.<br>
교환학생/방문학생 등의 이유로 해외에 나가있는 학생들이 중고물품을 보다 쉽게 거래할 수 있도록 지원합니다.

## ✨ 기능
**WWE**가 제공하는 기능은 다음과 같습니다.
###### &nbsp;&nbsp;&nbsp;&nbsp;v1.0
- 상품 등록 및 삭제 기능
- 구매 시 리뷰 작성 및 조회 기능
- 대륙 별 상품 조회 기능
- 상품 검색 기능

<br>

## 🧑🏻‍💻 팀원 소개
### BACKEND
|     복지희     |     이나경     |     이소정     |
|:--------------:|:--------------:|:--------------:|
|     [@jettieb](https://github.com/jettieb)     |     [@2.or_kng](https://github.com/rinarina0429)     |     [@doleebest](https://github.com/doleebest)     |
| 리뷰 도메인 | 상품 도메인 | 회원 도메인 |

### FRONTEND
|     김기연     |     김희서     |     이나현     |
|:--------------:|:--------------:|:--------------:|
|     [@arky02](https://github.com/arky02)     |     [@his0si](https://github.com/his0si)     |     [@CSE-pebble](https://github.com/CSE-pebble)     |
| 상품 도메인 | 리뷰 도메인 | 회원 도메인 |

<br>

## 🛠️ 기술 스택
<!-- 버전 명시 -->
- Frontend: HTML, CSS, Javascript
- Backend: Python, Flask
- Database: Firebase
- Version Control: GitHub

<br>

## 📂 패키지 구조
```
📂 WWE
├─ 📂 static                 ▶︎ 정적 파일들이 저장된 디렉토리
│  ├─ 📄 css
│  ├─ 📂 image
│  └─ 📄 js
├─ 📂 templates              ▶︎ Flask 템플릿 파일들을 보유한 디렉토리
├─ 🐍 app.py                 ▶︎ Flask 애플리케이션의 메인 파일
├─ 🐍 database.py            ▶︎ Firebase 데이터베이스
├─ 📄 LICENSE
└─ 📄 README.md 
```

## 프로젝트 시작
```
git clone https://github.com/Ewha-Ohsori/WWE.git
cd WWE

# 생성한 가상환경 이름
conda activate OSWF

# 설치
flask --debug run
```
## ✨ Demo Video

https://github.com/user-attachments/assets/1011cad5-a53f-4a2c-95f1-7e36d3cb0c14

<br>

## 📝 Git Convention

### Commit Convention
**Commit 예시 :**
`FEAT: 로그인 기능 구현`

|    태그    | 설명                            |
|:--------:|:------------------------------|
|   DOCS   | 문서 작성 및 수정 작업 (README, 템플릿 등) |
|   FEAT   | 새로운 기능 추가 작업                  |
|   FIX    | 에러 및 버그 수정, 기능 수정 작업          |
|  HOTFIX  | 긴급 수정                         |
| REFACTOR | 코드 리팩토링 작업 (버그 수정이나 기능 추가 X)  |
|  RENAME  | 네이밍 변경 (파일명, 변수명 등)           |
|  REMOVE  | 파일 및 코드 삭제                    |
| COMMENT  | 주석 추가                         |
|  CHORE   | 빌드 업무 및 패키지 매니저 수정 작업 등의 작업   |
|  MERGE   | 다른 브랜치 머지 작업                  |
|   TEST   | 테스트 관련 작업                     |
|  STYLE   | 코드 포맷팅                        |

<br>

### Branch Convention

**브랜치명 형식 :** `branchType/#issue`

- **예시 :** `feat/#1`

|   브랜치    | 설명           |
|:--------:|:-------------|
|   main   | 실제 프로덕트 브랜치  |
|   dev    | 신규 버전 개발 브랜치 |
|   feat   | 기능 구현 브랜치    |
|   fix    | 기능 수정 브랜치    |
| refactor | 리팩토링 브랜치     |
|  bugfix  | 버그 수정 브랜치    |

