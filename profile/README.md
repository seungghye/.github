<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

<!-- [![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![project_license][license-shield]][license-url] -->



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/AT-try-angle">
    <img src="./logo.svg" alt="Logo" width="80" height="80">
  </a>

<h1 align="center">Yogiyo-kkikki</h1>

  <p align="center">
   SNS 음식 조합 트렌드와 요기요 내부 데이터를 결합해, 장바구니 단계에서 어울리는 메뉴 조합을 추천하는 배달 커머스 피드 솔루션    <br />
    <a href="http://15.152.162.244/admin"><strong>TryAngle admin 바로가기</strong></a>
    <br />
    <br />
   📋 2026 한이음 드림업 AI 프로젝트 참여<br />
   🏆 2025 CAU 실전 창업 교육 F.A.S.T 1 [대상]<br />
   🏆 2025 2학기 중앙대학교 예술공학대학 과제전 [전체 1등]
  </p>
</div>



<!-- 프로젝트 소개 -->
## 프로젝트 소개

<p align="center">
  <a href="https://youtu.be/4tu52UHVxmA">
    <img src="https://img.youtube.com/vi/4tu52UHVxmA/maxresdefault.jpg" alt="TryAngle 홍보 영상 썸네일" width="720" />
  </a>
  <br />
  <a href="https://youtu.be/4tu52UHVxmA"><strong>홍보 영상 바로가기</strong></a>
</p>

본 프로젝트는 요기요 오라클 해커톤 진행을 위해 시작되었으며, 파편화된 SNS 트렌드 조합 탐색 비용을 줄이고, 내·외부 데이터 결합 추천을 통해 서로 다른 매장 간 연계 주문을 활성화하는 데이터 기반 배달 커머스 피드 솔루션입니다. 

> **프로젝트 기간**: 2026.06.19 - 현재 진행중
>

<p align="right">(<a href="#readme-top">back to top</a>)</p>


### 🎯 주요기능
![TryAngle 이미지 설명](./tryangle-info1.png)

본 프로젝트는 본 프로젝트는 기존 배달앱의 단일 매장 추천 한계를 극복하기 위해 내 • 외부 데이터를 융합한 실시간 조합 추천 엔진을 핵심 차별 방안으로 제안하고자 한다.

**실시간 SNS 트렌드가 반영된 메뉴 조합 추천(외부 데이터 기반)**
-  인스타그램, 틱톡, X(구 트위터) 등 주요 SNS 플랫폼에서 실시간으로 언급량이 급증하는 이색 메뉴 조합 데이터를 수집, 분석하여 이를 바탕으로 메뉴 조합을 사용자에게 추천함. 

**요기요 리뷰 조합 추천(내부 데이터 기반)**
- 요기요 내부에 축적된 방대한 리뷰 텍스트 데이터를 정제, 분석하여, 자주 함께 언급되거나 추천되는 메뉴 조합과 긍정적 추천 문맥을 추출함. 
- 이후 반복 등장하는 조합과 주문 빈도를 통계화하여, 사용자에게 조합 추천을 제공함

**사장님 전용 조합 기능 제공**
- 사용자에게 제공되는 내 • 외부 데이터를 파트너 센터에도 리포트 형태로 제공하여, 가게 사장님이 직접 데이터 기반의 마케팅을 기획할 수 있도록 지원함
-
<p align="right">(<a href="#readme-top">back to top</a>)</p>


### 😎 함께한 사람들
| 이름 | 학교 | 역할 | 참여 기간 | 비고 |
|:---:|:---:|:-------|:---:|:------|
| 조은비 | 중앙대학교 예술공학부 | `백엔드 개발자` | MVP 개발 ~ 현재 | [github](https://github.com/Ebee1205) [블로그](https://wavicle.tistory.com/) |
| 김지현 | 홍익대학교 컴퓨터공학과 | `백엔드 개발자` | MVP 개발 ~ 현재 | [velog](https://velog.io/@hyeoniss/posts) |
| 최승혜 | 중앙대학교 예술공학부 | `PM` `기획` | MVP 개발 ~ 현재 | [블로그](https://somiru03.tistory.com) |
| 이윤서 | 대진대학교 시각디자인과 | `UXUI 디자인` | MVP 개발 ~ 현재 | [포폴](https://www.behance.net/04yunseo) |



<p align="right">(<a href="#readme-top">back to top</a>)</p>


### 📚 기술 스택

![KKIKKI 시스템 아키텍처](./tryangle-info2.png)
KKIKKI 솔루션은

#### **Frontend**
[![Vue][Vue.js-badge]][Vue-url]

#### **Backend**
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
[![Python][Python-badge]][Python-url]
[![FastAPI][FastAPI-badge]][FastAPI-url]
![RabbitMQ](https://img.shields.io/badge/Rabbitmq-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
[![Redis][Redis-badge]][Redis-url]

#### **Business**
![Google Gemini](https://img.shields.io/badge/google%20gemini-8E75B2?style=for-the-badge&logo=google%20gemini&logoColor=white)
Google Trend API

##### DB
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)

##### CI/CD
[![AWS][AWS-badge]][AWS-url]

#### **협업도구**
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-%2334A853?style=for-the-badge&logo=googlesheets&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


### 📝 관련 링크
#### TryAngle 프로젝트 레포지터리
- [GitHub] https://github.com/AT-try-angle
- [GitHub - 목업 사이트] https://github.com/yogiyo-kkikki/kkikki-mock
- [GitHub - 서버] https://github.com/AT-try-angle/try-angle-server

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo_name/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo_name/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo_name/blob/master/LICENSE.txt

[product-screenshot]: images/screenshot.png


[Python-badge]: https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54
[Python-url]: https://www.python.org/
[FastAPI-badge]: https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi
[FastAPI-url]: https://fastapi.tiangolo.com/ko/
[Redis-badge]: https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white
[Redis-url]: https://redis.io/
[MySQL-badge]: https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white
[MySQL-url]: https://www.mysql.com/
[MongoDB-badge]: https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white
[MongoDB-url]: https://www.mongodb.com/

[Vue.js-badge]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Vuetify-badge]: https://img.shields.io/badge/Vuetify-1867C0?style=for-the-badge&logo=vuetify&logoColor=AEDDFF
[Vuetify-url]: https://vuetifyjs.com/

[AWS-badge]: https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white
[AWS-url]: https://aws.amazon.com/
[Github-Pages-badge]: https://img.shields.io/badge/github%20pages-121013?style=for-the-badge&logo=github&logoColor=white
[Github-Pages-url]: https://pages.github.com/
