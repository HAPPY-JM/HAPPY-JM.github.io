# 🌟 HAPPY-JM 포트폴리오 웹사이트

GitHub Pages를 활용한 개인 포트폴리오 웹사이트입니다.

## 📋 프로젝트 구조

```
HAPPY-JM.github.io/
│
├─ index.html        # 포트폴리오 메인 페이지
├─ about.html        # 자기소개 페이지
├─ projects.html     # 프로젝트 목록 페이지
├─ css/
│   └─ style.css     # 스타일 파일
├─ js/
│   └─ main.js       # JavaScript 파일
├─ img/              # 이미지 파일
├─ LICENSE
└─ README.md         # 프로젝트 소개
```

## 🚀 주요 기능

- ✨ **반응형 디자인**: 모바일, 태블릿, 데스크톱 모든 기기에서 최적화된 화면 제공
- 🎨 **모던한 UI/UX**: 그라디언트, 애니메이션, 호버 효과 등 디자인
- 📱 **모바일 네비게이션**: 햄버거 메뉴를 통한 모바일 친화적 네비게이션
- 🔍 **프로젝트 필터링**: 카테고리별 프로젝트 필터링 기능
- ⬆️ **스크롤 투 탑**: 페이지 상단으로 빠르게 이동하는 버튼
- 🎭 **스크롤 애니메이션**: 스크롤 시 요소들이 부드럽게 나타나는 효과
- 🌐 **소셜 링크**: GitHub, LinkedIn, Email 등 SNS 연결

## 🛠️ 사용 기술

- **HTML5**: 시맨틱 마크업
- **CSS3**: Flexbox, Grid, 애니메이션, 그라디언트
- **JavaScript (ES6+)**: 인터랙티브 기능, DOM 조작
- **Font Awesome**: 아이콘
- **GitHub Pages**: 자동 배포 및 호스팅

## 📦 설치 및 실행

### 로컬에서 실행하기

1. 저장소 클론

```bash
git clone https://github.com/HAPPY-JM/HAPPY-JM.github.io.git
cd HAPPY-JM.github.io
```

2. 브라우저에서 `index.html` 파일 열기
   - 또는 Live Server 등의 로컬 서버 사용

### GitHub Pages로 배포하기

1. GitHub 저장소 생성 (이름: `username.github.io`)
2. 코드를 저장소에 푸시

```bash
git add .
git commit -m "Initial commit: Portfolio website"
git push origin main
```

3. GitHub 저장소 설정
   - Settings → Pages
   - Source: `main` 브랜치 선택
   - 자동으로 `https://HAPPY-JM.github.io`에 배포됨

## 🎨 커스터마이징 가이드

### 1. 색상 변경

`css/style.css` 파일의 `:root` 섹션에서 색상 변경:

```css
:root {
  --primary-color: #6366f1;
  --secondary-color: #8b5cf6;
  /* 원하는 색상으로 변경 */
}
```

### 2. 콘텐츠 수정

- **index.html**: 메인 페이지 텍스트 및 프로젝트 정보
- **about.html**: 자기소개, 경력, 연락처 정보
- **projects.html**: 프로젝트 목록 및 설명

### 3. 이미지 추가

- `img/` 폴더에 이미지 파일 추가
- HTML 파일에서 이미지 경로 수정:

```html
<img src="img/your-image.jpg" alt="설명" />
```

### 4. 소셜 링크 변경

각 HTML 파일의 소셜 링크 섹션에서 URL 수정:

```html
<a href="https://github.com/your-username" target="_blank"></a>
```

## 📸 스크린샷

### 메인 페이지

- 히어로 섹션: 환영 메시지와 소셜 링크
- 기술 스택: 보유 기술 소개
- 주요 프로젝트: 대표 프로젝트 2개 표시

### 소개 페이지

- 프로필 이미지와 자기소개
- 통계 정보 (프로젝트 수, 기술 수 등)
- 타임라인 형식의 경력/교육 정보
- 연락처 정보

### 프로젝트 페이지

- 카테고리별 필터링
- 프로젝트 카드 그리드
- 호버 시 GitHub/라이브 데모 링크 표시

## 🔧 추가 개선 사항

- [ ] 다크 모드 추가
- [ ] 블로그 섹션 추가
- [ ] 연락 폼 추가
- [ ] 다국어 지원 (한국어/영어)
- [ ] SEO 최적화
- [ ] 성능 최적화 (이미지 압축, lazy loading)

## 📝 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다. 자세한 내용은 [LICENSE](LICENSE) 파일을 참조하세요.

## 👤 작성자

**HAPPY-JM**

- GitHub: [@HAPPY-JM](https://github.com/HAPPY-JM)
- Website: [https://HAPPY-JM.github.io](https://HAPPY-JM.github.io)

## 🙏 감사의 말

방문해주셔서 감사합니다!

---

⭐ 이 프로젝트가 도움이 되었다면 Star를 눌러주세요!
