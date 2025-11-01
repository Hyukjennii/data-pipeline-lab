# 🔗 data-pipeline-lab
> Kafka–Spark–Airflow 기반 **데이터 파이프라인 실험 프로젝트**  
> 로그 수집 → 실시간 처리 → 리포트 자동화의 전체 흐름을 개인 VM 환경에서 실험하기 위한 레포입니다.

---

## 🎯 목표
- Kafka를 통한 **로그 스트림 수집**
- Spark Structured Streaming 기반 **실시간 데이터 처리**
- Airflow를 통한 **스케줄 관리 및 자동화**
- Throughput / Latency 성능을 정량 분석하여 PDF 리포트화

---

## 🧩 구조
data-pipeline-lab/
├── dags/ # Airflow DAG
├── spark_jobs/ # Spark Job 코드
├── config/ # 설정 파일 (Kafka/Spark/Airflow)
├── reports/ # 성능 리포트
├── notebooks/ # 시각화/분석 노트북
└── scripts/ # 자동화 스크립트
