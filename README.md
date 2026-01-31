# AI Slop Blocklist 🚫

유튜브에서 AI 생성 저품질 콘텐츠(AI Slop)를 공유하는 커뮤니티 블랙리스트입니다.

## 사용 방법

### 확장프로그램 설치
1. [AI Slop Blocker 크롬 확장프로그램](https://github.com/KibumA/ai-slop-blocker) 설치
2. 확장프로그램이 자동으로 이 목록을 불러와 해당 채널을 필터링합니다

### 직접 조회
[blocklist.json](./blocklist.json) 파일에서 현재 등록된 채널 목록을 확인할 수 있습니다.

---

## 채널 신고하기

AI Slop 의심 채널을 발견하셨나요? 다음 방법으로 신고해주세요:

### 방법 1: Issue 등록 (쉬움)
[New Issue](../../issues/new?template=report_channel.yml) 클릭 후 채널 정보 입력

### 방법 2: Pull Request (권장)
1. 이 저장소 Fork
2. `blocklist.json`에 채널 추가
3. Pull Request 생성

---

## 블랙리스트 기준

다음 기준에 해당하는 채널을 등록합니다:

- ✅ AI 음성(TTS)으로 제작된 뉴스 형식 영상
- ✅ 자극적인 썸네일 + 내용 없는 영상
- ✅ 하루 10개 이상 기계적 업로드
- ✅ 유명인 딥페이크/AI 생성 영상

---

## 카테고리

| 코드 | 설명 |
|------|------|
| `news` | 가짜 뉴스/속보 |
| `celebrity` | 연예인 AI 생성 영상 |
| `finance` | 투자/재테크 사기 |
| `health` | 건강/의료 허위정보 |
| `other` | 기타 |

---

## 면책 조항

이 목록은 커뮤니티 기여를 기반으로 합니다. 잘못 등록된 채널이 있다면 Issue를 통해 알려주세요.

## 라이선스

MIT License