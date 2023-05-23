# employmint
Korea University Employmint

## 기본정보

팀명: EmployMint
팀장: 이서영(010-4506-9746)

팀원: 안준성(010-3212-3017), 김용준(010-4013-3604)

역할 분담: 스마트컨트랙트 / 백엔드 / 프론트엔드 / NFT 디자인

목표: 대외활동(BOB, 케이쉴드주니어, 그 외), 수료증, 수업 인증서, 국비교육(SSAFY) 등등의 인증서를 NFT화 하여

취업 시장에서 깃허브와 같은 기능을 할 수 있도록 한다.

또한, 유명 교수, 유명 대외활동 NFT 습득 시 본인 SNS에 투명하게 업로드가 가능하도록 하여 본인 Appeal이 가능하도록 한다.
투명성을 위해 EmployMint NFT는 거래를 허가하지 않는다. 

- 취업 시장에서 면접관이 보다 쉽게 확인할 수 있도록 웹 페이지 형식으로 제작(ex. github)
- 각종 기업, 프로젝트, 프로그램에서 발행하는 NFT이기 때문에 디자인 요소가 다르게 제작
    - 예를 들어, 기업 및 학교의 특징이 NFT에 드러날 수 있도록(색상, 로고 등)

## 역할분담
![역할분담](./docs/images/%EC%97%AD%ED%95%A0%EB%B6%84%EB%8B%B4.png)

## How to run

1. `.env` 생성 후 환경변수 설정
```
PRIVATE_KEY=<Test Facet이 들어있는 개인키>
EMPLOYMINT_FACTORY=<Employmint Contract을 배포한 주소> e.g. Sepolia Testnet에 배포한 컨트랙 주소
PORT=8080
RPC_ENDPOINT=<Infura/Alchemy 등에서 발급받은 API Endpoint URL> e.g. Sepolia Testnet에 연결된 API Endpoint
```

2. 서버실행
```
npm start
```

3. 테스트
```
https://localhost:8080/api/v1/sbt 에 POST request 전송
```