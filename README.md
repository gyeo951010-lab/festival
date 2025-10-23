# 추카제 2025 - KOICA 내부 조직문화 행사

이 프로젝트는 KOICA의 내부 조직문화 행사인 "추카제 2025"를 위한 웹사이트입니다.

## 로컬 환경에서 실행하기

이 애플리케이션은 완전히 로컬 환경에서 실행할 수 있도록 모든 외부 의존성을 다운로드하여 포함했습니다.

### 포함된 에셋

- **Google Fonts**: Noto Sans KR (300, 400, 500, 700 weight)
- **Font Awesome 6.0.0**: 아이콘 CSS 및 폰트 파일
- **KOICA 로고**: 로컬 이미지 파일

### 실행 방법

1. 이 폴더를 웹 서버의 루트 디렉토리에 복사하거나
2. 간단한 HTTP 서버를 실행합니다:

#### Python을 사용하는 경우:
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

#### Node.js를 사용하는 경우:
```bash
npx http-server
```

#### PHP를 사용하는 경우:
```bash
php -S localhost:8000
```

3. 브라우저에서 `http://localhost:8000`으로 접속합니다.

### 파일 구조

```
├── index.html          # 메인 HTML 파일
├── styles.css          # 메인 CSS 스타일
├── script.js           # JavaScript 기능
├── assets/             # 로컬 에셋 폴더
│   ├── css/           # CSS 파일들
│   │   ├── fontawesome.min.css
│   │   └── noto-sans-kr.css
│   ├── fonts/         # 폰트 파일들
│   │   ├── noto-sans-kr-300.ttf
│   │   ├── noto-sans-kr-400.ttf
│   │   ├── noto-sans-kr-500.ttf
│   │   └── noto-sans-kr-700.ttf
│   ├── images/        # 이미지 파일들
│   │   └── koica-logo.png
│   └── webfonts/      # Font Awesome 폰트 파일들
│       ├── fa-brands-400.woff2
│       ├── fa-regular-400.woff2
│       └── fa-solid-900.woff2
```

### 특징

- 📱 반응형 디자인 (모바일, 태블릿, 데스크톱 지원)
- 🎨 현대적이고 아름다운 UI/UX
- ⚡ 빠른 로딩 속도 (모든 에셋이 로컬)
- 🌐 인터넷 연결 없이도 완전 동작
- ♿ 접근성 고려된 디자인

### 브라우저 지원

- Chrome (최신)
- Firefox (최신)
- Safari (최신)
- Edge (최신)

## 개발 정보

이 웹사이트는 순수 HTML, CSS, JavaScript로 개발되었으며 외부 프레임워크나 라이브러리 의존성이 없습니다.
