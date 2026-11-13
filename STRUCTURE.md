# STRUCTURE · studio13-sample (v0.2 · 사장님 안내판 구성)

```
studio13-sample/
├─ index.html                 단일 파일 (CSS · JS 인라인)
├─ wrangler.toml              name = studio13-sample → studio13-sample.lgt3232.workers.dev
├─ .assetsignore              img/ · _old/ · 문서 · index_*.html · _deploy 배포 제외
├─ s13-outfit.woff2           메뉴 제목 ID PHOTO · POLAROID (Outfit 700, 영문 · 대문자)
├─ s13-bodoni.woff2           안내 제목 RESERVATION · CHANGE & CANCEL · LOCATION (Bodoni Moda 400)
├─ s13-notoserif.woff2        한글 명조 · 메뉴 이름 · 가격 · 설명 (Noto Serif KR 400–600, 페이지 글자 전부)
├─ s13-pretendard.woff2       버튼 · 작은 글씨 (Pretendard 400–700, 페이지 글자 전부)
├─ s13-logo.svg               워드마크 (잉크 #2C2C2C, potrace 벡터)
├─ s13-p01 ~ s13-p09.webp     인물 9장 (800×1000) · 히어로 p01 · p03 · p02 / 증명사진 p08 · p07 · p04 / 세미화보 p06 · p09 · p05
├─ s13-inst2 ~ s13-inst4.webp 와이드 폴라로이드 3장
├─ favicon.png · og-s13.jpg
├─ img/                       다올 제공 원본 23장 (배포 제외 · 미성년자 가능 사진 · 다른 브랜드 로고 포함, 레포에 올리지 말 것)
└─ CHANGELOG.md / STRUCTURE.md
```
※ 모든 서브셋은 공백 U+0020 · U+00A0 포함(R-6).

## 섹션 순서 (사장님 안내판 순서)
헤더 → 히어로 → `#id-photo` → `#polaroid` → `#reservation` → `#cancel` → `#location` → 푸터 + 모바일 `.quick`(nav).

## 링크 한곳 정리
- 카카오톡(예약 · 주 버튼) `https://pf.kakao.com/_xblFvK`: 헤더 · 히어로 · RESERVATION · 하단 바 · JSON-LD sameAs
- 전화 `tel:050713448356`: RESERVATION 당일 예약 박스 · LOCATION · 푸터 · 하단 바
- 네이버 길찾기 `map.naver.com/p/entry/place/1662992653`: LOCATION
- 네이버 플레이스 `m.place.naver.com/place/1662992653/home`: JSON-LD sameAs
- 인스타 `https://www.instagram.com/studio13_profile/`: 히어로 · LOCATION · 푸터

## 폰트 재생성
문구 바꾸면 빠진 글자 검사(LESSONS §26). 한글은 명조(Noto Serif KR)와 Pretendard 둘 다에 들어가야 함. 영문 제목 폰트 2종은 대문자 변환이 걸려 있어 대문자 포함.
