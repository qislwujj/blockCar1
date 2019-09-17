# BlockCar
> **하이퍼레저 기반 중고차 등록, 조회, 수정 등 중고차전산망과 블록체인을 접목시킨 앱** <br>


## Getting started
> 자동차에 대한 **이력**을 블록에 저장하여 제조사부터 정비 업체, 보험사, 감독 기관 등에 **공유**됩니다. <br>
차를 수리하게 되면 정비 업체의 수리 내역이 제조사, 보험사, 감독 기관에 공유돼 **하나의 블록**이 되어 <br>
차량 주인이 정비사에게 수리 내역을 삭제하는 등의 행위를 사실상 의미 없게 만듭니다. <br>
따라서 중고차 시장에서 **허위 매물**을 없앨 수 있고, 차량에 대한 이력을 손쉽게 확인함으로써 구매자 입장에서 **신뢰**를 얻을 수 있습니다. <br>


## Team
* 안성민
* 이대건
* 이진
* 김상혁
* 강준모


## Prerequisites
* Ubuntu - 16.04
* Docker - latest
* Docker Compose - latest
* NPM - latest
* nvm - latest
* Node.js - latest
* Golang - latest
* Git client - latest
* HyperledgerFabric Example - branch 1.4


## Application Workflow
![blockcar](https://user-images.githubusercontent.com/51254580/65012593-de33e780-d952-11e9-9eed-795bd36ec218.png)

* 차량소유자는 차를 팔게되면 중고차 전산망에 차량의 모든 정보가 등록이 되고 다른 고객이 차를 사게되면 차량의 판매상태를 1로 바꾸어 차량의 유무를 알 수 있고, <br>
중고차 전산망이 블록체인으로 바뀌면서 현재 난무하는 불법차량이나 허위차량 등 중고차시장에서 가장 문제로 꼽았던 문제들을 손쉽게 해결할 수 있게 됩니다.<br><br><br>

# 소스 코드

![bc4](https://user-images.githubusercontent.com/51254580/65012980-36b7b480-d954-11e9-9dfb-1875dbdaead5.png)

![bc2](https://user-images.githubusercontent.com/51254580/65012921-1a1b7c80-d954-11e9-8b30-ec3c65dc8e44.png)
![bc3](https://user-images.githubusercontent.com/51254580/65012976-31f30080-d954-11e9-83a3-93321547eb0f.png)
![blockcar code1](https://user-images.githubusercontent.com/51254580/65012864-daed2b80-d953-11e9-8e8a-f74b452b63f7.png)<br><br><br>



## References
* HyperledgerFabric Example - fabcar
* 이승한,이요한,신태영 「실전! 하이퍼레저 패브릭」 (위키북스 해킹 & 보안 시리즈, 2019)
