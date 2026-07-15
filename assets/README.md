# assets 폴더

이 폴더에 랜딩페이지가 참조하는 이미지 파일을 저장하세요.

## 필수 파일

### `hero-title.png` (또는 .webp)
- **참조 위치**: `index.html` 내 `<img src="assets/hero-title.png">`
- **내용**: "Galaxy Z Flip · Z Fold 8 Series" 로고 이미지
- **권장 사양**:
  - 배경: **투명 (PNG)** 또는 다크 톤 배경
  - 해상도: 가로 최소 800px 이상 (Retina 대응 위해 1200~1600px 권장)
  - 파일 크기: 200KB 이하 (WebP로 저장하면 더 작게 가능)
  - 종횡비: 원본 그대로 (CSS에서 `height:auto`로 유지됨)

### `carousel-slide-1.png` (또는 .webp/.jpg)
- **참조 위치**: 캐러셀 섹션 첫 번째 슬라이드
- **내용**: Galaxy Z Fold8 Ultra 공식 제품컷 (첨부 이미지)
- **권장 사양**:
  - 종횡비: 16:9 또는 16:10 (자동 fit)
  - 해상도: 가로 최소 1000px 이상
  - 파일 크기: 300KB 이하 (WebP 권장)
  - 배경: 원본 그대로 (라이트 그레이 배경 등)

## 파일 저장 후 배포
```bash
git add .
git commit -m "이미지 자산 추가"
git push
```
