# STRUCTURE · studio13-sample

```
studio13-sample/
├─ index.html                 단일 파일 (CSS · JS 인라인)
├─ wrangler.toml              name = studio13-sample → studio13-sample.lgt3232.workers.dev
├─ .assetsignore              img/ · _old/ · 문서 · index_*.html · _deploy 배포 제외
├─ s13-outfit.woff2           영문 제목 (Outfit 400–700, 쓰는 글자만)
├─ s13-dmmono.woff2           프레임 번호 (DM Mono 400, 대문자 포함)
├─ s13-pretendard.woff2       한글 · 본문 (Pretendard 400–700, 페이지 글자 전부)
├─ s13-logo.svg               워드마크 (잉크 #2C2C2C, potrace 벡터)
├─ s13-p01 ~ s13-p09.webp     인물 9장 (800×1000, 히어로 슬라이드 5장 · 컨택트 시트 9장)
├─ s13-inst1 ~ s13-inst4.webp 인스턴트 4장 (inst1 = 남성 4인 묶음)
├─ favicon.png · og-s13.jpg
├─ img/                       다올 제공 원본 23장 (배포 제외 · 미성년자 가능 사진 · 다른 브랜드 로고 포함, 레포에 올리지 말 것)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더 → 히어로 → `#sheet` → `#instant`(어두운 바탕) → `#info` → `#visit` → 푸터 + 모바일 `.quick`(nav).

## 링크 한곳 정리
- 네이버 플레이스 `m.place.naver.com/place/1662992653/home`: 헤더 · 히어로 · Info · 하단 바
- 네이버 길찾기 `map.naver.com/p/entry/place/1662992653`: Visit
- 인스타 `https://www.instagram.com/studio13_profile/`: 히어로 · 시트 마지막 칸 · Visit · 푸터 · 하단 바
- 전화 `tel:050713448356`: Info · Visit · 푸터 · 하단 바

## 폰트 재생성
문구 바꾸면 빠진 글자 검사(LESSONS §26). 본문 첫 폰트가 Pretendard라 영문 · 숫자도 Pretendard 서브셋에 들어가야 함. DM Mono는 대문자 변환이 걸려 있어 대문자도 포함.
