# 기여 가이드

AI Slop Blocklist에 기여해주셔서 감사합니다! 🙏

## 채널 추가하기

### 1. Fork & Clone
```bash
git clone https://github.com/YOUR_USERNAME/aislop.git
cd aislop
```

### 2. blocklist.json 수정
```json
{
  "id": "channel_handle",      // @handle 또는 채널 ID
  "name": "채널명",
  "reason": "신고 사유",
  "addedAt": "2026-01-31",
  "reportCount": 1,
  "category": "news"           // news, celebrity, finance, health, other
}
```

### 3. Pull Request
- 제목: `[추가] @channel_handle - 채널명`
- 본문: 해당 채널이 AI Slop인 증거 (영상 링크 등)

## 주의사항

- 개인 채널이 아닌 **AI 생성 콘텐츠 채널만** 신고
- 중복 확인 후 추가
- 증거 없는 신고는 반려됩니다

## 잘못된 등록 수정

잘못 등록된 채널은 Issue 또는 PR로 알려주세요.
