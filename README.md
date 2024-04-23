# RESUME

<details>
<summary><b><i>🐬문제 해결🐬</i></b></summary>
<br>

- 💡**AWS Chalice 배포 환경 변경**
  - Sagemaker에서 직접 인스턴스 생성 비용을 줄이기 위해 배포 환경을 Sagemaker → GoogleColab으로 변경

- 💡**AI 모델 React-native, Android 환경 배포**
  - AI 모델 서버 운용 비용 절감을 위해 모델 형식을 pt에서 onnx로 전환 후 앱 자체에 모델 탑재.

- 💡**React-native, Android 환경 배포된 AI 모델 성능 개선**
  - 앱 자체에 모델을 탑재시키기 위해서 로컬 GPU 환경을 구축하고 onnxruntime 라이브러리를 이용해 모델 파일 크기를 기존 대비 1/4로 경량화.
  - 모델 경량화로 인한 모델 성능 저하 최소화를 위해 로컬 GPU 사용 환경을 구축해 모델 최적화를 진행시켜 모델 정확도를 양자화 이전 모델과 동일하게 유지.

- 💡**AndroidEmulater 멈춤 및 끊김 현상 해결**
  - AndroidEmulater 멈춤 및 끊김 현상 해결을 위해 AndroidStudio 디버깅 및 profiler를 분석을 통해서 메모리 릭 현상을 발견
  - 메모리 릭 현상 해결을 위해 모델 세션 생성, 추론, 삭제를 1개의 트랜잭션으로 묶어 메모리 릭 현상을 해결.

- 💡**모델 학습 과정 및 결과 시각화**
  - 효율적인 모델 추적 및 데이터 시각화를 위해 GoogleColab - wandb를 연동시킨 후 wandb customizing을 통해 대시 보드 제작.

- 💡**ML 모델 자동화 파이프라인 구축**
  - ML 관련(데이터 준비, 훈련, 튜닝, 배포 등) 프로세스를 kubeflow와 kserve를 활용해 자동화 파이프라인 구축 완료.

</details>


## 사용 기술

### AI
MLOps 환경을 구축할 수 있는 기술을 가지고 있습니다.
- pytorch
- onnxruntime
- kubernetes - kubeflow

### Backend
클라우드 기반 아키텍처를 설계하고 실제 서비스로 구현하는 기술을 가지고 있습니다.
- Python - flask/django
- Java - SpringBoot - JPA/SpringCloud/Junit
- ConatinerRegistry - Docker, ECR
- AWS - S3, RDS, Sagemaker, ECR
- DB - Mysql, h2


  
