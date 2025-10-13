# 스페이스 슈팅게임 (웹 버전)

HTML5 Canvas를 사용한 웹 브라우저용 슈팅 게임입니다.

## 실행 방법

### 로컬 서버 실행
Python이 설치되어 있는 경우:
```bash
python -m http.server 8000
```

Node.js가 설치되어 있는 경우:
```bash
npx http-server
```

그 후 브라우저에서 `http://localhost:8000`으로 접속하세요.

### 직접 실행
`index.html` 파일을 브라우저에서 직접 열어서 실행할 수 있습니다.

## 게임 조작 방법

- **방향키**: 플레이어 이동
- **스페이스바**: 총알 발사
- **게임 오버 시 스페이스바**: 재시작

## 게임 특징

- HTML5 Canvas 기반 그래픽
- 다양한 적 유형과 보스전
- 점수 시스템 및 최고 점수 저장 (localStorage 사용)
- 효과음 및 배경음악 지원
- 반응형 UI

## 파일 구조

```
├── index.html          # 메인 HTML 파일
├── game.js            # 게임 로직 및 렌더링
├── package.json       # 프로젝트 설정 (웹용)
├── README.md          # 프로젝트 설명
└── sounds/            # 사운드 파일들
    ├── shoot.mp3      # 발사 효과음
    ├── explosion.mp3  # 폭발 효과음
    ├── collision.mp3   # 충돌 효과음
    ├── levelup.mp3     # 레벨업 효과음
    └── warning.mp3     # 경고 효과음
```

## 기술 스택

- HTML5 Canvas
- JavaScript (ES6+)
- CSS3
- Web Audio API

## 라이선스

MIT License