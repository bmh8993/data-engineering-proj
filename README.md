# 프로젝트 설명
- 설명
  - [TLC Trip Record Data(2020년 3월 데이터 사용)](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page)를 바탕으로 배치/실시간 처리 프로젝트
- 데이터 세트: TLC Trip Record Data
    - 10+년 이상의 택시와 모빌리티 서비스 기록
    : 2009~2021년까지 모든 기록이 공개
    - 매년 20GB씩 쌓이는 Dataset
    : 승차와 하차시간과 장소, 소요시간, 택시비와 같이 중요한 데이터를 포함

# 환경
- python 3.7
- anaconda

# 사용 프레임워크
- Batch: PySpark
- dataflow orchestration: airflow
- stream: Flink
- Queue: Kafka
