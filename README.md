### 🛠 Tech Stack

**Game Engine & Graphics**  
![Unity](https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![OpenGL](https://img.shields.io/badge/OpenGL-5586A4?style=for-the-badge&logo=opengl&logoColor=white)

**Web & Collaboration**  
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

### 📌 Quick Repository Links (클릭 시 상세 README로 이동)

<table>
  <tr>
    <td>
      <a href="https://github.com/thdrlghks/unity3D-BoneToBeKing">
        <img src="https://github-readme-stats.vercel.app/api/pin/?username=thdrlghks&repo=unity3D-BoneToBeKing&theme=tokyonight" alt="unity3D-BoneToBeKing" />
      </a>
    </td>
    <td>
      <a href="https://github.com/thdrlghks/DinosaurRPS">
        <img src="https://github-readme-stats.vercel.app/api/pin/?username=thdrlghks&repo=DinosaurRPS&theme=tokyonight" alt="DinosaurRPS" />
      </a>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/thdrlghks/unity2D-REMIX">
        <img src="https://github-readme-stats.vercel.app/api/pin/?username=thdrlghks&repo=unity2D-REMIX&theme=tokyonight" alt="unity2D-REMIX" />
      </a>
    </td>
    <td>
      <a href="https://github.com/thdrlghks/SmartLinkWeb">
        <img src="https://github-readme-stats.vercel.app/api/pin/?username=thdrlghks&repo=SmartLinkWeb&theme=tokyonight" alt="SmartLinkWeb" />
      </a>
    </td>
  </tr>
</table>

---

### 🎮 Featured Game Projects & Troubleshooting

#### 1. BONE TO BE KING — 3D 액션 RPG (`Unity 6` / `C#`)
* 👉 **[상세 README 및 코드 보러가기](https://github.com/thdrlghks/unity3D-BoneToBeKing)**
* **프로젝트 개요**: 지형지물을 활용하는 파쿠르 이동과 3종 무기(검·활·폭탄) 스위칭, 선입력 콤보 시스템을 구현한 3인칭 액션 RPG (2인 팀 프로젝트)
* **핵심 구현 및 트러블슈팅**
  * **Dual Raycast 파쿠르 알고리즘**: 초기 `Trigger Collider` 판정의 벽 뚫림·미끄러짐 한계를 해결하기 위해 전방 벽 검사와 상단 착지 평지 검사를 결합한 `Dual Raycast`로 구조를 개선하고, 보간 이동 및 상태 제어(`isClimbing`)를 적용해 등반 정밀도 확보
  * **객체지향 무기 스위칭 & 선입력 전투**: `W_Base` 상속 구조로 3종 무기를 확장성 있게 설계하고, 공격 중 입력 버퍼를 저장하는 **콤보 선입력**과 **선·후딜레이 타이밍 조정**으로 조작감·타격감 극대화
  * **3인칭 숄더뷰 카메라 & 상태 동기화**: 수직 각도 클램핑과 지형 가림 보정 카메라, 행동 상태별 입력 차단을 통해 애니메이션과 로직의 일관성 유지

---

#### 2. DinosaurRPS — 사이드뷰 격투 카메라 & 심리전 게임 (`Unity` / `C#`)
* 👉 **[상세 README 및 코드 보러가기](https://github.com/thdrlghks/DinosaurRPS)**
* **프로젝트 개요**: 사이드뷰 격투 게임 스타일의 카메라 구도와 가위바위보 메커니즘을 결합한 액션 심리전 게임
* **핵심 구현 내용**
  * 양 플레이어 간 거리에 따라 동적으로 줌인·줌아웃되는 사이드뷰 격투 카메라 트래킹 및 연출 구현
  * 공격·방어·상성 판정에 따른 상태 전이 및 타격 피드백 시스템 설계

---

#### 3. REMIX — 턴제 퍼즐 액션 게임 (`Unity` / `C#`)
* 👉 **[상세 README 및 코드 보러가기](https://github.com/thdrlghks/unity2D-REMIX)**
* **프로젝트 개요**: 제한된 턴 수 내에 장애물과 기믹을 돌파하는 '헬테이커' 오마주 2D 그리드 기반 퍼즐 액션 게임
* **핵심 구현 내용**
  * 그리드(격자) 좌표 기반 이동 판정, 오브젝트 밀기·함정 상호작용 로직 및 턴 카운트 상태 관리 구현

---

#### 4. C++ & OpenGL 3D Graphics / Multi-Genre Prototypes (`C++` / `OpenGL` / `Unity`)
* 👉 **[전체 레포지토리 목록 보기](https://github.com/thdrlghks?tab=repositories)**
* **C++ & OpenGL 3D 그래픽스**: 3D 공간 변환, 쿼터니언 회전, 계층적(Skeletal) 캐릭터 애니메이션, GLSL 셰이더 조명·그림자 매핑 및 포켓몬 턴제 전투 애니메이션 연출 구현
* **기타 Unity 프로토타입**: 3D 휠체어 공포 게임(관성·경사로 물리 및 래그돌), 3D 방탈출 공포 게임, 3D 헨젤과 그레텔, 2D 쿼터뷰 로그라이크 등 다장르 구현

---

### 🌐 Web & AI Engineering Projects

#### 5. SmartLinkWeb — 반도체 후공정(Singulation) 모니터링 대시보드 & AI 리포트 (`React` / `TypeScript` / `Spring Boot`)
* 👉 **[상세 README 및 코드 보러가기](https://github.com/thdrlghks/SmartLinkWeb)**
* **프로젝트 개요**: 반도체 절단 공정 데이터 실시간 시각화 대시보드 및 Gemini API 기반 일일 분석 PDF 리포트 자동 생성 웹 서비스 (캡스톤 프로젝트)
* **핵심 구현 내용**: 공정 데이터 모니터링 UI/UX 아키텍처 설계 및 백엔드 API·AI 자동 요약 리포트 파이프라인 연동

#### 6. 자연어 처리 기반 웹 서비스 (`React` / `TypeScript`)
* 👉 **[상세 README 및 코드 보러가기](https://github.com/thdrlghks/2025_8_H_FE)**
* **프로젝트 개요**: 자연어 처리(NLP) 기능을 활용한 웹 애플리케이션 프론트엔드 구축 프로젝트
* **핵심 구현 내용**: 사용자 입력 처리 인터페이스 설계 및 비동기 데이터 상태 관리 구현

---

### 🤝 Collaboration & Engineering Principles
* **일관된 플레이 경험 우선**: 기능 구현 이후 다양한 예외 상황과 입력 타이밍을 반복 테스트하여 끊김 없는 조작감을 완성합니다.
* **병합과 확장을 고려한 설계**: 초기 단계부터 역할과 인터페이스를 명확히 구분하고, 팀원과의 코드 병합 및 유지보수를 고려해 구조를 설계합니다.
