

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Contact](#contact)

<!-- ABOUT THE PROJECT -->
## About The Project

  <img src="/images/logo.png" width="10%" height="10%" alt="로고"></img>
 
  이 챗봇은 현재 날씨를 기반으로 식사 메뉴를 추천해주고, 해당 메뉴를 먹을 수 있는 음식점을 소개합니다.

  이 챗봇을 이용한다면 지도 어플리케이션에 들어가서 일일이 검색할 필요없이 간단한 작업으로 음식점을 소개받을 수 있습니다.


### Built With

* [Express](https://github.com/expressjs/express)
* [Kakao map API](https://developers.kakao.com/)
* [Line messaging API](https://developers.line.biz/en/)
* [Openweather Map API](https://openweathermap.org/)

<!-- GETTING STARTED -->
## Getting Started

다음의 간단한 작업 후에 프로그램을 실행시킬 수 있습니다.

### Installation

1. 다음 링크에 접속하여 무료 API를 신청한 후 key를 이용합니다.
  * [https://developers.line.biz/en/](https://developers.line.biz/en/)
  * [https://developers.kakao.com/](https://developers.kakao.com/)
  * [https://openweathermap.org/](https://openweathermap.org/)

2. 이 레파지토리를 Clone합니다.
```
git clone http://khuhub.khu.ac.kr/2018102205/meal-recommender.git
```

3. NPM packages를 설치합니다.
```
npm install
```

4. `app.js` 파일에 받은 API 값을 입력합니다.
```
const TOKEN = 'Line Messege API 얻은 Channel access token';
const KAKAOKEY = 'Kakao Developers에서 얻은 API Key';
const WEATHERKEY = 'Openweathermap에서 얻은 API Key';
```

<!-- USAGE EXAMPLES -->
## Usage

먼저 라인에서 "오늘의 메뉴" 챗봇을 친구 추가해야 합니다. PC버전의 라인 어플리케이션이나 모바일 어플리케이션을 이용해 라인을 접속하세요. @453qrzxr를 검색하여 아이디로 친구로 추가하거나 아래의 QR코드로 친구 추가할 수 있습니다.

<img src="/images/QRcode.png" width="10%" height="10%" alt="QR CODE"></img>

기본 중심값은 경희대학교 국제캠퍼스로 설정되어 있습니다. 중심값을 바꾸고 싶다면 "내위치"를 전송하세요. 라인에서 지원하는 Quick Reply 메세지로 원하는 중심값을 전송할 수 있습니다. (이 기능은 pc버전 라인 메신저에서 제공되지 않습니다. 모바일에서 이용해주세요.) 해당 챗봇은 이렇게 설정한 중심값 주변의 음식점을 추천해줍니다.

"날씨추천"을 전송한다면 날씨를 기반으로 추천된 메뉴를 제공받습니다. 그 외에도 사용자는 자신이 입력한 키워드를 통해 음식점 정보를 받아볼 수 있습니다.

<p float="left">
  <img src="/images/screenshot1.png" width="20%" height="20%" alt="Screenshot1"></img>
  <img src="/images/screenshot2.png" width="20%" height="20%" alt="Screenshot2"></img>
</p>

<!-- LICENSE -->
## License

MIT 라이센스에 따라 배포. 자세한 내용은 `LICENSE`를 참조하세요.

<!-- CONTACT -->
## Contact

* 엄상은 | sangeun99@khu.ac.kr

* [http://khuhub.khu.ac.kr/2018102205/meal-recommender.git](http://khuhub.khu.ac.kr/2018102205/meal-recommender.git)