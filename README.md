# TB 공동연구 기밀 문서함

대한결핵협회 × 마이허브 결핵 AI 공동연구 내부 문서의 암호화 사본. 원본과 목록(manifest.txt)은 로컬 `Project_TB/confidential/`에서 관리하고, 이 저장소는 GitHub Pages 배포용이다.

- 뷰어: `index.html` (비밀번호 입력 → 브라우저에서 복호화)
- 암호문: `vault/` (PBKDF2-SHA256 600,000회 + AES-256-GCM)
- 갱신: 상위 폴더에서 `python tools/vault_build.py` 후 여기서 커밋·푸시

평문은 이 저장소에 없다. 비밀번호를 잃으면 복구할 수 없다.
