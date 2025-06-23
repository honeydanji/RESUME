# RESUME

<details>
<summary><b><i>🐬 프로젝트 목록 보기</i></b></summary>
<br>

### 🛠️ <strong>디자인 업무 자동화 (2025.05 ~ 진행중)</strong>
Claude MCP와 Adobe를 활용한 디자인 업무 자동화 프로젝트  
<strong>기술</strong>: Python, Adobe Photoshop  
- Cluade MCP servcer를 구축해서 adobe photoshop에서 진행하는 디자인 업무를 자동화하였음  
- n8n과 mcp, slack을 연결해서 아파트가 등록되면 배너, 안내문, 평면도 등 디자인 업무 자동화 진행  

---

### 🛠️ <strong>서버 마이그레이션 (2025.04 ~ 2025.05)</strong>
API 서버를 Flask에서 FaskAPI로 마이그레이션 프로젝트  
<strong>기술</strong>: FastAPI  
- 기존 프로젝트 안전성 확인을 위해 테스트 커버리지 0% → 85% 달성  
- 비동기 적용을 통해 API 응답 속도 개선  
- SQLArchemy 1.0 → 2.0 업그레이드  

---

### 🛠️ <strong>Amazon EKS 기반 MLOps 인프라 비용 최적화 (2025.03 ~ 2025.04)</strong>
Karpenter와 Knative를 이용한 서버 비용 최소화 프로젝트  
<strong>기술</strong>: Amazon EKS, Kubernetes  
  - 워크로드 특성에 따라 동적 정적 노드그룹으로 분류하고, 유휴 상태인 서비스 파드를 제로 스케일 적용 및 이벤트 기반 노드 운영을 통해 서버 운영 비용 50~90% 절감하였습니다  

<strong>저장소 링크</strong>:  

---

### 🛠️ <strong>아파트 하자 분류 AI 서비스 (2024.04 ~ 2025.03)</strong>
아파트 하자 분류 AI 서비스 MLOps 인프라 구축 프로젝트  
<strong>기술</strong>: Amazon EKS, Kubernetes, Kubeflow, Argo, Grafana  
  - SageMaker → KServe 마이그레이션으로 운영 비용 최소 50% 절감 및 aws 종속성 제거  
  - 추론 서버를 서버리스 형식 구축 및 운영을 통해 추론 비용 추가 절감  
  - Kubeflow 기반 ML 파이프라인 자동화 (데이터 수집, 전처리, 학습, 배포) 구축  
  - gitops + slack sdk를 활용해 실시간 대응 환경 구축  

<strong>저장소 링크</strong>:  

---

### 🛠️ <strong>다중 객체 이미지 판별 및 6D 포즈 추정 웹서비스 (2023.07 ~ 2023.08)</strong>
다중 객체 이미지를 활용하여 객체의 포즈를 추정하는 솔루션 개발  
<strong>기술</strong>: Java, Spring Boot, MySQL, PyTorch, OpenCV  
  - (주) 다래비젼에서 요구한 프로젝트에서 Back End와 팀장으로서 역할을 다했습니다  
  - 기업 측에서 과거에 진행했던 프로젝트였지만 현재 회사 내부적으로 여건이 안서 관련 프로젝트가 중단된 상태였습니다. 기업에서 요구한 사항은 단순히 6D Pose 값만 출력하는 것이었지만 웹서비스를 추가로 구현하였습니다  
  - 프로젝트에서는 SpringBoot를 활용하여 서버 API를 구성하고, 객체 식별 및 포즈 추출을 위해 Flask와 OpenCV, Yolov8를 이용해 API를 구축했습니다  
  - 최종적으로 기업 이사들 앞에서 발표를 진행했고, 예상했던 6D Pose 값만 보여준 게 아니라 객체의 6D를 추정하는 데 있어서 나오는 과정들을 웹서비스로 동적인 형태로 시각화해서 보여준 결과 긍정적인 피드백을 받았습니다  

<strong>저장소 링크</strong>:  

</details>

---

<details>
<summary><b><i>🐬etc...</i></b></summary>
<br>

- 💡 **AWS Chalice 배포 환경 변경**  
  Sagemaker에서 직접 인스턴스 생성 비용을 줄이기 위해 배포 환경을 Sagemaker → GoogleColab으로 변경

- 💡 **AI 모델 React-native, Android 환경 배포**  
  AI 모델 서버 운용 비용 절감을 위해 모델 형식을 pt에서 onnx로 전환 후 앱 자체에 모델 탑재

- 💡 **React-native, Android 환경 배포된 AI 모델 성능 개선**  
  앱 자체에 모델을 탑재시키기 위해서 로컬 GPU 환경을 구축하고 onnxruntime 라이브러리를 이용해 모델 파일 크기를 기존 대비 1/4로 경량화  
  모델 경량화로 인한 모델 성능 저하 최소화를 위해 로컬 GPU 사용 환경을 구축해 모델 최적화를 진행시켜 모델 정확도를 양자화 이전 모델과 동일하게 유지

- 💡 **AndroidEmulater 멈춤 및 끊김 현상 해결**  
  AndroidStudio 디버깅 및 profiler 분석을 통해 메모리 릭 현상 발견  
  모델 세션 생성, 추론, 삭제를 1개의 트랜잭션으로 묶어 메모리 릭 현상을 해결

- 💡 **모델 학습 과정 및 결과 시각화**  
  GoogleColab - wandb 연동, wandb customizing으로 대시 보드 제작

</details>
