# Android_Portfolio

* 2015년부터 2017년까지 제가 작업한 안드로이드 프로젝트들을 정리한 문서입니다.

## 목록

> 2017

```text
    2017.03 2017 선린인터넷고등학교 졸업전시회 어플리케이션 - GraduateExhibition - https://github.com/kotohana5706/GraduateExhibition
    2017.05 제 2회 국민대학교 두리톤 Get It Pouch - https://github.com/kotohana5706/get_it_pouch
    2017.06 3학년 스마트앱콘텐츠제작 수행평가 - RandomFood - https://github.com/kotohana5706/RandomFood
    2017.07 개인 외주 - LiveCoin - https://github.com/kotohana5706/livecoin-android
    2017.07 모바일 콘텐츠 경진대회 Cardline - https://github.com/clik-labs/cardline_android/tree/mocon_final
    2017.07 모바일 콘텐츠 경진대회 Piller - https://github.com/hw-piller/piller_android
```

> 2016

```text
    2016.01 제 1회 강원도 공공데이터 이용 앱 개발 공모전 효돌이 - https://github.com/kotohana5706/repay-androidclient
    2016.02 개인 작업 - Exchat - https://github.com/kotohana5706/Old_Exchat
    2016.05 개인 작업 - ShakitText - https://github.com/kotohana5706/ShakitText_Rev.1
    2016.05 단국대 집현전 해커톤 Indian - https://github.com/kotohana5706/Indian
    2016.07 모바일 콘텐츠 경진대회 Sharbat - https://github.com/kotohana5706/Sharbat
    2016.07 제 11회 AppJam Tenword - https://github.com/kotohana5706/Tenword
    2016.07 개인 외주 - Kkobugi - https://github.com/kotohana5706/Kkobugi
    2016.07 제 2회 선린해커톤 EVA - https://github.com/kotohana5706/EVA
    2016.07 모바일 콘텐츠 경진대회 Cumchuck - https://github.com/kotohana5706/CumChuck
    2016.08 화학 수행평가 - SpaceBalloon - https://github.com/kotohana5706/SpaceBalloon-AndroidClient
    2016.09 제 51회 기능경기대회 앱 개발 공모전 기능경기대회 도우미 - https://github.com/kotohana5706/Alime
    2016.09 제 3회 대한민국 SW융합 해카톤대회ACAR - https://github.com/kotohana5706/ACAR
    2016.10 삼성 주니어 소프트웨어 창작대회 Safood - https://github.com/kotohana5706/Safood
    2016.10 함께서울 앱 공모전 Buspolis@Seoul - https://github.com/Buspolis/app-android
    2016.11 디지털 콘텐츠 경진대회 Srnow & SrHome - https://github.com/srDevelopers/srAndroid
    2016.11 제 2회 강원도 공공데이터 이용 앱 개발 공모전 GroVenue - https://github.com/kotohana5706/GroVenue
    2016.12 삼성 투머로우 솔루션 Rerant - https://github.com/GoodReserve/app-android
    2016.12 SK Smarteen App Challenge 한글을 한글로! - https://github.com/Hangeulro/app-android
```

> 2015

```text
    2015.07 모바일 콘텐츠 경진대회 Bill.Im - https://github.com/kotohana5706/bill.im
    2015.07 제 1회 선린해커톤 Familing - https://github.com/kotohana5706/familing
    2015.07 제 8회 AppJam Paper Crane - https://github.com/kotohana5706/PaperCrane
    2015.08 개인 작업 - neoanime - https://github.com/kotohana5706/neoanime
    2015.10 삼성 주니어 소프트웨어 창작대회 오늘의 어린이상 - https://github.com/kotohana5706/awardoftoday_android
    2015.10 단국대 집현전 해커톤 멍냥병원 - https://github.com/kotohana5706/MalangHospital_Client
    2015.11 디지털 콘텐츠 경진대회 Knock - https://github.com/kotohana5706/knock-androidclient
    2015.12 함께서울 앱 공모전 I.LOST.U - https://github.com/kotohana5706/ilostu_android
    2015.12 제 9회 AppJam Merror - https://github.com/kotohana5706/merror-androidclient
```

## 2015

> Bill.IM
* 2015 선린 모바일 콘텐츠 경진대회 은상

>> 역할

```text
    안드로이드 클라이언트 메인 프로그래머
    프로젝트 기획 보조
    Restful API 작성
```

>> 기획

```text

    필요할때 꼭 없는 그러한 여러 물건들을 같은 단체 내에서 빌릴 수 있도록 해주는 서비스. 중고 제품의 물물교환도 가능하도록 하여, 단체 내에서 새로운 물건을 구매 하는 것이 아닌 서로 필요한 것을 주고받으며 도울 수 있도록 만들어 주는 서비스.
    임대 기능, 신고 기능, 중고 제품 교환 기능 제공.
```

>> 기술

```text
    서버는 Node.JS로 구동하였으며 CoffeeScript로 작성되었고, MongoDB를 사용하였음.
    클라이언트는 안드로이드로 구현하였으며, Realm 데이터베이스와 SharedPreferences를 사용하였음.
    FloatingActionButton, Material, MaterialViewPager, MaterialEditText, SwipyRefreshLayout, MaterialDialog 라이브러리를 사용하였음.
    서버 -> 안드로이드 클라이언트에는 Google Cloud Messaging을 사용하였음.
    안드로이드 클라이언트 -> 서버에는 HTTP 통신을 이용하였음. (Retrofit 사용)
    각각의 거래 항목은 데이터베이스에 저장하였으며 변경사항이 요청자 / 거래자로부터 발생하면 GCM을 이용해 클라이언트에 푸시를 보내고, 변경사항을 데이터베이스에 업데이트하였음.
```

> Familing
* 2015 선린 해커톤 동상

>> 역할

```text
    안드로이드 클라이언트 메인 프로그래머
    백엔드 서버 보조 프로그래머
    Restful API 작성
```

>> 기획

```text
    Familing은 가족끼리 하고 싶었던 말을 진솔하게 전하고 가족간의 추억을 저장하며 가족간의 상의나 문제해결을 도와주는 어플리케이션.
    가족이 한 그룹이 되며, 그 안에 아빠, 엄마, 아들, 딸 등 각 가족 구성원이 가입되어 있는 형식임.
    가족 구성원들이 게시글을 게시판에 게시할 수 있으며, 그룹 구성원들은 그에 댓글을 달아 반응할 수 있음.
```

>> 기술

```text
    서버는 Node.JS로 구동하였으며 CoffeeScript로 작성되었고, MongoDB를 사용하였음.
    클라이언트는 안드로이드로 구현하였으며, Realm 데이터베이스와 SharedPreferences를 사용하였음.
    FloatingActionButton, Material, MaterialEditText, MaterialDialog 라이브러리를 사용하였음.
    서버 -> 안드로이드 클라이언트에는 Google Cloud Messaging을 사용하였음.
    안드로이드 클라이언트 -> 서버에는 HTTP 통신을 이용하였음. (Retrofit 사용)
    각각 게시글은 데이터베이스에 저장하였으며 댓글도 따로 데이터베이스 객체로 저장하고 게시글 객체에 관계시키는 방식으로 구현하였음.
```

> Paper Crane
* 2015 제 8회 AppJam 우수상

>> 역할

```text
    안드로이드 클라이언트 메인 프로그래머
```

>> 기획

```text
    천 마리의 종이학 접기에서 모티브를 받은 앱으로, 소중한 사람에게 긴 기간동안 편지를 모아 사용자가 설정한 시각에 한번에 보내주는 어플리케이션임.
    현재 작성중인 편지 목록, 보낼 대상 추가, 즉시 전송 기능을 제공.
    보내는 대상은 전화번호부에서 찾거나 직접 전화번호를 입력해서 전송할 수 있음.
```

>> 기술

```text
    서버를 이용하지 않고 클라이언트로만 구현하였음.
    클라이언트는 안드로이드로 구현하였으며,  SharedPreferences를 사용하였음.
    FloatingActionButton, Material, MaterialEditText, MaterialDialog 라이브러리를 사용하였음.
    서버 -> 안드로이드 클라이언트에는 Google Cloud Messaging을 사용하였음.
    안드로이드 클라이언트 -> 서버에는 HTTP 통신을 이용하였음. (Retrofit 사용)
    각각의 거래 항목은 데이터베이스에 저장하였으며 변경사항이 요청자 / 거래자로부터 발생하면 GCM을 이용해 클라이언트에 푸시를 보내고, 변경사항을 데이터베이스에 업데이트하였음.
```

> neoanime
* 개인 프로젝트

>> 역할

```text
    안드로이드 클라이언트 메인 프로그래머
```

>> 기획

```text
    NeoAnime 커뮤니티의 OST 게시판의 음원들을 스트리밍하는 어플리케이션
```

>> 기술

```text
    서버를 이용하지 않고 클라이언트로만 구현하였음.
    클라이언트는 안드로이드로 구현하였으며, SharedPreferences를 사용하였음.
    Material, MaterialEditText, MaterialDialog 라이브러리를 사용하였음.
    Jsoup HTML Parser를 이용하여 OST 게시판을 파싱하고, 그 안의 링크를 가져와 MediaPlayer를 이용해 스트리밍하였음.
```

오늘의 어린이상
멍냥병원

> Knock
* 2015 선린 디지털 콘텐츠 경진대회 동상

>> 역할

```text
    안드로이드 클라이언트 메인 프로그래머
    Restful API 작성
```

>> 기획

```text
    보안이 중요시되는 현대 사회에서 공동으로 사용하는 공간에서 보안에 취약한 컴퓨터들을 위해서 카드 태깅을 이용하여 PC Lock / Unlock할 수 있는 플랫폼.
    PC에서는 로그인, 로그아웃, 카드를 이용한 잠금 / 잠금 해제를 제공함.
    모바일에서는 로그인, 로그아웃, 카드를 이용하지 않은 잠금 / 잠금 해제를 지원함.
```

>> 기술

```text
    서버는 Node.JS로 구동하였으며 JavaScript (ECMAScript 5.1)로 작성되었고, MongoDB를 사용하였음.
    PC 클라이언트는 DirectX API를 이용하여 창을 구현하였음.
    모바일 클라이언트는 안드로이드로 구현하였으며, SharedPreferences를 사용하였음.
    PC <-> 서버, 서버 <-> 안드로이드간의 실시간 통신에는 Socket을 사용하였음.
    MaterialDialog 라이브러리를 사용하였음.
    안드로이드 클라이언트 -> 서버에는 HTTP 통신을 이용하였음. (Retrofit 사용)
    Lock / Unlock 요청이 들어오면 서버의 데이터베이스에 현재 상태를 저장하고, Socket을 이용하여 요청 상황을 각 클라이언트에 브로드캐스트시키는 방식을 사용하였음.
```

> I.LOST.U
* 2015 함께서울 앱 공모전 장려상

>> 역할

```text
    안드로이드 클라이언트 메인 프로그래머
```

>> 기획

```text
    대중교통에서 분실물이 발생 할 시 본인이 원하는 유실물이 바로바로 확인하고 찾을 수 편리하게 찾을 수 있도록 정보를 제공해주는 어플리케이션.
    지하철 호선별 / 도시버스 / 마을버스로 분류함
    물품 이름, 현 상태, 내용, 분실물 수령 가능한 곳 등을 제공함.
```

>> 기술

```text
    서버를 이용하지 않고 클라이언트로만 구현하였음.
    클라이언트는 안드로이드로 구현하였으며,  SharedPreferences를 사용하였음.
    JSoup HTML Parser, MaterialDialogs, MaterialSpinner, Material, MaterialRipple, SwipyRefreshLayout 라이브러리를 사용하였음.
    서울시에서 제공하는 공공데이터를 사용하여 데이터를 표시하였으며, 모바일 어플리케이션상에서 표시가 어려운 부분들은 웹뷰를 이용하여 표시하였음.
```

> Merror
* 2015 제 9회 AppJam 장려상

>> 역할

```text
    안드로이드 클라이언트 메인 프로그래머
```

>> 기획

```text
    "이상한 나라에 사는 사람을 위한 프로그램"이라는 주제가 주어짐.
    이상한 나라에서 똑같은 이름을 가진 또 다른 나 자신과 만나는 컨셉으로 어플리케이션임. 
    또다른 나를 찾아보기 기능을 이용하여 같은 이름을 가진 사용자와 실시간 채팅을 이용할 수 있음.
    이름, 생일 수정, 채팅방 색상 수정 등을 이용할 수 있음.
```

>> 기술

```text
    서버는 Node.JS로 구동하였으며 JavaScript (ECMAScript 5.1)로 작성되었고, MongoDB를 사용하였음.
    모바일 클라이언트는 안드로이드로 구현하였으며, SharedPreferences를 사용하였음.
    서버 <-> 안드로이드간의 실시간 채팅에는 Socket을 사용하였음.
    MaterialDialog 라이브러리를 사용하였음.
    안드로이드 클라이언트 -> 서버에는 HTTP 통신을 이용하였음. (Retrofit 사용)
```
## 2016

> 효돌이
* 2015 제 1회 강원도 공공데이터 이용 창업 앱 공모전 학생부 최우수상

>> 역할

```text
    안드로이드 클라이언트 메인 프로그래머
    백엔드 서버 프로그래머
    데이터베이스 관리
    Restful API 작성
```

>> 기획

```text
   사회적으로 대두되고 있는 문제인 고독사를 어플리케이션으로 해결해 보고자 함.
   휴대폰을 가지고 있지만 어떻게 써야 할 지 모르시는 어르신, 부모님과 연락을 조금 더 체계적으로, 자주하고 싶은 자녀를 타겟팅함.
   앱의 UI는 사용자가 부모인지, 자녀인지에 따라 달라짐.
   근처 운동시설, 복지센터 등을 알 수 있는 기능, 추억이 담긴 갤러리 공유, 쇼핑몰과 연계해 여러 제품을 제공해주는 마켓 기능, 병원 시설 기능 등을 제공함.
```

>> 기술

```text
    서버는 Node.JS로 구동하였으며 JavaScript (ECMAScript 5.1)로 작성되었고, MongoDB를 사용하였음.
    모바일 클라이언트는 안드로이드로 구현하였으며, 캐싱을 위해 Realm DB, SharedPreferences를 사용하였음.
    서버 -> 안드로이드에는 Google Cloud Messaging을 사용하였음.
    YoutubeAndroidPlayerAPI, MaterialDialogs, MaterialEditText, FloatingActionButton 라이브러리를 사용하였음.
    서버의 이미지를 로드해오기 위해 Volley 라이브러리를 사용하였음.
    안드로이드 클라이언트 -> 서버에는 HTTP 통신을 이용하였음. (Retrofit 사용)
```

> Exchat
* 개인 작업 / 플레이 스토어 업로드 (https://play.google.com/store/apps/details?id=kr.edcan.exchat)

>> 역할

```text
    안드로이드 클라이언트 메인 프로그래머
    환율 데이터 파싱
    데이터베이스 관리
```

>> 기획

```text
   환율을 복잡하게 찾아보기 않고, 접근성이 용이하게 하여 바로 확인할 수 있게 한 어플리케이션.
   메인 화면에서 유저가 설정한 주요 환율과 환율 변환, 최근 기록을 확인 할 수 있음.
   어플리케이션 외부에서 금액을 복사할 시 바로 변환하여 팝업으로 알려주는 기능을 제공함.
```

>> 기술

```text
    모바일 클라이언트는 안드로이드로 구현하였으며, 캐싱을 위해 Realm DB, SharedPreferences를 사용하였음.
    Jsoup HTML Parser, Material, MaterialDialogs, AndroidParallax 라이브러리를 사용하였음.
    KEB하나은행에서 제공하는 환율 페이지를 일정 주기로 파싱해와 데이터베이스에 저장하고, 이를 이용해 계산함.
    계산기는 환율 변경, 원래 환율과 대상 환율의 교환을 제공함.
    복사해서 팝업으로 열람한 환율 정보나 저장버튼을 눌러 저장한 정보는 메인의 계산기 밑에 카드뷰로 표시됨. 
```

> ShakitText
* 개인 작업 

>> 역할

```text
    안드로이드 클라이언트 메인 프로그래머
```

>> 기획

```text
    항상 트윗할게 생각났을때 앱을 켜고, 작성하고, 보내는 과정이 번거롭다고 생각되어 제작됨.
    간단하게 휴대폰을 흔들어서 트윗을 작성할 수 있는 어플리케이션.
```

>> 기술

```text
    모바일 클라이언트는 안드로이드로 구현하였으며, 계정 정보를 저장하기 위해 Realm DB, 설정값 저장을 위해 SharedPreferences를 사용하였음.
    Material, MaterialDialogs, Android Fabric (Twitter API) 라이브러리를 사용하였음.
    휴대폰을 흔드는 액션이 감지되면 팝업을 띄워 트윗을 작성 할 수 있음.
    In-App에서는 트위터 계정 설정과 흔드는 감도 설정, 테마 등을 설정 할 수 있음.
```

> Indian 
* 2016 단국대 집현전 해커톤 참가작

>> 역할

```text
    안드로이드 클라이언트 메인 프로그래머
    Restful API 작성
```
<img src="./img/img.png" width="120">

>> 기획

```text
    홍보와 객관적인 리뷰를 얻기 어려운 인디게임들을 위한 홍보 플랫폼.
    게임 개발자는 게임 등록이 가능하며 일반 사용자들은 이를 열람하고 리뷰를 남길 수 있음.
    게임을 검색하거나 개발자별로 게임 종류를 살펴볼 수 있음.
    또한 이 플랫폼을 통해 게임을 구매할 수 있으며 게임 라이센스는 코드로 지급됨.
```

>> 기술

```text
    서버는 Node.JS로 구동하였으며 JavaScript (ECMAScript 6)로 작성되었고, MongoDB를 사용하였음.
    모바일 클라이언트는 안드로이드로 구현하였으며, 계정 정보를 저장하기 위해 Realm DB, 설정값 저장을 위해 SharedPreferences를 사용하였음.
    Material, MaterialDialogs 라이브러리를 사용하였음.
    안드로이드 클라이언트 -> 서버에는 HTTP 통신을 이용하였음. (Retrofit 사용).
```

> Sharbat 
* 2016 모바일 콘텐츠 경진대회 참가작

>> 역할

```text
    안드로이드 클라이언트 메인 프로그래머
    Restful API 작성
```

>> 기획

```text
    기존의 메일 앱들은 메일 확인, 관리, 읽기, 다운받기 등 기본적인 기능만 지원하였으나, Sharbat은 #(해당되는 키워드), @(해당되는 사람), /(특수한 메일)의 특수 기호를 통해 원하는 대로 분류해 주는 특징을 가지고 있음.
    플래그 세우기, 빠르게 분류함 만들기, 비밀번호나 Touch ID를 이용한 메일 암호화를 지원함.
```

>> 기술

```text
    모바일 클라이언트는 안드로이드로 구현하였으며, 계정 정보를 저장하기 위해 Realm DB, 설정값 저장을 위해 SharedPreferences를 사용하였음.
    Google, Outlook.com, Yahoo Mail!을 기본적으로 지원하며 지원하지 않는 이메일은 IMAP, POP3을 통해 연결 가능함.
    각 사에서 제공하는 메일 클라이언트 라이브러리와 Material, MaterialDialogs 라이브러리를 사용하였음.
    새로 도입된 버튼 디자인을 구현하기 위해 CartaTagView 커스텀뷰를 구현하여 이용하였음.
    안드로이드 클라이언트 -> 메일 서버 Request에는 HTTP 통신을 이용하였음. (Retrofit 사용).
```

> Cumchuck
* 2016 선린 모바일 콘텐츠 경진대회 동상

>> 역할

```text
    안드로이드 클라이언트 메인 프로그래머
    Restful API 작성
    백엔드 서버 보조 프로그래머
```

>> 기획

```text
    SNS 친구들과 함께 주변에 맛집을 찾아 레이드를 떠나 맛있고 행복하게 밥을 먹을 수 있도록 도와주는 서비스.
    주변 분야별 음식점 리스트를 제공하며, 친구의 범위는 페이스북 친구로 한정함.
    음식점 찾기, 레이드 구성하기, 친구들을 초대하기, 리뷰 작성하기 등의 기능을 제공함.
    레벨 시스템 구축을 통해 레이드를 떠남으로써의 성취감을 유도함.
    Foursquare API를 통한 정확하고 신뢰성 높은 음식점 정보와 사용자들의 리뷰와 별점으로 빅데이터 구축함.
```

>> 기술

```text
    서버는 Node.JS로 구동하였으며 JavaScript(ECMAScript 5.1)으로 작성되었고, MongoDB를 사용하였음.
    클라이언트는 안드로이드로 구현하였으며, Realm 데이터베이스와 SharedPreferences를 사용하였음.
    서버 -> 클라이언트에는 Google Cloud Messaging을 사용하였음.
    클라이언트 -> 서버에는 HTTP 통신을 이용하였음. (Retrofit 사용)
    레이드의 각각 방은 Socket을 이용해 실시간 통신을 가능하게 하였고, 레이드당 방을 각각 생성하였음.
```

> Tenword
* 2016 제 11회 AppJam 참가작 

>> 역할

```text
    안드로이드 클라이언트 메인 프로그래머
    백엔드 서버 보조 프로그래머
    데이터베이스 관리
```

>> 기획

```text
    "미니멀리즘"이라는 주제가 주어짐.
    미니멀리즘을 SNS 안에서 구현해보면 어떨까 생각하던 차에, 자신의 생각을 열글자 안에 담아 표현하는 SNS를 구상하게 되었음.
    모든 게시글과 댓글은 열글자 내에서 작성이 가능한 가벼운 SNS 플랫폼임.
```

>> 기술

```text
    서버는 Node.JS로 구동하였으며 JavaScript(ECMAScript 6)으로 작성되었고, MongoDB를 사용하였음.
    클라이언트는 안드로이드로 구현하였으며, 게시글 데이터 캐싱을 위해 Realm 데이터베이스를 사용하였고 설정값 저장을 위해 SharedPreferences를 사용하였음.
    서버 -> 클라이언트에는 Google Cloud Messaging을 사용하였음.
    클라이언트 -> 서버에는 HTTP 통신을 이용하였음. (Retrofit 사용)
    각각의 게시글은 서버 데이터베이스에 저장하였으며, 댓글은 게시글 객체 안에 Array로 저장하였음.
```

> Kkobugi
* 개인 외주 

>> 역할

```text
    안드로이드 클라이언트 메인 프로그래머
    데이터베이스 관리
```

>> 기획

```text
    현대 사회에서 휴대폰을 사용하느라 목이 구부정해진 사람들을 위하여 현재 자세를 알려주어 자세 교정을 유도하는 어플리케이션.
    현재 휴대폰을 각도에 따라서 자신의 상태를 알려주고 월별 통계를 알려주는 대시보드, Facebook 친구들과 연결하여 경쟁하도록 하는 랭킹, 친구 리스트를 볼 수 있음.
```

>> 기술

```text
    서버는 Node.JS로 구동하였으며 JavaScript(ECMAScript 5.1)으로 작성되었고, MongoDB를 사용하였음.
    클라이언트는 안드로이드로 구현하였으며, 로컬 데이터 캐싱을 위해 Realm 데이터베이스를 사용하였고 설정값 저장을 위해 SharedPreferences를 사용하였음.
    클라이언트 -> 서버에는 HTTP 통신을 이용하였음. (Retrofit 사용)
    유저의 월별, 일별 수치는 서버에 각각 개인 데이터베이스 객체에 저장하였음.
    휴대폰의 각도는 현재 활동 중일때 안드로이드 디바이스 내 자이로센서를 이용하여 각도를 받아와서 측정하였음.
```

> EVA
* 2016 제 2회 선린해커톤 금상 

>> 역할

```text
    안드로이드 클라이언트 메인 프로그래머
    Restful API 리스트 작성
```

>> 기획

```text
    "응답하라 0000년"이라는 주제를 가지고, 가까운 미래인 2020년, 잔돈이 사라지고 있는 과도기가 온다는 가정함.
    잔돈이 없으나, 현금만 받는 가게라던가 잔돈이 필요한 상황이 발생할 시 이용할 수 있는 소액을 유저끼리 전환해서 받는 서비스.
    카카오페이 혹은 기타 결제수단을 통해 크레딧을 충전해 놓고, 전환할 금액과 위치를 확인하고 EVA를 요청하면 근처에 있는 EVA 유저들이 수락함.
    평가를 통해 서비스에 피드백, 유저에게 평가를 할 수 있음.
    VIP 서비스로 드론 배송 시스템인 초호기 배송을 지원함.
```

>> 기술

```text
    서버는 Node.JS로 구동하였으며 JavaScript(ECMAScript 6)으로 작성되었고, PostgreSQL를 사용하였음.
    클라이언트는 안드로이드로 구현하였으며, 설정값 저장을 위해 SharedPreferences를 사용하였음.
    클라이언트 -> 서버에는 HTTP 통신을 이용하였음. (Retrofit 사용)
    서버 -> 클라이언트에는 Google Cloud Messaging을 사용하였음.
    클라이언트와 서버의 실시간 거래 상황 연동을 위하여 Socket을 사용하였음.
```

> SpaceBalloon
* 2016 화학 수행평가

>> 역할

```text
    안드로이드 클라이언트 메인 프로그래머
    백엔드 서버 프로그래머
    데이터베이스 관리
    Restful API 리스트 작성
```

>> 기획

```text
    
```

>> 기술

```text
    서버는 Node.JS로 구동하였으며 JavaScript(ECMAScript 6)으로 작성되었고, PostgreSQL를 사용하였음.
    클라이언트는 안드로이드로 구현하였으며, 설정값 저장을 위해 SharedPreferences를 사용하였음.
    클라이언트 -> 서버에는 HTTP 통신을 이용하였음. (Retrofit 사용)
    서버 -> 클라이언트에는 Google Cloud Messaging을 사용하였음.
    클라이언트와 서버의 실시간 거래 상황 연동을 위하여 Socket을 사용하였음.
```

