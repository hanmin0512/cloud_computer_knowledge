r# cloud_computer_knowledge
Cloud computing

# 데이터센터와 Cloud의 차이점


# DATA Center 아키텍쳐
- physical Server (렉 안에 서버를 쌓아 업체별로 나뉘어 관리한다.)
- 렉 안에는 서버 팜, 스토리지 팜, 네트웤 팜 이 들어갈 수 있다.
> ![1](https://github.com/hanmin0512/cloud_computer_knowledge/assets/37041208/60ef2bd9-ae61-4f63-a969-4288c0edcad4)

# Cloud Market
- aws
- Azure
- Google Cloud
- Alibaba Cloud
- IBM Cloud

# Region Availability Zone (리전 가용 영역)
- aws 리전은 더 높은 가용성, 확장성, 내결함성을 위해서 다중의 가용영역으로 구성된다.
- aws 서울 리전은 abailability zone 4개가 있고, 그 데이터 센터의 서버팜을 나눠 서버를 제공 받는다 ec2
- 그냥 로컬 컴퓨터에 VM으로 다른 서버를 운영하는거와 같지만, 내 컴퓨터의 하이퍼바이저가 아닌, aws서버의 하이퍼바이저를 이요한 서버를 제공받는 것이다.

# aws ec2 인스턴스 표기법
- M5d.Xlarge
> M : 인스턴스 패밀리
> 5 : 인스턴스 세대
> Xlarge : 인스턴스 크기

- 비용은 인스턴스 크기 만큼 발생한다고 보면된다.
- 즉 8Xlarge 서버 하나랑, 4Xlarge + 4Xlarge 두개를 운영하는 비용이 같다.
- 이것이 중요한이유 큰서버보다 작은서버를 나눠서 곂쳐 놓는다면 트레픽에따라 잘 놔눠야 한다.

# 웹 호승팅, 서버 호스팅, 클라우드 차이점
- 클라우드 (DB, network architecture, 등 클라우드 서버에 인프라를 다 직접 적용해야한다.)
- 서버 호스팅 (데이터 센터에 서버를 사서 운영 자유도가 뛰어나며 권한도 나의 것이다.)
- 웹 서버 호스팅 (웹 인프라가 다 구축 되어있어서, 코드만 삽입해서 사용하면된다.)

# 클라우드 컴퓨팅 특징
- 초기 투자 비용이 든다( 서버의 크기가 얼마나 필요한지 알 수 없기 때문에 예측을 해야한다.)
- PAY TO GO 사용한 만큼 비용이 발생한다.
- 

