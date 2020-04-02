# GOODLUXE - 팀 프로젝트

> 제 목 : 중고 명품 거래 사이트
>
> 기 간 : 2개월
>
> 참여인원 : 5명


### 제작기간 - 2019/12/23 ~ 2020/2/23

* 1주차 ~ 2주차 : 주제선정 및 기능 정리

* 3주차 ~ 4주차 : UI 디자인 및 DB 설계

* 5주차 ~ 6주차 : UI 구현

* 6주차 ~ 9주차 : 기능 구현 및 통합 테스트

* 9주차 ~ 10주차 : 오류 테스트 및 마무리 작업


### 사용기술

> 회원가입 시 구글 SMTP를 이용한 인증, 도로명주소 API 연결

> 카카오/네이버 API를 이용한 간편 로그인

> 카카오맵 API를 이용한 위치소개

> Import를 이용한 카카오페이 정기결제 예약/취소

> 상품 리스트 무한스크롤

> 상품 리스트 필터를 이용한 여러가지 조건 적용

> 상품 위시리스트/예약/알람

> 상품 상세페이지 문의 및 리뷰

> 캘린더를 이용한 배송/반납일정

> 관리자와의 1:1 채팅

> 커뮤니티 게시판 및 댓글

> 마이페이지 구독정보, 포인트, 활동내역, 회원정보 수정/탈퇴, 개인쉐어

> 관리자 페이지 차트, 회원관리, 결제관리, 개인쉐어상품 수락/거절, 상품 반납처리

역할

1. DB 설계

2. SMTP를 이용한 email 인증, 서울시 공공데이터 도로명주소 API 연결

3. 상품 페이지

페이징 대신 무한스크롤 방식으로 상품 리스트 출력
다중 필터로 특정 상품 검색 가능
4. 상품 상세 페이지

위시리스트, 북마크, 찜 등록or취소
상품 리뷰, 상품 문의 작성
5. 상품 등록, 수정, 삭제 페이지

6. 상품과 관련된(위시리스트, 예약, 찜 기타 등등) 마이페이지 및 관리자 페이지 구현

7. 기타 전반적인 부분 수정 및 관리

8. .war 파일 AWS EC2에 배포(openjdk 1.8 && apache tomcat 8.5 && AWS RDS(Oracle))
