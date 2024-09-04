### **커밋 규칙**

<이모지> <타입>: <제목> 의 형식으로 제목을 아래 공백줄에 작성
제목은 50자 이내 / 변경사항이 "무엇"인지 명확히 작성 / 끝에 마침표 금지
예) ✨ feat: 사용자 로그인 기능 추가

바로 아래 공백은 지우지 마세요 (제목과 본문의 분리를 위함)

본문(구체적인 내용)을 아랫줄에 작성
여러 줄의 메시지를 작성할 땐 "-"로 구분 (한 줄은 72자 이내)

📌 **커밋 작성 규칙**

- 🐛 fix: 버그 수정
- 🎨 style: 코드 포맷팅, 세미콜론 누락 등 문법 관련 수정
- 🔨 chore: 빌드 업무 수정, 패키지 매니저 설정 등
- 🎉 init: 프로젝트 초기 설정 및 초기 커밋
- ➕ plus: 의존성 추가
- ➖ minus: 의존성 제거
- ⚙️ config: 설정 파일 수정
- 📝 docs: 문서 수정
- 🚀 deploy: 배포 관련 커밋
- 🔥 remove: 코드/파일 삭제
- 🧪 test: 테스트 코드 추가/수정
- 🚧 wip: 작업 진행 중인 커밋

### **브랜치 규칙**

- **Feature**: 새로운 기능을 개발하기 위한 브랜치입니다.
- **Hotfix**: 긴급 버그 수정을 위한 브랜치입니다.
- **Release**: 배포 준비를 위한 브랜치입니다.
- **Refactor**: 코드 리팩토링을 위한 브랜치입니다.

📌 **브랜치명 규칙**

- **Feature 브랜치**: `feat/feature-name` (예: `feat/user-authentication`)
- **Hotfix 브랜치**: `fix/hotfix-description` (예: `fix/urgent-login-bug`)
- **Release 브랜치**: `release/release-version` (예: `release/1.0.0`)
- **Refactor 브랜치**: `refactor/refactor-description` (예: `refactor/code-cleanup`)
