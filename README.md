# 🙋🏻‍♂ GitHub 오픈소스 활용 프로젝트

비트코인 자동매매 프로그램 및 텔레그램 봇을 이용하여 실시간으로 텔레그램으로 비트코인 및 여러 코인의 변동 사항을 보고받을 수 있다.


## 팀 구성
| **이름** | **학번** |
|—————|——|
|😁 장준현 |21828668|
|😁 이훈철 |21711173|
|😁 전상근 |22029440|



### 업비트 Open API

우선은 업비트에서 로그인(회원가입 필수) 한 후 고객센터에서 Open API를 사용하여 ACCESS KEY와 SECRET KEY를 받습니다.

ACCESS KEY와 SECRET키는 잃어버리지 않도록 주의합니다.

![test](https://user-images.githubusercontent.com/41141851/118991825-080e9e80-b9bf-11eb-9f74-8e9bb6584138.png)

#### 텔레그램 API

1) 텔레그렘앱을 설치 후 채팅검색 창에서 "BotFather"를 검색한다.
2) "BotFather"의 Chat room에서 /newbot을 입력하여 Username과 Botname을 만든다.
3) HTTP API를 발급받는다. (잊지 않도록 복사해두자) 다시 검색창에서 "userinfobot"을 검색하여 /start을 검색, User number ID(이것또한 잊지말고 복사해두자)를 구헌다.

이로써 업비트 Open API의 ACCESS KEY와 SECRET KEY, 텔레그램 API의 HTTP API와 User number ID를 얻었다. 이제 자동매매 프로그램을 이용해보자.

#### 본격적으로 시작해보자!

![test](https://user-images.githubusercontent.com/41141851/118992432-9aaf3d80-b9bf-11eb-8843-d3cca4b3673c.png)

현재 보이는 코드에 upbit-api-key에서 access key와 secret key를 넣고, telegram-api-key에서 telegram token key와 telegram mc key를 넣습니다.

### 프로그램 실행 전 필수 설치

```sh
pip install pyupbit
pip install python-telegram-bot
pip install virtualenv
pip install python-dotenv
pip install requests
pip install BeautifulSoup
```

텔레그램 봇으로 최신순 뉴스 업데이트

- requests (특정 url의 html 문서 받기)
- BeautifulSoup (html 문서에서 원하는 요소 선택적 추출)
- python-telegram-bot (뉴스 링크를 텔레그램 봇으로 채팅방에 전송)


투자하고 싶은 코인을 추가하고 싶을 때

coin_list에 투자할 코인의 정보 입력






