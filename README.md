<div align="right">
  <img src="https://komarev.com/ghpvc/?username=2dydgh&amp;color=5B8CC9&amp;style=flat-square&amp;label=VISITORS" alt="Profile views" />
</div>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&amp;color=0:263B63,50:466FA8,100:6A94C9&amp;height=190&amp;section=header&amp;text=YongHo%20Lee&amp;fontSize=48&amp;fontColor=E0B36A&amp;fontAlignY=52&amp;stroke=E0B36A&amp;strokeWidth=2&amp;animation=fadeIn" width="100%" alt="YongHo Lee" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;size=24&amp;pause=1800&amp;color=526B8A&amp;center=true&amp;vCenter=true&amp;width=760&amp;height=44&amp;lines=Vision+AI+Engineer;Vision+AI+%C2%B7+Edge+AI;Building+Agentic+AI+Systems" width="100%" alt="Vision AI Engineer / Vision AI · Edge AI / Building Agentic AI Systems" />

<p><strong>모델을 이해하고, 한계를 검증하고, 쓰임을 만듭니다.</strong></p>

<p>이용호 · Dongguk University · South Korea</p>

<p>
  <a href="#research">Research</a> &nbsp; / &nbsp;
  <a href="#selected-projects">Projects</a> &nbsp; / &nbsp;
  <a href="#toolkit">Toolkit</a>
</p>

</div>

---

컴퓨터 비전과 모델 경량화를 연구하고, AI를 활용한 검토·관제·콘텐츠 서비스를 만듭니다.
모델이 **어디에서 실패하는지**, 제한된 자원에서 **어떻게 동작하는지**, 사용자가 **어떤 근거로 결과를 판단할 수 있는지**에 관심이 있습니다.

데이터 전처리와 학습부터 평가, API, 대시보드까지 하나의 흐름으로 구현합니다.

## Research

### KD4SRSS — 가벼운 모델로 더 선명하게 이해하는 장면

**초해상도와 지식 증류를 활용한 경량 시맨틱 세그멘테이션 연구**

고해상도·저해상도 이미지 쌍을 활용해 경량 모델의 장면 분할 성능을 개선하고,
정확도와 연산 효율을 함께 평가했습니다.

| Publication | Edge Inference | Datasets |
| :--- | :--- | :--- |
| **Applied Soft Computing** · Elsevier | **27 FPS** · NVIDIA Jetson TX2 | CamVid · Minicity |

<p>
  <img src="https://img.shields.io/badge/Knowledge_Distillation-263B63?style=flat-square" />
  <img src="https://img.shields.io/badge/Super_Resolution-E0B36A?style=flat-square" />
  <img src="https://img.shields.io/badge/Semantic_Segmentation-6F4E37?style=flat-square" />
  <img src="https://img.shields.io/badge/Edge_AI-2B2B2B?style=flat-square" />
</p>

[코드 보기 →](https://github.com/2dydgh/KD4SRSS)

## Selected Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/2dydgh/Document-review-agent-sytem">
        <img src="https://raw.githubusercontent.com/2dydgh/Document-review-agent-sytem/main/web/public/screenshots/review-screen.png" width="100%" alt="DocSuree" />
      </a>
      <h3>DocSuree</h3>
      <p><strong>문서를 읽고 원문 근거로 검토하는 AI</strong></p>
      <p>문서 검토·비교 결과를 원문 하이라이트와 함께 제공합니다. 인용을 원문과 대조하는 검증 구조를 갖추고, 능동 탐색 Agent로 확장하고 있습니다.</p>
      <p>
        <img src="https://img.shields.io/badge/Python-263B63?style=flat-square" />
        <img src="https://img.shields.io/badge/FastAPI-E0B36A?style=flat-square" />
        <img src="https://img.shields.io/badge/vLLM_%C2%B7_Qwen3-6F4E37?style=flat-square" />
      </p>
      <p><sub>문서 검토 · 근거 검증 · Agent 개발 중</sub></p>
      <p><a href="https://github.com/2dydgh/Document-review-agent-sytem">코드 보기 →</a></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/2dydgh/Agentic-fall-detection-system">
        <img src="https://raw.githubusercontent.com/2dydgh/Agentic-fall-detection-system/main/figures/demo_new.gif" width="100%" alt="Agentic Fall Detection" />
      </a>
      <h3>Agentic Fall Detection</h3>
      <p><strong>영상과 소리로 낙상을 감지하고 대응을 판단하는 관제 시스템</strong></p>
      <p>실시간 감지·알림과 비동기 Agent 분석을 병행합니다. Agent가 사고 이력 조회와 영상 재분석 도구를 선택해 후속 대응을 판단합니다.</p>
      <p>
        <img src="https://img.shields.io/badge/YOLO_Pose-263B63?style=flat-square" />
        <img src="https://img.shields.io/badge/VLM-E0B36A?style=flat-square" />
        <img src="https://img.shields.io/badge/LangGraph-6F4E37?style=flat-square" />
      </p>
      <p><sub>멀티모달 인식 · 실시간 처리 · 도구 선택</sub></p>
      <p><a href="https://github.com/2dydgh/Agentic-fall-detection-system">코드 보기 →</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/2dydgh/Corner-case-bench">
        <img src="https://raw.githubusercontent.com/2dydgh/Corner-case-bench/main/assets/compare_segmentation.png" width="100%" alt="Corner Case Bench" />
      </a>
      <h3>Corner-Case-Bench</h3>
      <p><strong>악조건에서 자율주행 인식 모델이 놓치는 객체를 찾는 벤치마크</strong></p>
      <p>안개·폭우·역광 등 합성 코너 케이스를 생성하고 원본과 변형 이미지의 검출·분할 결과를 비교합니다. 조건별·클래스별 취약성을 대시보드로 확인합니다.</p>
      <p>
        <img src="https://img.shields.io/badge/InstructPix2Pix-263B63?style=flat-square" />
        <img src="https://img.shields.io/badge/YOLOv8-E0B36A?style=flat-square" />
        <img src="https://img.shields.io/badge/Next.js-6F4E37?style=flat-square" />
      </p>
      <p><sub>합성 데이터 · 강건성 평가 · 실패 사례 분석</sub></p>
      <p><a href="https://github.com/2dydgh/Corner-case-bench">코드 보기 →</a></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/2dydgh/Maritime-OSINT-sentry">
        <img src="https://raw.githubusercontent.com/2dydgh/Maritime-OSINT-sentry/main/static/demos/main.png" width="100%" alt="Maritime Sentry" />
      </a>
      <h3>Maritime Sentry</h3>
      <p><strong>선박을 추적하고 충돌 위험을 분석하는 해양 관제 플랫폼</strong></p>
      <p>선박·항공기·위성 데이터를 3D 지도에 통합합니다. 공간 필터링과 XGBoost 기반 충돌 위험 예측을 연결해 위험 상황을 시각화합니다.</p>
      <p>
        <img src="https://img.shields.io/badge/FastAPI-263B63?style=flat-square" />
        <img src="https://img.shields.io/badge/CesiumJS-E0B36A?style=flat-square" />
        <img src="https://img.shields.io/badge/PostGIS-6F4E37?style=flat-square" />
        <img src="https://img.shields.io/badge/XGBoost-212529?style=flat-square" />
      </p>
      <p><sub>실시간 데이터 통합 · 위험 예측 · 지리공간 시각화</sub></p>
      <p><a href="https://github.com/2dydgh/Maritime-OSINT-sentry">코드 보기 →</a></p>
    </td>
  </tr>
</table>

### More Projects

| Project | What it does |
| :--- | :--- |
| **QCNet on ETD**<br>[코드 보기 →](https://github.com/2dydgh/QCNetonETD_PP) | ETRI 주행 데이터로 차량의 미래 이동 경로를 예측합니다. 데이터 분포 보정부터 QCNet 학습·평가·추론까지 연결합니다. |
| **ShortKinds**<br>[코드 보기 →](https://github.com/2dydgh/ShortKinds) | 뉴스 기사를 요약하고 이미지와 내레이션을 생성해 1분 쇼츠로 자동 제작합니다. |

## Toolkit

| Area | Technologies |
| :--- | :--- |
| **Languages** | Python · TypeScript · JavaScript |
| **Vision & ML** | PyTorch · OpenCV · YOLO · XGBoost |
| **LLM & Agents** | LangGraph · LangChain · VLM · vLLM · Ollama |
| **API & Web** | FastAPI · React · Next.js |
| **Data & Infrastructure** | PostgreSQL · PostGIS · Docker · Git |

---

<p align="center">
  <sub>Computer Vision &nbsp; · &nbsp; Model Efficiency &nbsp; · &nbsp; Robustness &nbsp; · &nbsp; Agentic Systems</sub>
</p>
