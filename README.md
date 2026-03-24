# NomadWeather

현재 위치 기반 날씨 예보 앱 (React Native / Expo)


## 기능

- GPS 기반 자동 위치 감지 및 도시명 표시
- OpenWeatherMap API를 통한 날씨 예보 조회
- 가로 스크롤 방식의 날씨 카드 UI
- 날씨 상태별 아이콘 표시 (맑음, 흐림, 비, 눈, 번개 등)
- 한국어 날씨 설명 지원

## 기술 스택

| 패키지 | 버전 | 용도 |
|--------|------|------|
| Expo | 54.0.0 | 개발 프레임워크 |
| React Native | 0.81.5 | 모바일 UI |
| React | 19.1.0 | UI 라이브러리 |
| expo-location | 19.0.8 | GPS / 역지오코딩 |
| Fontisto | (expo 내장) | 날씨 아이콘 |

## 시작하기

### 사전 준비

- Node.js
- Yarn 또는 npm
- [Expo Go](https://expo.dev/go) 앱 (모바일 테스트용)
- [OpenWeatherMap API Key](https://openweathermap.org/api)

### 설치

```bash
yarn install
```

### 환경 변수 설정

프로젝트 루트에 `.env` 파일 생성:

```
EXPO_PUBLIC_API_KEY=your_openweathermap_api_key
```

### 실행

```bash
yarn start        # 개발 서버 시작
yarn android      # Android
yarn ios          # iOS
yarn web          # Web
```

## 프로젝트 구조

```
NomadWeather/
├── App.js          # 메인 컴포넌트 (위치, API, UI)
├── app.json        # Expo 설정
├── package.json    # 의존성
├── .env            # API 키 (git 제외)
├── .prettierrc     # 코드 포맷 설정
└── assets/         # 아이콘, 스플래시 이미지
```

## 앱 화면
<div align="center">
  <video src="https://github.com/user-attachments/assets/3a2040aa-2d04-4c4d-ace3-3457ea4bb3de" width="300" />
</div>

