<img width="1536" height="1024" alt="이거로 결정" src="https://github.com/user-attachments/assets/59d2a751-4444-49db-b411-940caaf96258" />
  
</div>

---

# MyPlanet

다양한 선택지를 통해 매 순간마다 새로운 전략으로 플레이하는 로그라이트 뱀서류 게임

---

## 프로젝트 소개

* 개발 인원 : 개발자 3인, 기획자 3인 (협업 프로젝트)
* 개발 기간 : 2025.11.07 ~ 2026.01.06 (8주)
* 빌드 : Android (Google PlayStore 등록)
* 개발 환경 : Unity 6.x

---

## 기술 스택 / 개발 환경

프로젝트 개발 환경 및 사용 기술

| Category        | Technology           |
| --------------- | -------------------- |
| Engine          | Unity                |
| Language        | C#                   |
| IDE             | Visual Studio Code   |
| Version Control | Git / GitHub         |

---

### 게임 설명

* 몰려오는 적들을 잡아 레벨업하고, 원하는 선택지를 골라 자신이 원하는 플레이 전략을 맞춰나갑니다.
* 모든 웨이브를 버티면서 마지막 보스를 잡아 스테이지를 클리어합니다.
* 메인 로비에서는 더 좋은 전략을 세우기 위해 행성과 타워를 강화하거나 도감에서 등장 확률을 조작할 수 있습니다.

---

## 주요 기능 및 시스템

🛸 행성 & 타워 (Player)

* 조이스틱 기반 행성 이동 시스템
* 공격타워 / 버프타워 등 다양한 역할의 타워 시스템

💀 Enemy

* 다양한 공격과 행동 방식을 가진 적
* 웨이브 기반 적 등장 시스템

⚡ 인게임 플레이

* 레벨업 시 증강 선택지 제공
* 강화 아이템 및 데미지 통계 기능
* 타워 배치 수정 기능으로 전략적 운영 가능

🔧 기타 시스템

* 타워 & 행성 기본 능력치 강화
* 뽑기 / 상점 / 도감 기능
* Firebase 기반 계정 관리 시스템
* 다양한 조작 UI

---

## 구현 파트 정리
<p>
<table align="center" width="100%">
  <tr>
    <td align="top" width="600">
      <b>개발 팀장 (이정환)</b><br><br>
        - Firebase 로그인<br>
        - 타워 증강 눙력 구현<br>
        - 타워 강화 구현<br>
        - 데이터 비동기 로드 작업<br>
        - 상점 구현<br>
        - UI 디자인<br>
        - 테스트 환경 구축
    </td>
    <td align="top" width="600">
      <b>개발 팀원 (서준규)</b><br><br><br>
        - 전투 시스템 (적) 구현<br>
        - 웨이브 기반 스폰 시스템 구현<br>
        - 어드레서블 로드 작업<br>
        - 오브젝트 풀링<br>
        - 행성 레벨 및 성급 강화 구현<br>
        - 타워 및 증강 출현 확률 강화 구현<br>
        - 뽑기 시스템 구현
    </td>
    <td align="top" width="600">
      <b>개발 팀원 (김민주)</b><br><br><br>
        - 요격 및 버프 타워 기능 구현<br>
        - 증강 시스템 구현<br>
        - 타겟팅 시스템 구현<br>
        - 오류 수정<br>
       <br>
    </td>
  </tr>
</table>
</p>

---

## 게임 스크린샷 및 GIF

|  인게임 전투 화면  | 증강 선택지 화면  |  도감 기능  |  타워 강화  |
|  --------------------------------- | ----------------------------------- | --------------------------------- | --------------------------------- |
|  ![](https://github.com/user-attachments/assets/52b3ecf3-1aa7-4fda-ae0a-75db9394975e) |  ![](https://github.com/user-attachments/assets/104af4ac-9b34-4394-8480-36e883fc0979)  | ![](https://github.com/user-attachments/assets/2adfd9eb-5e1f-4bc1-b533-93097babd33e) | ![](https://github.com/user-attachments/assets/86a7001b-c66f-486d-9b41-5bdd462a6eea) |

---
