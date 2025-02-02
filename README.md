### 😎 프로젝트 소개 
프로그래머스 데브코스 과정 수강 중 수행한 과제입니다. <br>
일대다의 연관 관계를 가지는 회원과 게시글엔티티에 대한 API 를 구현하였습니다.

### 👩‍💻 구체적인 요구 사항
과제 [링크](https://ancient-citron-06b.notion.site/SpringBoot-Part4-7-632dd10678164daca96a5ea185a02b60) 입니다.

### 🤔 신경 쓰고 고민 한 부분

- 서비스가 아닌 도메인에 로직을 응집시키지 위해 노력하였습니다.


- 테스트를 작성해였습니다.
  - 테스트 코드의 가독성을 위해 테스트가 정말로 관심있어 하는 부분에 대한 검증만을 수행하기 위해 노력하였습니다.
  - [링크](https://backtony.github.io/spring/2021-10-15-spring-test-3/) 를 참고하여 컨트롤러 테스트시 공통되는 부분을 추상화 하고 레스트 독스를 활용한 API 문서화의 가독성을 높였습니다.
  

- 인증을 구현하지 않고 게시글의 작성 및 수정 API 를 말이 되게 구현하기 위해 http 인증 헤더에 로그인 아이디를 포함 하는 방식을 채택하였습니다. 