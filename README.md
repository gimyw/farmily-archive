# farmily-archive

urbanworkteam Farmily 프로젝트 **디컴미션 아카이브** (2026-07-07).
org 소멸 전 5개 레포를 커밋 히스토리 보존(git subtree) 상태로 통합.

| 디렉토리 | 원본 레포 | 설명 |
|---|---|---|
| `Backend/` | urbanworkteam/Backend | REST API (Spring Boot) |
| `Frontend/` | urbanworkteam/Frontend | 모바일 앱 (Expo) |
| `Frontend-web/` | urbanworkteam/Frontend-web | 소비자 웹 (Vite/React) |
| `Infra/` | urbanworkteam/Infra | Terraform + Jenkins + GitOps |
| `AgentCore/` | urbanworkteam/AgentCore | Bedrock AgentCore |

각 서브디렉토리는 원본 레포의 전체 커밋 히스토리를 보존한다(`git log Backend/`).
인프라 설계·운영 문서/PDF는 옵시디언 볼트 `1-Projects/팀-어반워크/디컴미션-아카이브-2026-07-07/` 참조.
