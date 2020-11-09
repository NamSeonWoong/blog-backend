# ![]()Blog_Backend, Frontend

## Backend

* 서버 실행: node src

* 백엔드 Koa 프레임워크

  * Koa의 장단점: 메모리를 덜먹고 표현력이 좋다. 다른 프레임워크에 비해 미들웨어 작성이 쉽다. 기본적으로 뼈대 프레임워크라서 제공되는 미들웨어와 함께 사용해야만 하는 Express와 Hapi와 달리, 개발자가 필요한 미들웨어만 구성해 사용할 수 있다. ES6를 도입하고 있어 ES6 제너레이터를 사용할 수 있다.

    여전히 불안정하고 많은 양의 개발이 진행중이다. ES6를 사용하기 위해 최신 버전의 node.js를 사용해야 한다. (주, 이 문제는 지금도 해당하는지 모르겠음.) 미들웨어를 직접 작성할 수 있는게 장점일 수 있지만 단점일 수도 있다.

* Data Base: Mongoose

  * Mongoose: **mongoose**란, mongoDB라는 NoSQL 데이터베이스를 지원하는 노드의 확장모듈입니다. mongoose는 mongoDB의 ODM입니다. ODM은 Object Document Mapping의 약자로, 문서를 DB에서 조회할 때 자바스크립트 객체로 바꿔주는 역할을 합니다. mongoDB의 ODM에는 mongodb-native 등 여러 개가 있지만 그중 mongoose가 가장 많이 사용됩니다.

  * NoSQL

    ------

    기존의 데이터베이스들은 대부분 관계형 모델에 기반을 두고 있으므로 대부분 SQL이라는 질의문에 의해 데이터베이스를 수정, 갱신, 저장, 검색하도록 구성되어 있습니다. 그러나 최근 들어 이러한 관계형 데이터베이스 모델과는 다른 데이터베이스 관리 시스템에 대한 관심이 증가하고 있는데, 이러한 시스템을 일컬어 **NoSQL(Not Only SQL)**이라고 부르며 mongoDB는 이러한 데이터베이스 시스템 중 하나입니다. 빅데이터를 다룰 때 RDBMS로만 트래픽을 감당하기 어려워져 이를 해결하기 위해 탄생한 것이 NoSQL입니다. 관계형 데이터 모델을 사용하지 않고 SQL을 사용하지 않는 그 이외의 모든 데이터베이스 시스템 또는 데이터 스토어를 일컬어 **NoSQL**이라고 칭합니다. 가장 큰 특징은 확장성과 기용성, 높은 성능, 그리고 다양한 데이터 형태를 수용할 수 있다는 것입니다. 

    **NoSQL**은 무한에 가까운 확장성을 제공하는데, 이를 위해 NoSQL 데이터베이스는 단순한 키와 값의 쌍으로 이루어져 있습니다. 인덱스와 데이터는 분리되어 별도로 운영되며 고정된 스키마도 없습니다. RDBMS와는 다르게 테이블 스키마가 유동적이라 다양한 형태들의 데이터를 유연하게 처리할 수 있습니다. 대신 분산형 구조이기 때문에 분산 시스템의 특징을 반영합니다. NoSQL의 대표적인 제품은 구글의 빅테이블, 그리고 mongoDB 등이 있습니다. 그 밖의 NoSQL에는 Cassandra, HBase, Redis, Coherence, CouchDB, Couchbase, Riak 등이 있습니다.

* JWT Token: 다음과 같은 상황에서 JWT 가 유용하게 사용 될 수 있습니다:
  - **회원 인증:** JWT 를 사용하는 가장 흔한 시나리오 입니다. 유저가 로그인을 하면, 서버는 유저의 정보에 기반한 토큰을 발급하여 유저에게 전달해줍니다. 그 후, 유저가 서버에 요청을 할 때 마다 JWT를 포함하여 전달합니다. 서버가 클라이언트에게서 요청을 받을때 마다, 해당 토큰이 유효하고 인증됐는지 검증을 하고, 유저가 요청한 작업에 권한이 있는지 확인하여 작업을 처리합니다.
    서버측에서는 유저의 세션을 유지 할 필요가 없습니다. 즉 유저가 로그인되어있는지 안되어있는지 신경 쓸 필요가 없고, 유저가 요청을 했을때 토큰만 확인하면 되니, 세션 관리가 필요 없어서 서버 자원을 많이 아낄 수 있죠.

## Frontend

* 메인화면
  * ![1604914414463](C:\Users\Seon woong\AppData\Roaming\Typora\typora-user-images\1604914414463.png)
  * 

* 회원가입, 회원로그인 구현
  * ![1604914344140](C:\Users\Seon woong\AppData\Roaming\Typora\typora-user-images\1604914344140.png)
  * ![1604914376580](C:\Users\Seon woong\AppData\Roaming\Typora\typora-user-images\1604914376580.png)
* 게시물 작성하기
  * ![1604914442049](C:\Users\Seon woong\AppData\Roaming\Typora\typora-user-images\1604914442049.png)
* 게시물 수정, 삭제 
  * ![1604914490491](C:\Users\Seon woong\AppData\Roaming\Typora\typora-user-images\1604914490491.png)





















