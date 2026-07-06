# 아이랩아트 홈페이지

> Creative Art Lab for Kids — 청담 영어미술·키즈아트 아틀리에

미술과 영어가 만나는 창의적 아트 랩, **아이랩아트** 공식 홈페이지입니다.  
GitHub Pages로 **무료** 호스팅할 수 있습니다.

## 도메인 안내

| 옵션 | 비용 | URL 예시 |
|------|------|----------|
| GitHub Pages 기본 | **무료** | `username.github.io/ilabart` |
| 커스텀 도메인 | **연 1~2만원** | `ilabart.kr`, `ilabart.com` |

커스텀 도메인은 **필수는 아닙니다**. GitHub 무료 URL로도 Google 검색 등록이 가능합니다.  
다만 브랜드 신뢰도와 기억하기 쉬운 주소를 위해 `.kr` 또는 `.com` 구매를 권장합니다.

## GitHub Pages 배포 방법

### 1. GitHub 저장소 생성

```bash
git init
git add .
git commit -m "아이랩아트 홈페이지 초기 배포"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/ilabart.git
git push -u origin main
```

### 2. GitHub Pages 활성화

1. GitHub 저장소 → **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` / `/ (root)`
4. Save

### 3. 커스텀 도메인 연결 (선택)

1. DNS A 레코드: `185.199.108.153` 등 GitHub Pages IP
2. `CNAME` 파일에 도메인 입력
3. GitHub Pages Settings → Custom domain 입력 → Enforce HTTPS

## Google 검색 등록

1. [Google Search Console](https://search.google.com/search-console) 접속
2. 사이트 URL 등록 및 소유권 확인
3. Sitemap 제출: `https://your-domain/sitemap.xml`

## 사진 추가

`assets/images/` 폴더에 `hero.jpg`, `studio-1.jpg`, `class-1.jpg` 등 추가

## 연락처

- **주소**: 서울 강남구 학동로101길 11, 엘프론트 청담 410호
- **전화/문자**: 010-9264-2035
- **Instagram**: [@i.lab_art](https://www.instagram.com/i.lab_art)
