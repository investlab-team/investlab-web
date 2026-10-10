# InvestLab Web — 기술 선정 보류

프론트 구현과 담당은 아직 미정입니다. 백엔드를 먼저 구현하고 별도 프론트 또는 Thymeleaf를 결정합니다. 이 레포는 이슈·PR 템플릿과 협업 구조만 준비하며 React·TypeScript·Node 빌드를 확정하지 않습니다.

Thymeleaf 선택 시 화면은 백엔드의 templates/static에 포함하고 이 레포의 사용 여부를 재검토합니다.

검증: GitHub Conventions 검사 및 이슈 폼 등록. 전체 설계는 backend/docs를 따릅니다.

기본·개발 통합 브랜치는 `dev`입니다. 최신 `dev`에서 작업 브랜치를 만들고 PR도 `dev`로 보냅니다. 회의 설명과 CI 통과 후 작성자가 머지할 수 있습니다. `main`은 릴리스 기준으로 보존하며 반영 시점은 팀 합의 후 별도 PR로 정합니다.
