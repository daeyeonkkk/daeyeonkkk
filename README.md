<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0ea5e9,50:22c55e,100:f59e0b&height=220&section=header&text=Kim%20Daeyeon&fontSize=54&fontColor=ffffff&fontAlignY=37&desc=AI%20Product%20Builder%20%7C%20Full-stack%20Developer&descSize=18&descAlignY=56&descColor=ffffff&animation=fadeIn" width="100%" alt="Kim Daeyeon header"/>
</p>

<p align="center">
  <a href="https://github.com/daeyeonkkk/DreamCatcher"><img src="https://img.shields.io/badge/AI%20Photo%20Studio-DreamCatcher-0ea5e9?style=for-the-badge" alt="DreamCatcher"/></a>
  <a href="https://github.com/daeyeonkkk/GigaStudy"><img src="https://img.shields.io/badge/Music%20Practice%20Studio-GigaStudy-22c55e?style=for-the-badge" alt="GigaStudy"/></a>
  <a href="https://github.com/daeyeonkkk/Theseus"><img src="https://img.shields.io/badge/Agentic%20Platform-Theseus-f59e0b?style=for-the-badge" alt="Theseus"/></a>
</p>

<p align="center">
  <b>AI 기능을 실제 제품 흐름으로 연결하는 개발자</b><br/>
  모델 호출, API 계약, 사용자 경험, 검증 evidence, 배포/운영 문서를 하나의 작동하는 시스템으로 묶는 일을 좋아합니다.
</p>

---

## About

저는 빠르게 만드는 사람보다, **이어받아 운영할 수 있는 형태로 만드는 사람**이 되고 싶습니다. AI 기능을 붙일 때도 "모델이 답했다"에서 끝내지 않고, 실패했을 때 무엇을 보여줄지, 어떤 contract를 검증할지, 어떤 evidence를 남길지까지 함께 설계합니다.

최근에는 다음 문제들을 많이 다뤘습니다.

- AI workflow를 사용자가 이해할 수 있는 product surface로 감싸기
- frontend, backend, AI runtime, storage, deploy 사이의 contract 정리
- 음악, 이미지, 금융, agent platform처럼 domain logic이 있는 제품을 full-stack으로 구조화
- private source와 public portfolio surface를 분리해 공개 가능한 repo 품질 관리

## Focus

| 관심사 | 제가 신경 쓰는 질문 |
| --- | --- |
| Product Engineering | 사용자는 어떤 모델을 이해해야 하고, 어떤 복잡도는 시스템이 숨겨야 할까? |
| AI Orchestration | LLM/vision/audio 모델 호출을 실패, 재시도, 검수, 운영 흐름까지 어떻게 연결할까? |
| Backend Contract | API schema, storage model, job state, evidence packet을 어떻게 작고 검증 가능하게 만들까? |
| Frontend UX | 복잡한 상태를 설명문 없이도 누를 수 있는 화면으로 어떻게 바꿀까? |
| Public Portfolio | 공개 가능한 코드와 비공개 secret/history의 경계를 어떻게 깔끔히 유지할까? |

## Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/daeyeonkkk/DreamCatcher">DreamCatcher</a></h3>
      <p><b>개인용 프로 사진 편집 Studio</b></p>
      <p>React/FastAPI 기반 Studio가 ComfyUI와 RunPod GPU 환경을 조율하고, seed workflow, model readiness, quality gate, release bundle을 하나의 편집 제품 흐름으로 묶습니다.</p>
      <p>
        <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"/>
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"/>
        <img src="https://img.shields.io/badge/ComfyUI-111827?style=flat-square" alt="ComfyUI"/>
        <img src="https://img.shields.io/badge/RunPod-673ab7?style=flat-square" alt="RunPod"/>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/daeyeonkkk/GigaStudy">GigaStudy</a></h3>
      <p><b>6성부 아카펠라 편곡·연습·채점 Studio</b></p>
      <p>녹음, 업로드, MIDI/MusicXML/PDF import, AI generation 결과를 하나의 shared timeline으로 정리하고, practice waterfall과 pitch/rhythm report로 이어지는 음악 연습 흐름을 만듭니다.</p>
      <p>
        <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"/>
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"/>
        <img src="https://img.shields.io/badge/Audio-0f766e?style=flat-square" alt="Audio"/>
        <img src="https://img.shields.io/badge/Scoring-16a34a?style=flat-square" alt="Scoring"/>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/daeyeonkkk/FINAI">FINAI</a></h3>
      <p><b>AI 기반 맞춤형 금융상품 추천·자산 관리 플랫폼</b></p>
      <p>금융감독원 공개 데이터를 기반으로 예금, 적금, 전세자금대출을 수집하고, 사용자 목적과 자산 정보를 반영해 상품 추천, 가입 상태 관리, 예상 수령액 계산을 제공합니다.</p>
      <p>
        <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" alt="Django"/>
        <img src="https://img.shields.io/badge/DRF-a30000?style=flat-square" alt="DRF"/>
        <img src="https://img.shields.io/badge/Vue_3-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white" alt="Vue 3"/>
        <img src="https://img.shields.io/badge/FinTech-2563eb?style=flat-square" alt="FinTech"/>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/daeyeonkkk/Theseus">Theseus</a></h3>
      <p><b>Agentic development platform</b></p>
      <p>Spring API Server와 FastAPI AI Core를 Kafka event flow로 분리하고, RAG, tool planning, tool execution, billing/history/chat domain의 경계를 설계한 프로젝트입니다.</p>
      <p>
        <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot"/>
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"/>
        <img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" alt="Kafka"/>
        <img src="https://img.shields.io/badge/RAG-7c3aed?style=flat-square" alt="RAG"/>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/daeyeonkkk/SARVIS">SARVIS</a></h3>
      <p><b>AIoT 스마트 모니터링 프로젝트</b></p>
      <p>React Native mobile app, Django/Channels backend, Jetson edge AI, robot arm control을 연결한 SSAFY 팀 프로젝트입니다. 공개 repo에는 실제 파일명 skeleton과 제품 README만 제공합니다.</p>
      <p>
        <img src="https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React Native"/>
        <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" alt="Django"/>
        <img src="https://img.shields.io/badge/Jetson-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="Jetson"/>
        <img src="https://img.shields.io/badge/AIoT-0f172a?style=flat-square" alt="AIoT"/>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/daeyeonkkk/MonET">MonET</a></h3>
      <p><b>Unity Web 기반 금융 교육 러닝 게임</b></p>
      <p>금융 퀴즈를 게임의 전투, 보상, 성장 루프 안에 넣어 사용자가 플레이하면서 저축, 투자, 소비, 위험 감수의 감각을 익히도록 만든 프로젝트입니다.</p>
      <p>
        <img src="https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white" alt="Unity"/>
        <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot"/>
        <img src="https://img.shields.io/badge/Game-9333ea?style=flat-square" alt="Game"/>
        <img src="https://img.shields.io/badge/Education-f59e0b?style=flat-square" alt="Education"/>
      </p>
    </td>
  </tr>
</table>

## Tech Stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React"/>
  <img src="https://img.shields.io/badge/Vue_3-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" alt="Vue 3"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django"/>
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" alt="Kafka"/>
</p>

## GitHub Snapshot

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=daeyeonkkk&show_icons=true&hide_border=true&theme=transparent&title_color=0ea5e9&icon_color=22c55e&text_color=64748b" height="165" alt="GitHub stats"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=daeyeonkkk&layout=compact&hide_border=true&theme=transparent&title_color=0ea5e9&text_color=64748b" height="165" alt="Top languages"/>
</p>

## Contact

<p>
  <a href="mailto:rlaeodus0426@naver.com"><img src="https://img.shields.io/badge/Mail-rlaeodus0426%40naver.com-03C75A?style=for-the-badge&logo=naver&logoColor=white" alt="Mail"/></a>
  <a href="https://github.com/daeyeonkkk"><img src="https://img.shields.io/badge/GitHub-daeyeonkkk-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0ea5e9,50:22c55e,100:f59e0b&height=110&section=footer" width="100%" alt="footer"/>
</p>
