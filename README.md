# AD 프로젝트

- 파이보 서비스에 부족한 점을 보완하는 서비스 6개 구축 (아마도 3-16 의 도전 과제를 의미)
- 3-13 (스크롤 초기화) 부분부터 4-15 (PostgreSQL데이터베이스 적용하기) 내용 중 원하는 서비스 3개 구현해 보기
- 총 6개 서비스 구현 (3개 + 3개)
- 3분 시연 영상 제작 + ppt

## 도전 과제

- [ ] 도전 1: 답변 페이징과 정렬 기능
  - 성능을 위해서라도 답변 페이징은 반드시 필요하다.
  - 답변을 보여줄 때 최신순, 추천순 등으로 정렬하여 보여줄 기능도 필요하다.

- [ ] 도전 2: 카테고리 기능 만들기
  - 현재 파이보는 질문으로만 게시판이 구성되지만 여기에 '강좌'나 '자유게시판'과 같은 게시판을 더 만들고 싶을 수도 있다.
  - 이런 경우 Question 모델에 카테고리 개념을 적용해야 한다.

- [ ] 도전 3: 비밀번호 찾기, 변경 기능 만들기
  - 비밀번호를 잃어버렸을 때 가입할 때 입력한 이메일 주소로 임시비밀번호를 발송하여 로그인할 수 있도록 조치하는 간단한 기능을 구현해 보자.
  - 임시비밀번호는 1회 사용할 수 있도록 하고, 사용한 뒤 비밀번호를 강제로 변경하도록 만들면 더 좋다.

- [ ] 도전 4: 프로필 화면 보여주기
  - 로그인한 사용자의 프로필 화면을 만들어 보자.
  - 이 화면에는 사용자의 기본 정보와 작성한 질문, 답변, 댓글이 보이면 좋다.

- [ ] 도전 5: 최근 답변과 최근 댓글 기능 추가하기
  - 사용자는 최근 답변이나 최근 댓글이 궁금할 수도 있다.
  - 최근 답변과 최근 댓글을 확인할 수 있는 기능을 추가해 보자.

- [ ] 도전 6: 조회 수 표시하기
  - 현재 파이보는 답변 수와 추천 수를 알 수 있지만 조회 수는 표시하지 않는다.
  - 조회 수가 표시 되도록 수정해 보자.

- [ ] 도전 7: 소셜 로그인 추가하기
  - 파이보에 구글이나 페이스북, 트위터 등을 경유하여 로그인하는 소셜 로그인 기능을 구현해 보자.

- [ ] 도전 8: 마크다운 에디터 적용하기
  - 마크다운 문법을 더 쉽게 입력할 수 있는 마크다운 에디터를 적용해 보자.
  - 인터넷을 찾아보면 추천하는 마크다운 에디터가 몇 가지 있는데, 그중에서 simpleMDE(simplemade.com)를 추천한다.

- [ ] 03-13 스크롤 초기화 문제점 해결하기
- [ ] 03-14 마크다운 기능 적용하기
- [ ] 03-15 검색, 정렬 기능 추가하기
- [ ] 04-1 깃으로 버전 관리하기
- [ ] 04-2 깃허브 사용해 보기
- [ ] 04-3 파이보를 위한 서버 운영 방법 알아보기
- [ ] 04-4 AWS 라이트세일 사용해 보기 – 1달 무료
- [ ] 04-5 세상에 파이보 공개하기
- [ ] 04-6 서버·개발 환경을 위한 settings 분리하기
- [ ] 04-7 MobaXterm으로 서버에 접속하기
- [ ] 04-8 웹 브라우저와 서버, 파이보 작동 방식 이해하기
- [ ] 04-9 WSGI 서버 Gunicorn 사용하기
- [ ] 04-10 웹 서버, Nginx 사용해서 파이보에 접속하기
- [ ] 04-11 서버 환경에서 장고 Admin 사용하기
- [ ] 04-12 서버 환경에서 DEBUG 모드 끄기
- [ ] 04-13 장고에 로깅 적용하기
- [ ] 04-14 파이보에 도메인 적용하기 – 비용 발생
- [ ] 04-15 PostgreSQL 데이터베이스 적용하기