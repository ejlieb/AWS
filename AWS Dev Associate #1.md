# AWS Dev Associate #1



#### 1. AWS Region

Region: Data 센터의 집합, AWS 서비스의 대부분은 리전에 국한되어서 이용 가능하다.

- 리젼의 선택 요인
  1. 법률: 어떤 정부들은 어플이 배포될 대상 국가 내에 데이터를 보관하기를 원한다. 이 경우 해당 국가를 선택해야 된다.
  2. 지연시간: 대부분의 사용자가 있는 곳에서 가까운 곳을 선택한다. 그래야 지연 시간이 낮아지니까.
  3. 서비스의 존재 유무: 모든 리전이 모든 서비스를 가지고 있지는 않다.
  4. 요금 : 요금은 리전마다 다르다.

Availability Zone

- 보통 각각의 리전은 2-6개 평균 3개의 가용영역을 가지고 있다.
- 각각의 AZ는 하나 이상의 데이터 센터로 이루어져 있다. 각각의 가용영역은 분리되어 있다. ap-southeast-2a에 문제가 생겨도 ap-southeast-2b는 문제가 없는 것. 
- 이런 가용영역은 높은 대역폭의 초저지연 네트워크로 연결되어 리전을 형성



Edge Location

- AWS는 216개의 전송지점을 가지고 있다. lower latency 가능



#### AWS Console

- AWS GLobal Service:
  - Identity and Access Management(IAM)
  - Route 53(DNS)
  - CloudFront(Content Delivery Network)
  - WAF(Web Application Firewall)
- 나머지는 거의 대부분 리젼 국한 서비스
  - EC2
  - Elastic Beanstalk 등



#### IAM 



MFA ==>password가 해킹당해도 account is not compromised.





