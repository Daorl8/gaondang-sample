# STRUCTURE · gaondang-sample (v0.3 · 따뜻하고 고급스러운 대형 베이커리 카페)

```
gaondang-sample/
├─ index.html                 단일 파일 (CSS·JS 인라인)
├─ wrangler.toml              name = gaondang-sample → gaondang-sample.lgt3232.workers.dev (Worker 이름도 같게)
├─ .assetsignore              img/ · _old/ · 문서 · index_*.html · _deploy 배포 제외
├─ gd-hahmlet.woff2           제목 (함렛 500 고정, 쓰는 글자만)
├─ gd-pretendard.woff2        본문 (Pretendard 400–700, 쓰는 글자만)
├─ gd-logo.webp               컬러 전체 로고 (히어로 · 푸터)
├─ gd-icon.webp / gd-icon-w.webp   아이콘 주황(헤더) · 흰색(나눔 짙은 면)
├─ gd-display.webp            히어로 진열대
├─ gd-ciabatta.webp           새벽의 빵
├─ gd-shelf / mango / cream / pecan / crumble .webp   오늘의 진열대
├─ gd-seat / overview / stair .webp                    공간 (와이드 · 내려다본 진열대 · 계단)
├─ favicon.png · og-gaondang.jpg
├─ img/                       다올 제공 원본 43장 (배포 제외)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더 → 히어로(아이보리) → `#dawn` → `#case`(크림) → `#share`(짙은 원목) → `#space` → `#visit`(크림) → 푸터(아이보리) + 모바일 `.quick`.

## 색 규칙 (v0.3)
아이보리 #F8F4EE · 크림 #F0E9DF · 먹 #2B211B · 원목 브라운 #7A5536(라벨 · 번호) · 짙은 원목 #3B2B21(나눔 면만).
주황 #E7501B는 로고만, 채움 버튼 · 하단 바는 #C84012(흰 글자 5.0:1). 주황 큰 면 없음.

## 링크
- 길찾기 `map.naver.com/p/entry/place/2015276527` · 전화 `032-876-8988` · 인스타 `@gaondang_bakery`

## 그리드
v0.3에서 손댄 그리드는 `minmax(0, …)`(LESSONS §27).

## 폰트 재생성
문구 바꾸면 빠진 글자 검사(LESSONS §26). 함렛 · Pretendard 두 서브셋 모두 다시.
