# AWS를 활용한 S3 버킷 및 Lambda 함수 관리 자동화
![AWS_실습_빅데이터9기_신유라](https://github.com/user-attachments/assets/222c83fb-fb6e-43d3-84b7-469925ffee28)

## Skills
<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/>&nbsp;
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>&nbsp;
<img src="https://img.shields.io/badge/Boto3-4285F4?style=for-the-badge&logo=python&logoColor=white"/>&nbsp;
<img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>&nbsp;

## 프로젝트 상세

- **진행 기간**: 2024년 10월 23일
- **프로젝트 유형**: 개인 프로젝트

## 프로젝트 목표

- 클라우드 환경에서 파일 저장과 서버리스 컴퓨팅 기능 이해 및 자동화
- S3, Lambda, VPC 등 AWS의 핵심 서비스 사용
- Boto3를 이용해 AWS 자원 관리, 파일 저장 및 Lambda 트리거 설정 자동화


## 사용한 데이터 셋

- 사용자 지정 데이터를 사용하지 않고, AWS S3 서비스의 버킷을 생성하여 데이터를 관리하는 방식으로 실습 진행


## 워크플로우

- **AWS S3 버킷 생성 및 관리**
  - Boto3 라이브러리를 사용해 S3 버킷을 생성하고 목록을 확인함. 환경 변수 파일 (.env)에 AWS Access Key 및 Secret Key를 저장하여 보안을 유지하며 접근
  - S3에 파일을 업로드하고, 버킷 정책을 설정하여 접근을 제어함

- **Lambda 함수 설정**
  - 서버리스 환경에서 Lambda 함수를 생성하고 특정 트리거에 의해 실행되도록 설정
  - 제한 시간과 메모리를 설정하고, Python을 활용하여 파일 처리 및 데이터 전송 작업을 자동화함

- **VPC 및 네트워크 설정**
  - VPC를 생성하여 사설 네트워크를 구성하고, 서브넷을 설정하여 퍼블릭/프라이빗 통신이 가능한 환경 구축
  - 보안 그룹과 NACL을 설정하여 접근 제어 및 보안을 강화


## 프로젝트 결과

- **AWS 자원 자동화**: Boto3를 통해 S3 버킷의 생성, 파일 업로드 및 삭제가 자동화되었으며, Lambda 함수를 통해 서버리스 데이터 처리도 자동화됨


## 트러블 슈팅

- **인증 오류 해결**: 처음에는 AWS 인증 관련 오류가 발생하여 환경 변수 파일(.env)에 AWS Access Key와 Secret Key를 저장하고, 이를 Python 코드에서 불러오는 방식으로 해결


## 프로젝트를 통해 얻은 역량

- **클라우드 서비스 이해**: AWS S3, Lambda, VPC 등의 서비스 구조와 역할에 대한 이해
- **Python과 Boto3 사용**: Boto3 라이브러리를 사용해 Lambda 트리거 설정 자동화
