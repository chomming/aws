## EC2
- Elastic Compute Cloud
- 실행 환경을 구축할 수 있느 가상 서버
- 주요 기능
  - EBS
    - Elastic Block Store
    - 블록 수준 스토리지 볼륨 제공
  - AMI
    - Amazon Machine Image
    - 인스턴스 생성에 필요한 모든 소프트웨어 정보를 담고 있는 템플릿 이미지
  - 키 페어
    - 인스턴스에 접속할 때 인증을 위해 사용하는 키
  - 보안 그룹
    - 인스턴스 접근 규칙 설정
  - Elastic IP
    - 동적 컴퓨팅을 위해 사용되는 고정 public Ip 주소

## S3
- Simple Storage Service
- 웹 서버, 파일 서버용 스토리지로 사용 가능
- region 내 버킷을 생성하여 데이터 저장

## RDS
- Relational Database Service
- Amazon Aurora, PostgreSQL, MySQL, MariadB, Oracle DB, SQL Server를 클라우드에서 이용할 수 있는 서비스

## IAM
- Identity and Access Management
- IAM 정책의 구성요소
  - 주체
  - 작업
  - 리소스
- 

## VPC
- Virtual Private Cloud
- AWS 리소스를 구동할 수 있는 논리적으로 격리된 네트워크
- 구성요소
  - 서브넷
  - 라우팅 테이블
  - 인터넷 게이트웨이

## ELB
- Elastic LoadBalancer
- 네트워크 트래픽 분산
- 부하 분산 대상
  - EC2 인스턴스
  - container
  - IP 주소
- 제공 방식
  - Application LoadBalancer
  - Network LoadBalancer
  - Classic LoadBalancer

## NAT


## IGW


## Route53
- DNS 기능 제공

# EIP
- Elastic IP
- public IP 주소 제공

## WAF

