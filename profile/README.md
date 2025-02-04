# PAD

<img width="2301" alt="Cover Image (1)" src="https://github.com/user-attachments/assets/83407701-ccbd-40d5-a12e-9cde365ad425" />

> 개발자, 아티스트, 디자이너를 위한 소셜 커뮤니티

- 배포 URL:

- 테스트 아이디: `test`

- 테스트 비밀번호: `12341234`

<br />

## 프로젝트 소개
- `FlavorPath`는 사용자들에게 **맞춤형 식당 추천 경험**를 제공하는 데 초점을 맞춘 식당 탐색 애플리케이션입니다.
- 사용자는 한식, 중식, 디저트 등 선호하는 카테고리를 선택해 해당 카테고리에 가장 적합한 식당 정보를 빠르게 찾을 수 있습니다.
- 또한, 리뷰 기능을 통해 사용자들이 직접 작성한 신뢰도 높은 후기와 평가를 확인할 수 있어 식당 선택에 도움을 줍니다.
- 간단한 인터페이스와 직관적인 사용성을 갖춰 사용자가 원하는 식당 정보를 빠르고 정확하게 제공하여 최적의 외식 경험을 제공합니다.

<br />

## 프로젝트 실행하기
```
$ git clone https://github.com/FlavorPath/front.git
$ pnpm install
$ pnpm run dev
```

<br />

## 개발 환경
### 프론트엔드
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Zustand](https://img.shields.io/badge/zustand-%2320232a.svg?style=for-the-badge)
![PandaCSS](https://img.shields.io/badge/pandacss-%23FDE046.svg?style=for-the-badge)
![React Query](https://img.shields.io/badge/-React%20Query-FF4154?style=for-the-badge&logo=react%20query&logoColor=white)
<br />
### 백엔드
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)
![Swagger](https://img.shields.io/badge/-Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
<br />
### 협업 도구 및 배포
![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)
<img src="https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white" />
![Swagger](https://img.shields.io/badge/-Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white)
![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)

<br />

## 폴더 구조
```
src/
├── api/                 # API 호출 및 관련 로직
├── assets/              # 이미지 및 정적 자산
├── fonts/               # 폰트 파일
├── hooks/               # 커스텀 훅
├── mocks/               # Mock 데이터
├── pages/               # 페이지 컴포넌트
├── routes/              # 라우트 설정
├── store/               # 상태 관리 관련 코드
    ├── queries
    └── stores
├── styles/              # 스타일 관련 파일
├── ui/                  # UI 컴포넌트
    ├── components
    └── view
        ├── atom
        ├── molecule
        └── template
└── utils/               # 유틸리티 함수 및 모듈
```

```
backend
├── controllers          # 각 기능별 API들을 모아둔 디렉토리
├── middlewares          # 인증 관련 및 S3업로드를 연결하는 미들웨어
├── routes               # 각 기능별 API들을 연결하는 라우팅 파일
├── utils                # DB 설정 및 S3 사용을 위한 셋팅
├── app.js
└── server.js 
```
- **[데이터베이스 설계 설명](https://clean-indigo-57d.notion.site/DB-14d382bd5b8e80f4b9a4f6bf71df047f?pvs=4)**
<br />

## 트러블슈팅
- **[라벨에 의한 마커패칭시 화면 깜빡임 문제 해결](https://graceful-dresser-be9.notion.site/Feat-prefetching-14c011daa17b80568ad5df102a471f33)** 
- **[데이터베이스 설계 및 데이터 중복 문제 해결](https://clean-indigo-57d.notion.site/14c382bd5b8e80bbbaa6ed4d6fa6f603?pvs=4)** 
  
<br />

## 주요 기능
| 회원가입/로그인 페이지 | 홈페이지 | 상세페이지 |
| -- | -- | -- |
|<img src="https://github.com/user-attachments/assets/2ffde60d-3cb9-4230-96aa-fa4c87c71df1" width="200" /> | <img src="https://github.com/user-attachments/assets/49f984da-0341-4bb5-8cae-b9828a4926b7" width="200" /> | <img src="https://github.com/user-attachments/assets/f918fb2d-3708-4d94-a235-3f6b14eba04d" width="200" /> |

| 검색페이지 | 스크랩페이지 | 마이페이지 |
| -- | -- | -- |
| <img src="https://github.com/user-attachments/assets/30ce62fc-43bf-47b0-9f5a-77370e0ae80e" width="200" /> |<img src="https://github.com/user-attachments/assets/b7281fce-b201-4056-b697-3905e6fd5151" width="200" /> |<img src="https://github.com/user-attachments/assets/7205e2f3-db5e-46e0-9ba8-37ba33a8cc30" width="200" />|

<br />

## 향후 개선 사항
 - 로딩 에러 처리의 개선 사항
 - 관리자 페이지 생성
 - 백엔드에서의 사진 관리
 - 리프레쉬 토큰과 로그아웃 구현
<br />

## FlavorPath 팀
| [한태동](https://github.com/HANTAEDONG) | [심채윤](https://github.com/chaeyun-sim) | [조성민](https://github.com/Ss0Mae) | [정동현](https://github.com/peppertown) |
| -- | -- | -- | -- |
| <img src="https://avatars.githubusercontent.com/u/132195232?v=4" width="120" /> | <img src="https://avatars.githubusercontent.com/u/111689342?v=4" width="120" /> | <img src="https://avatars.githubusercontent.com/u/80831228?v=4" width="120" />  | <img src="https://avatars.githubusercontent.com/u/142657661?v=4" width="120" />  |
| <p align="center">FE</p> | <p align="center">FE</p> | <p align="center">BE</p> | <p align="center">BE</p> |
