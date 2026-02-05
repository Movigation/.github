<div align="center">

<img src="../assets/movigation_header.png" alt="Movigation Header" width="100%" />

<br/>

[![무비서 소개](https://img.shields.io/badge/무비서_소개-LIVE-2563EB?style=for-the-badge)](https://moviesir.cloud)
[![무비서 B2C](https://img.shields.io/badge/무비서_B2C-DEMO-10B981?style=for-the-badge)](https://demo.moviesir.cloud)
[![무비서 API](https://img.shields.io/badge/무비서_API-B2B-F59E0B?style=for-the-badge)](https://api.moviesir.cloud)
[![무비서 CONSOLE](https://img.shields.io/badge/무비서_CONSOLE-DASHBOARD-8B5CF6?style=for-the-badge)](https://console.moviesir.cloud)

---

## [무비서 (MovieSir)](https://github.com/Movigation/MovieSir)

### **"이동 시간에 딱 맞는 영화 조합을 AI가 추천해 드립니다."**

전 세계 소비자는 시청할 콘텐츠를 검색하는 데 **평균 14분**을 소비하고, 검색에 실패하면 **19%가 시청을 포기**합니다.

무비서는 이동 시간만 입력하면 **AI 하이브리드 추천 엔진(SBERT + ALS)** 이 개인 취향과 러닝타임을 동시에 고려한 최적의 영화 조합을 제안합니다.

<br/>

### 서비스 구성

<table>
  <tr>
    <td width="50%" align="center" valign="bottom">
      <img src="https://raw.githubusercontent.com/Movigation/MovieSir/main/docs/landing_screenshot.png" alt="Landing" width="100%"/>
      <br/><sub><b>무비서 소개</b></sub>
      <br/><sub>서비스 소개 페이지</sub>
    </td>
    <td width="50%" align="center" valign="bottom">
      <img src="https://raw.githubusercontent.com/Movigation/MovieSir/main/docs/demo_screenshot.png" alt="Demo App" width="100%"/>
      <br/><sub><b>무비서 B2C</b></sub>
      <br/><sub>사용자 맞춤 영화 추천 서비스</sub>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="50%" align="center" valign="bottom">
      <img src="https://raw.githubusercontent.com/Movigation/MovieSir/main/docs/api_screenshot.png" alt="API Docs" width="100%"/>
      <br/><sub><b>API 소개</b></sub>
      <br/><sub>External API 문서 및 Swagger</sub>
    </td>
    <td width="50%" align="center" valign="bottom">
      <img src="https://raw.githubusercontent.com/Movigation/MovieSir/main/docs/console-dashboard.png" alt="B2B Console" width="100%"/>
      <br/><sub><b>무비서 Console</b></sub>
      <br/><sub>기업용 API 관리 대시보드</sub>
    </td>
  </tr>
</table>

### 무비서 B2B API 연동 사례: [Air-Demo](https://github.com/Movigation/Air-Demo)

<table>
  <tr>
    <td width="33%" align="center" valign="bottom">
      <img src="https://raw.githubusercontent.com/Movigation/MovieSir/main/docs/air-demo_main.png" alt="Air-Demo 탑승권" width="100%"/>
      <br/><sub><b>탑승권 화면</b></sub>
    </td>
    <td width="33%" align="center" valign="bottom">
      <img src="https://raw.githubusercontent.com/Movigation/MovieSir/main/docs/air-demo_main2.png" alt="Air-Demo 장르 선택" width="100%"/>
      <br/><sub><b>장르 선택</b></sub>
    </td>
    <td width="33%" align="center" valign="bottom">
      <img src="https://raw.githubusercontent.com/Movigation/MovieSir/main/docs/air-demo_main3.png" alt="Air-Demo 영화 추천" width="100%"/>
      <br/><sub><b>영화 추천 결과</b></sub>
    </td>
  </tr>
</table>

<br/>

### 주요 기능

| 기능                   | 설명                                                        |
| ---------------------- | ----------------------------------------------------------- |
| **시간 맞춤 추천**     | 이동 시간을 입력하면 러닝타임 합이 딱 맞는 영화 조합을 추천 |
| **AI 하이브리드 추천** | SBERT(콘텐츠 기반) + ALS(협업 필터링) 2-Track 시스템        |
| **OTT 필터링**         | 구독 중인 OTT 플랫폼에서 바로 볼 수 있는 영화만 추천        |
| **B2B API**            | 항공사, OTT 등 기업 고객을 위한 AI 영화 추천 API 제공       |

<br/>

### 아키텍처

<img src="https://raw.githubusercontent.com/Movigation/MovieSir/main/docs/moviesir_infra_arch1.png" alt="Architecture" width="100%"/>

<br/>

### 레포지토리

| 레포지토리                                             | 설명                            |
| ------------------------------------------------------ | ------------------------------- |
| [**MovieSir**](https://github.com/Movigation/MovieSir) | 메인 프로젝트                   |
| [**Air-Demo**](https://github.com/Movigation/Air-Demo) | 무비서 API 시연용 항공사 데모앱 |

---

## 팀 무비게이션 (Movigation)

### **"Movie + Navigation** - 영화를 향한 길을 안내합니다."

<table>
  <tr>
    <td align="center" width="20%">
      <a href="https://github.com/qkqqkqkq">
        <img src="https://github.com/qkqqkqkq.png" width="100px;" alt=""/>
        <br/><sub><b>문수현</b></sub>
      </a>
      <br/><sub>PM / Database</sub>
    </td>
    <td align="center" width="20%">
      <a href="https://github.com/Dieod1598741">
        <img src="https://github.com/Dieod1598741.png" width="100px;" alt=""/>
        <br/><sub><b>한대연</b></sub>
      </a>
      <br/><sub>Frontend</sub>
    </td>
    <td align="center" width="20%">
      <a href="https://github.com/tinytinalee">
        <img src="https://github.com/tinytinalee.png" width="100px;" alt=""/>
        <br/><sub><b>이승원</b></sub>
      </a>
      <br/><sub>Backend</sub>
    </td>
    <td align="center" width="20%">
      <a href="https://github.com/wldn7601">
        <img src="https://github.com/wldn7601.png" width="100px;" alt=""/>
        <br/><sub><b>박지우</b></sub>
      </a>
      <br/><sub>AI / ML</sub>
    </td>
    <td align="center" width="20%">
      <a href="https://github.com/leelaeloo">
        <img src="https://github.com/leelaeloo.png" width="100px;" alt=""/>
        <br/><sub><b>이태수</b></sub>
      </a>
      <br/><sub>Infra / DevOps</sub>
    </td>
  </tr>
</table>

<br/>

---

<img src="../assets/movigation_footer.png" alt="Movigation Footer" width="100%" />

</div>
