# study-thymeleaf-basic

타임리프 기본 - 
1. 데이터 출력하기
   - <h1>컨텐츠에 데이터 출력하기</h1>
   - th:text, th:utext 
2. SpringEL 표현식
  - Object, List, Map에서 각각 데이터 끄내는법
  - 지역 변수 -> th:with
3. 식 기본 객체 (Expression Basic Objects)와 편의객체
4. 유틸리티 객체와 날짜
5. 리터럴  - th:text="|hello ${data}|" -> 파이프라인 사용법 등..
6. 연산 - th:text="${data}?: '데이터가 없습니다.'"  -> ?를 이용하여 nullpointException 처리.
       - th:text="${data}?: _"   -> _ 이용하여 아무것도 안함 처리
7. 속성값처리 -> th:attrappend, th:attrprepend, th:classappend, th:checked 사용법
8. 반복 -> th:each
9. 조건 -> th:if, th:unless, th:switch,th:case
10. 주석 -> 표준 HTML 주석, 타임리프 파서 주석, 타임리프 프로토타입 주석
11. 블록 -> th:block
12. 자바스크립트 인라인 -> <script th:inline="javascript">
13. 템플릿 레이아웃 -> fragment, layout, layoutExtend
