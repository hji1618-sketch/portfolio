# 안효진 포트폴리오 — 웹 배포 패키지

URL로 접근 가능하게 만드는 배포용 폴더입니다. 파일명을 영문으로 정리하고 내부 링크도 맞춰뒀습니다.

## 폴더 구성
| 파일 | 내용 | 배포 후 URL 예시 |
|---|---|---|
| `index.html` | 메인 포트폴리오 (첫 화면) | `.../` |
| `ai-automation.html` | AI 운영 자동화 종합 케이스 | `.../ai-automation.html` |
| `cover-generator.html` | 표지 자동생성기 상세 케이스 | `.../cover-generator.html` |
| `resume.pdf` | 이력서 | `.../resume.pdf` |
| `career.pdf` | 경력기술서 | `.../career.pdf` |

> `index.html`이 첫 화면이 되도록 이름이 정해져 있습니다. 그대로 올리면 됩니다.

---

## 방법 A. GitHub Pages (안나님 계정 anna09ips 추천)

cover-maker를 이미 올려보셨으니 동일한 방식입니다.

1. GitHub에서 **New repository** → 이름 예: `portfolio` → Public → Create
2. 저장소 화면에서 **Add file ▸ Upload files**
3. 이 `deploy` 폴더 안의 **파일 5개를 드래그**해서 업로드 → **Commit changes**
4. 상단 **Settings ▸ Pages** 이동
5. **Source: Deploy from a branch** → Branch: `main` / 폴더 `/ (root)` → **Save**
6. 1~2분 뒤 페이지 새로고침하면 주소가 뜹니다:
   **`https://anna09ips.github.io/portfolio/`**

수정할 때는 같은 파일을 다시 Upload(덮어쓰기)하면 됩니다.

### 참고
- 한글 폰트(Pretendard)·차트(Chart.js)는 CDN으로 불러오므로 별도 설치 불필요, 인터넷만 되면 정상 표시됩니다.
- 표지 페이지의 라이브 데모 버튼은 기존 `anna09ips.github.io/cover-maker/`로 연결됩니다.

---

## 방법 B. Netlify Drop (가장 빠름, GitHub 불필요)

1. https://app.netlify.com/drop 접속
2. 이 `deploy` 폴더를 통째로 **드래그&드롭**
3. 즉시 임시 URL 발급 (예: `https://random-name.netlify.app`)
4. 로그인하면 URL 이름 변경·유지 가능

---

## 커스텀 도메인(선택)
나중에 `anna.com` 같은 도메인을 연결하고 싶으면 GitHub Pages / Netlify 둘 다 설정에서 지원합니다. 필요하면 안내해 드릴게요.
