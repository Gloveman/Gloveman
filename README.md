<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,45:2563EB,100:14B8A6&height=220&section=header&text=Gloveman&fontColor=F8FAFC&fontSize=56&fontAlignY=36&desc=AI%20Backend%20Engineer%20%7C%20Data%20to%20Agent%20Workflow&descAlignY=56&animation=fadeIn)

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=20&duration=2600&pause=800&color=38BDF8&center=true&vCenter=true&width=760&lines=Public+Data+%E2%86%92+ML+%E2%86%92+RAG+%E2%86%92+Recommendation+%E2%86%92+Agent;Designing+backend+systems+that+connect+AI+with+real+workflows;Building+reliable+pipelines%2C+APIs%2C+and+agentic+services)](https://git.io/typing-svg)

<br/>

<b>지속적인 몰입을 통해 탄탄한 백엔드와 AI 아키텍처를 설계하고자 하는 개발자입니다.</b>

데이터 수집과 DB 설계에서 시작해 머신러닝 예측 모델, RAG 서비스, 개인화 추천 시스템, LangGraph 기반 Agent Workflow까지 구현하며  
AI가 실제 서비스 흐름 안에서 안정적으로 동작하는 구조를 탐구하고 있습니다.

<br/>

<a href="mailto:bule3306@naver.com">
  <img src="https://img.shields.io/badge/Contact-Naver-03C75A?style=for-the-badge&logo=naver&logoColor=white" />
</a>
<a href="https://velog.io/@bule3306">
  <img src="https://img.shields.io/badge/Tech%20Blog-Velog-20C997?style=for-the-badge&logo=velog&logoColor=white" />
</a>
<a href="https://gloveman.notion.site/My-personal-study-note-2ee0b3f090cb80e2a9a6f0945f8f0326">
  <img src="https://img.shields.io/badge/Study%20Note-Notion-111111?style=for-the-badge&logo=notion&logoColor=white" />
</a>

</div>

---

## Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>5th. Lovv Agent</h3>
      <p><b>LangGraph 기반 소도시 여행 추천 Agent Workflow</b></p>
      <p>
        사용자의 여행 조건을 구조화하고, 관광지 검색 결과를 근거로 후보 도시를 평가한 뒤,
        일정과 추천 설명을 API 응답 계약에 맞춰 패키징하는 Agent 시스템입니다.
      </p>
      <ul>
        <li>LangGraph StateGraph 기반 Supervisor workflow</li>
        <li>Amazon Bedrock Converse structured output</li>
        <li>Bedrock embedding + S3 Vector 관광지 검색</li>
        <li>DynamoDB 기반 일정 상세 정보 보강</li>
        <li>Candidate Evidence, scoring audit, deterministic Response Packager</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Python-3.12-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/LangGraph-Agent-1F2937?style=flat-square" />
        <img src="https://img.shields.io/badge/AWS-Bedrock%20%7C%20S3%20Vector%20%7C%20DynamoDB-FF9900?style=flat-square&logo=amazonaws&logoColor=white" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>4th. Olfit</h3>
      <p><b>AI 기반 개인화 향수 추천 서비스</b></p>
      <p>
        사용자의 OOTD 이미지를 VLM으로 분석하고 명시적 향 선호를 결합해,
        향수 데이터를 벡터 매칭하는 개인화 추천 서비스입니다.
      </p>
      <ul>
        <li>OOTD 이미지 기반 5축 scent aura score 산출</li>
        <li>NVIDIA NIM Gemma VLM 기반 이미지 감성 분석</li>
        <li>Django REST Framework + React/TypeScript</li>
        <li>MySQL JSONField 기반 반정형 향수 데이터 관리</li>
        <li>Radar chart, report capture, preference-driven recommendation</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Django-REST-092E20?style=flat-square&logo=django&logoColor=white" />
        <img src="https://img.shields.io/badge/React-TypeScript-3178C6?style=flat-square&logo=react&logoColor=white" />
        <img src="https://img.shields.io/badge/VLM-NVIDIA%20NIM-76B900?style=flat-square&logo=nvidia&logoColor=white" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>3rd. Job Pocket</h3>
      <p><b>RAG 기반 AI 자기소개서 초안 및 피드백 서비스</b></p>
      <p>
        취업 준비생의 입력 정보를 구조화하고 채용 공고 데이터를 검색해,
        직무 적합성과 표현력을 함께 개선하는 AI 피드백 서비스를 구현했습니다.
      </p>
      <ul>
        <li>FastAPI backend + Streamlit frontend</li>
        <li>EXAONE 3.5 7.8B 기반 피드백 생성</li>
        <li>Qwen3 Embedding 기반 텍스트 임베딩</li>
        <li>MySQL Vector type 활용 유사도 검색</li>
        <li>Docker Compose 기반 멀티 컨테이너 구성</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
        <img src="https://img.shields.io/badge/RAG-Vector%20Search-6366F1?style=flat-square" />
        <img src="https://img.shields.io/badge/MySQL-Vector-4479A1?style=flat-square&logo=mysql&logoColor=white" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>2nd. Twilkka Malkka ML</h3>
      <p><b>OTT 고객 이탈 예측 머신러닝 프로젝트</b></p>
      <p>
        Netflix 사용자 행동 데이터를 기반으로 이탈 가능성을 예측하고,
        CRM 관점에서 활용 가능한 Streamlit 대시보드를 설계했습니다.
      </p>
      <ul>
        <li>PPM 이론 기반 이탈 요인 분석</li>
        <li>시청 이력 로그를 사용자 단위 feature로 집계</li>
        <li>Logistic Regression, Random Forest, XGBoost 비교</li>
        <li>최종 XGBoost 모델 PR-AUC 0.945 달성</li>
        <li>학습/추론 파이프라인 모듈화</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/scikit--learn-ML-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" />
        <img src="https://img.shields.io/badge/XGBoost-PR--AUC%200.945-EC5E0C?style=flat-square" />
        <img src="https://img.shields.io/badge/Streamlit-Dashboard-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>1st. Mobility FAQ</h3>
      <p><b>목적지 주변 주차장 및 주유소 조회 시스템</b></p>
      <p>
        공공데이터와 실시간 API를 결합해 목적지 반경 내 주차장과 주유소 정보를
        지도와 카드 UI로 제공하는 위치 기반 모빌리티 서비스입니다.
      </p>
      <ul>
        <li>공공데이터 Open API 수집 및 가공</li>
        <li>MySQL 공간 쿼리 기반 반경 필터링</li>
        <li>주유소 가격 정보 실시간 API 연동</li>
        <li>Streamlit 지도 시각화 및 카드 UI</li>
        <li>PM 및 DB/BACK 역할 수행</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Public%20API-Data-0EA5E9?style=flat-square" />
        <img src="https://img.shields.io/badge/MySQL-Spatial%20Query-4479A1?style=flat-square&logo=mysql&logoColor=white" />
        <img src="https://img.shields.io/badge/Streamlit-Map%20UI-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>What I Keep Improving</h3>
      <p><b>프로젝트를 거치며 반복해서 강화한 축</b></p>
      <ul>
        <li>데이터 수집부터 서비스 응답까지 이어지는 pipeline 설계</li>
        <li>API contract, schema, validation 중심의 backend 구현</li>
        <li>RAG와 추천 시스템에서 retrieval quality를 검증하는 습관</li>
        <li>LLM 출력을 그대로 믿지 않고 deterministic packaging으로 마무리하는 구조</li>
        <li>문서, 테스트, task 단위 기록을 통한 재현 가능한 개발 흐름</li>
      </ul>
    </td>
  </tr>
</table>

---

## Tech Stack

<div align="center">

### Backend & API
<img src="https://skillicons.dev/icons?i=python,fastapi,django,flask,nodejs" />

### AI, Data & ML
<img src="https://skillicons.dev/icons?i=pytorch,sklearn,mysql,mongodb" />

### Frontend & Tools
<img src="https://skillicons.dev/icons?i=react,ts,js,html,css,vite,docker,git,github,vscode" />

</div>

---

## Education & Certification

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>Education</h3>
      <table>
        <tr>
          <td width="72px" align="center"><b>POSTECH</b></td>
          <td>
            <b>Computer Science & Engineering</b><br/>
            <sub>2020.02 - 2026.02</sub>
          </td>
        </tr>
        <tr>
          <td width="72px" align="center"><b>SKN</b></td>
          <td>
            <b>SK Networks Family AI Camp 26th</b><br/>
            <sub>2026.01 - Present</sub>
          </td>
        </tr>
      </table>
    </td>
    <td width="50%" valign="top">
      <h3>Certification</h3>
      <table>
        <tr>
          <td width="72px" align="center">
            <img src="https://img.shields.io/badge/Data-Certified-2563EB?style=flat-square" />
          </td>
          <td><b>빅데이터분석기사</b></td>
        </tr>
        <tr>
          <td width="72px" align="center">
            <img src="https://img.shields.io/badge/PCCE-Lv.4-14B8A6?style=flat-square" />
          </td>
          <td><b>PCCE Level 4</b><br/><sub>Score 1000</sub></td>
        </tr>
        <tr>
          <td width="72px" align="center">
            <img src="https://img.shields.io/badge/PCCP-Lv.3-0EA5E9?style=flat-square" />
          </td>
          <td><b>PCCP Level 3</b><br/><sub>Score 700</sub></td>
        </tr>
        <tr>
          <td width="72px" align="center">
            <img src="https://img.shields.io/badge/OPIc-IH-64748B?style=flat-square" />
          </td>
          <td><b>OPIc English</b><br/><sub>Intermediate High</sub></td>
        </tr>
      </table>
    </td>
  </tr>
</table>

<p align="center">
  <img src="https://img.shields.io/badge/Focus-AI%20Backend-0F172A?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Interest-Agent%20Workflow-2563EB?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Strength-Data%20to%20Service-14B8A6?style=for-the-badge" />
</p>

---

## Organizations & Team Work

<div align="center">

<a href="https://github.com/Joraemon-s-Secret-Gadgets">
  <img src="https://avatars.githubusercontent.com/u/273980028?v=4" width="86" />
</a>

<h3>Joraemon's Secret Gadgets</h3>

<p>
  <b>SK Networks AI Camp team organization</b><br/>
  RAG service, recommendation system, and Lovv agent workflow projects
</p>

<p>
  <a href="https://github.com/Joraemon-s-Secret-Gadgets">
    <img src="https://img.shields.io/badge/Organization-Joraemon's%20Secret%20Gadgets-2563EB?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <img src="https://img.shields.io/badge/Public%20Repos-28-14B8A6?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Created-2026.04-64748B?style=for-the-badge" />
</p>

</div>

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>3rd Project</h3>
      <p><b>Job Pocket and RAG playgrounds</b></p>
      <ul>
        <li><a href="https://github.com/Joraemon-s-Secret-Gadgets/3rd_mysql-faiss-retriever-playground">mysql-faiss retriever playground</a></li>
      </ul>
    </td>
    <td width="33%" valign="top">
      <h3>4th Project</h3>
      <p><b>Olfit and recommendation experiments</b></p>
      <ul>
        <li><a href="https://github.com/Joraemon-s-Secret-Gadgets/4th_olfit_connect_playground">olfit connect playground</a></li>
        <li><a href="https://github.com/Joraemon-s-Secret-Gadgets/4th_perfume_crawling_playground">perfume crawling playground</a></li>
      </ul>
    </td>
    <td width="33%" valign="top">
      <h3>Final Project</h3>
      <p><b>Lovv data, backend, docs, and agent</b></p>
      <ul>
        <li><a href="https://github.com/Joraemon-s-Secret-Gadgets/Lovv-agent">Lovv-agent</a></li>
        <li><a href="https://github.com/Joraemon-s-Secret-Gadgets/oh_my_documents">oh_my_documents</a></li>
        <li><a href="https://github.com/Joraemon-s-Secret-Gadgets/oh_my_agents">oh_my_agents</a></li>
      </ul>
    </td>
  </tr>
</table>

<div align="center">

<a href="https://github.com/Joraemon-s-Secret-Gadgets/job-pocket">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Joraemon-s-Secret-Gadgets&repo=job-pocket&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=38BDF8&text_color=CBD5E1&icon_color=14B8A6" />
</a>
<a href="https://github.com/Joraemon-s-Secret-Gadgets/olfit">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Joraemon-s-Secret-Gadgets&repo=olfit&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=38BDF8&text_color=CBD5E1&icon_color=14B8A6" />
</a>

</div>

<br/>

<p align="center">
  <sub>
    GitHub public API does not expose hidden/private organization memberships.
    This section reflects public organization data and public repositories confirmed from GitHub.
  </sub>
</p>

---

## Algorithm Study

<p align="center">
  <a href="https://solved.ac/bule3306">
    <img src="https://mazassumnida.wtf/api/v2/generate_badge?boj=bule3306" />
  </a>
</p>

<p align="center">
  <b>Algorithm Engineering</b>:
  알고리즘 문제 해결 발상과 최적화 과정을 기록하는 repository
</p>

---

## GitHub Activity

<div align="center">

<picture>
  <source
    srcset="https://github-readme-stats.vercel.app/api?username=Gloveman&show_icons=true&hide_border=true&rank_icon=github&theme=tokyonight&bg_color=0D1117&title_color=38BDF8&text_color=CBD5E1&icon_color=14B8A6"
    media="(prefers-color-scheme: dark)"
  />
  <source
    srcset="https://github-readme-stats.vercel.app/api?username=Gloveman&show_icons=true&hide_border=true&rank_icon=github&theme=default&title_color=2563EB&text_color=334155&icon_color=14B8A6"
    media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
  />
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=Gloveman&show_icons=true&hide_border=true&rank_icon=github&theme=tokyonight&bg_color=0D1117&title_color=38BDF8&text_color=CBD5E1&icon_color=14B8A6" />
</picture>

<picture>
  <source
    srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Gloveman&layout=compact&hide_border=true&theme=tokyonight&bg_color=0D1117&title_color=38BDF8&text_color=CBD5E1"
    media="(prefers-color-scheme: dark)"
  />
  <source
    srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Gloveman&layout=compact&hide_border=true&theme=default&title_color=2563EB&text_color=334155"
    media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
  />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Gloveman&layout=compact&hide_border=true&theme=tokyonight&bg_color=0D1117&title_color=38BDF8&text_color=CBD5E1" />
</picture>

</div>

<p align="center">
  <sub>Language stats reflect public repositories and may not represent private or local project work.</sub>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:14B8A6,45:2563EB,100:0F172A&height=120&section=footer" />
</p>
