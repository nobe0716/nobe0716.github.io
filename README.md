# Noah Jung's Tech Blog

Hugo(PaperMod 테마) 기반의 한국어 기술 블로그입니다. 성능 최적화, 아키텍처 설계, 엔지니어링 매니지먼트에 대한 고민과 경험을 기록합니다.

## 🚀 시작하기

### 로컬에서 실행하기
Hugo가 설치되어 있어야 합니다. ([설치 가이드](https://gohugo.io/installation/))

```bash
# 저장소 복제 (서브모듈 포함)
git clone --recursive https://github.com/nobe0716/nobe0716.github.io.git
cd nobe0716.github.io

# 로컬 서버 실행 (드래프트 포함)
hugo server -D
```

실행 후 `http://localhost:1313`에서 확인할 수 있습니다.

### 새로운 포스트 작성하기
아래 명령어를 통해 새로운 포스트를 생성할 수 있습니다. (archetype 기반)

```bash
hugo new posts/your-post-title.md
```

생성된 파일은 `content/posts/` 폴더에 위치하며, 상단의 `front matter`를 수정한 후 내용을 작성하시면 됩니다.

## 🛠 구성 정보

- **정적 사이트 생성기**: [Hugo](https://gohugo.io/)
- **테마**: [PaperMod](https://github.com/adityatelange/hugo-PaperMod)
- **배포**: GitHub Actions를 통해 `main` 브랜치 푸시 시 자동 배포 (GitHub Pages)
- **퍼마링크**: `/posts/:slug/` 구조를 사용하여 날짜에 의존하지 않는 깔끔한 URL 유지

## 🔍 SEO 및 최적화

- **기본 지원**: Sitemap, robots.txt, RSS 피드
- **메타 데이터**: Open Graph, Twitter Cards 지원
- **검색 엔진**: Google Search Console 등록 준비 완료 (hugo.yaml의 `googleAnalyticsID` 등 추가 가능)
- **속도**: 매우 가볍고 빠른 테마를 사용하여 모바일/데스크톱 가독성 극대화

## 📁 디렉토리 구조

- `archetypes/`: 포스트 템플릿 정의
- `content/`: 블로그 포스트 및 페이지 (Markdown)
- `themes/`: 블로그 테마 (PaperMod)
- `hugo.yaml`: 사이트 전반의 설정 파일
- `.github/workflows/`: GitHub Actions 자동 배포 설정

## 📝 라이선스
이 블로그의 콘텐츠는 특별한 명시가 없는 한 저작권의 보호를 받습니다.
