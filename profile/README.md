# 몽글 (Mongle) - 프로젝트 소개

<img width="2007" height="1365" alt="image" src="https://github.com/user-attachments/assets/20ab6ec7-6a40-4680-8c78-601454dd9fc8" />

---

## 프로젝트 소개

**몽글**은 AI 기반 그림동화 창작 플랫폼입니다.

아이들이 직접 상상한 이야기를 입력하면, AI가 텍스트를 다듬고 아름다운 삽화를 생성하여 세상에 단 하나뿐인 나만의 그림동화책을 완성해 줍니다.

### 기획 배경

스마트폰과 태블릿이 일상이 된 지금, 아이들은 영상 콘텐츠를 수동적으로 소비하기만 합니다. 몽글은 **"아이들이 디지털 기기를 창의적인 도구로 활용할 수는 없을까?"** 라는 고민에서 출발했습니다.

### 주요 기능

| 기능 | 설명 |
|------|------|
| **AI 동화 생성** | 4단계 위자드(템플릿 선택 → 그림체 선택 → 페이지 수 설정 → 제목 입력)를 통해 동화를 생성 |
| **다양한 그림체** | 수채화, 유화, 스케치, 3D, 애니메이션 등 다양한 일러스트 스타일 지원 |
| **동화 갤러리** | 다른 사용자들이 만든 동화를 탐색하고 읽을 수 있는 커뮤니티 공간 |
| **소셜 로그인** | 카카오, 네이버 OAuth2 소셜 로그인 지원 |
| **작가/독자 대시보드** | 작가는 조회수·평점 통계, 독자는 읽기 진행률·목표 관리 |
| **내 서재** | 좋아요한 동화와 내가 만든 동화 모아보기 |
| **프로필 관리** | 프로필 이미지 업로드, 닉네임·자기소개 수정 |
| **안전한 콘텐츠** | AI 콘텐츠 필터링으로 아이들에게 부적합한 내용 사전 차단 |

### 기술 스택

**Frontend**

| 분류 | 기술 |
|------|------|
| Framework | React 19 + TypeScript 5.8 |
| Build Tool | Vite 6.2 |
| Styling | Tailwind CSS 4.1 |
| Routing | React Router DOM 7.13 |
| Animation | Motion 12 (Framer Motion) |
| AI | Google Generative AI |

**Backend**

| 분류 | 기술 |
|------|------|
| Framework | Spring Boot 4.0.5 (Java 21) |
| Database | PostgreSQL 16 |
| Cache | Redis |
| Storage | MinIO (S3 호환 오브젝트 스토리지) |
| Security | Spring Security + JWT + OAuth2 |
| Architecture | DDD + Hexagonal Architecture |
| API 문서 | SpringDoc OpenAPI (Swagger) |

**Infra**

| 분류 | 기술 |
|------|------|
| Server | WSL 홈서버 (Nginx 리버스 프록시) |
| CI/CD | GitHub Actions → SSH 배포 |
| Domain | mongle.cloud |
| Image CDN | img.mongle.cloud (MinIO) |

---

## 프로젝트 인원 소개

<table>
  <tr>
    <td align="center">
      <img src="프로필이미지URL" width="150" height="150" style="border-radius: 50%;" alt="CHYJ0609" /><br />
      <a href="https://github.com/CHYJ0609"><b>CHYJ0609</b></a><br />
      <sub>Full-Stack</sub><br />
      <sub>프론트, 백엔드<br />인프라 (Nginx, MinIO, CI/CD)</sub>
    </td>
    <td align="center">
      <img src="프로필이미지URL" width="150" height="150" style="border-radius: 50%;" alt="kimsoi" /><br />
      <a href="https://github.com/kimsoi"><b>kimsoi</b></a><br />
      <sub>Backend</sub><br />
      <sub>백엔드 API 개발, 도메인 설계</sub>
    </td>
    <td align="center">
      <img src="프로필이미지URL" width="150" height="150" style="border-radius: 50%;" alt="leeys" /><br />
      <a href="https://github.com/leeys"><b>leeys</b></a><br />
      <sub>Backend</sub><br />
      <sub>백엔드 API 개발, 도메인 설계</sub>
    </td>
  </tr>
</table>


---

## 사이트

| 항목 | URL |
|------|-----|
| **서비스** | [https://mongle.cloud](https://mongle.cloud) |
| **이미지 CDN** | [https://img.mongle.cloud](https://img.mongle.cloud) |
