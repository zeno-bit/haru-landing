# 하루 — Landing Site

[하루](https://github.com/zeno-bit/Haru) iOS · iPadOS · macOS 일기 앱의 마케팅 / Privacy Policy 사이트.

GitHub Pages로 호스팅: `https://zeno-bit.github.io/haru-landing/`

## 구조

- `index.html` — 랜딩 페이지 (기능 소개 + 개인정보 callout)
- `privacy-policy.html` — 개인정보처리방침 (한 / 영)
- `style.css` — Apple-like 디자인, 다크모드 자동 적응
- `logo.png` — 앱 아이콘 (512×512)

## 로컬 미리보기

```bash
python3 -m http.server 8000
# http://localhost:8000
```

## 배포

main 브랜치에 push하면 GitHub Pages가 자동 배포 (Settings → Pages → Source: main / root).
