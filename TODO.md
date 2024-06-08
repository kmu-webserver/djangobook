# TODO

## 도전 1: 답변 페이징과 정렬 기능
- 성능을 위해서라도 답변 페이징은 반드시 필요하다.
- 답변을 보여줄 때 최신순, 추천순 등으로 정렬하여 보여줄 기능도 필요하다.

### AS-IS

<img width="1149" alt="image" src="https://github.com/kmu-webserver/djangobook/assets/25102702/97eea60c-e527-46af-90ac-a7a537cbc079">


### TO-BE
https://pybo.kr/pybo/question/detail/4/

![screencapture-pybo-kr-pybo-question-detail-4-2024-06-08-16_09_37](https://github.com/kmu-webserver/djangobook/assets/25102702/553715f7-3a07-4540-86c7-a31d24b951d0)


## 도전 2: 카테고리 기능 만들기
- 현재 파이보는 질문으로만 게시판이 구성되지만 여기에 '강좌'나 '자유게시판'과 같은 게시판을 더 만들고 싶을 수도 있다.
- 이런 경우 Question 모델에 카테고리 개념을 적용해야 한다.

### AS-IS

![screencapture-localhost-8000-pybo-2024-06-08-16_22_09](https://github.com/kmu-webserver/djangobook/assets/25102702/19e5dcee-485c-4210-9f5d-5c69d46615d0)


### TO-BE
https://pybo.kr/pybo/question/list/qna/

![screencapture-pybo-kr-pybo-question-list-qna-2024-06-08-16_25_26](https://github.com/kmu-webserver/djangobook/assets/25102702/c9569a77-6dc9-44bb-a4cb-c604eacb4241)


## 도전 3: 비밀번호 찾기, 변경 기능 만들기
- 비밀번호를 잃어버렸을 때 가입할 때 입력한 이메일 주소로 임시비밀번호를 발송하여 로그인할 수 있도록 조치하는 간단한 기능을 구현해 보자.
- 임시비밀번호는 1회 사용할 수 있도록 하고, 사용한 뒤 비밀번호를 강제로 변경하도록 만들면 더 좋다.

## 도전 4: 프로필 화면 보여주기
- 로그인한 사용자의 프로필 화면을 만들어 보자.
- 이 화면에는 사용자의 기본 정보와 작성한 질문, 답변, 댓글이 보이면 좋다.

### AS-IS

N/A

### TO-BE

https://pybo.kr/common/profile/base/1865/

<img width="943" alt="image" src="https://github.com/kmu-webserver/djangobook/assets/25102702/b1be7bcd-4f28-4791-8b81-fd3eb5c9d0bc">

<img width="943" alt="image" src="https://github.com/kmu-webserver/djangobook/assets/25102702/38e90469-102c-49d6-8238-df90cf6c380b">

<img width="941" alt="image" src="https://github.com/kmu-webserver/djangobook/assets/25102702/d44c23fc-8e8c-46d1-a7a3-3df313d31ca5">

<img width="942" alt="image" src="https://github.com/kmu-webserver/djangobook/assets/25102702/3afb445f-3b18-4cc1-bd14-c920d590a57e">

## 도전 5: 최근 답변과 최근 댓글 기능 추가하기
- 사용자는 최근 답변이나 최근 댓글이 궁금할 수도 있다.
- 최근 답변과 최근 댓글을 확인할 수 있는 기능을 추가해 보자.

### AS-IS

N/A

### TO-BE

https://pybo.kr/pybo/recent_list/

<img width="1192" alt="스크린샷 2024-06-08 오후 4 34 12" src="https://github.com/kmu-webserver/djangobook/assets/25102702/b26080c5-bb0e-4ced-9f48-46e90da4e8e8">


## 도전 6: 조회 수 표시하기
- 현재 파이보는 답변 수와 추천 수를 알 수 있지만 조회 수는 표시하지 않는다.
- 조회 수가 표시 되도록 수정해 보자.

### AS-IS

![screencapture-localhost-8000-pybo-2024-06-08-16_22_09](https://github.com/kmu-webserver/djangobook/assets/25102702/19e5dcee-485c-4210-9f5d-5c69d46615d0)


### TO-BE

https://pybo.kr/pybo/question/list/qna/

<img width="1183" alt="스크린샷 2024-06-08 오후 4 36 07" src="https://github.com/kmu-webserver/djangobook/assets/25102702/2d1fc1d7-50ab-4954-8db5-d488c816d972">


## 도전 7: 소셜 로그인 추가하기
- 파이보에 구글이나 페이스북, 트위터 등을 경유하여 로그인하는 소셜 로그인 기능을 구현해 보자.

### AS-IS

### TO-BE

## 도전 8: 마크다운 에디터 적용하기
- 마크다운 문법을 더 쉽게 입력할 수 있는 마크다운 에디터를 적용해 보자.
- 인터넷을 찾아보면 추천하는 마크다운 에디터가 몇 가지 있는데, 그중에서 simpleMDE(simplemade.com)를 추천한다.


## 03-13 스크롤 초기화 문제점 해결하기
- https://wikidocs.net/71792 참고

## 03-14 마크다운 기능 적용하기
- https://wikidocs.net/71795 참고

## 03-15 검색, 정렬 기능 추가하기
## 04-1 깃으로 버전 관리하기
## 04-2 깃허브 사용해 보기
## 04-3 파이보를 위한 서버 운영 방법 알아보기
## 04-4 AWS 라이트세일 사용해 보기 – 1달 무료
## 04-5 세상에 파이보 공개하기
## 04-6 서버·개발 환경을 위한 settings 분리하기
## 04-7 MobaXterm으로 서버에 접속하기
## 04-8 웹 브라우저와 서버, 파이보 작동 방식 이해하기
## 04-9 WSGI 서버 Gunicorn 사용하기
## 04-10 웹 서버, Nginx 사용해서 파이보에 접속하기
## 04-11 서버 환경에서 장고 Admin 사용하기
## 04-12 서버 환경에서 DEBUG 모드 끄기
## 04-13 장고에 로깅 적용하기
## 04-14 파이보에 도메인 적용하기 – 비용 발생
## 04-15 PostgreSQL 데이터베이스 적용하기
