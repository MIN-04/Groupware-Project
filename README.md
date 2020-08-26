# Groupware-Project
[쌍용강북교육센터] 3차 프로젝트 : Groupware - April (프로젝트 기간 : 2020.03 - 2020.05)


# April

## 목차
+ 프로젝트명 / 팀명
+ 팀원 / 팀장
+ 담당업무
+ 개발환경
+ 개발아키텍쳐 : MVC
+ 프로젝트 화면 구성
+ 요구사항정의서
+ ERD
+ WBS
  
  
### 1. 프로젝트명 / 팀명
    - Groupware / April
   
    
### 2. 팀원 / 팀장
    - 팀장 : 양은영
    - 팀원 : 김주희, 이지은, 이재원, 정수연, 김민지   
    
### 2.1. 담당업무
    - 1) 업무 연락 : 김민지
        - 1.1) Email Alarm 기능 : 최근 30분 이내에 수신 받은 업무 연락(메일)을 상단바 아이콘에 띄우기
        - 1.2) 받은 메일함 페이지 :
                - 받은 메일 목록 Retrieve
                - 읽지 않은 메일 갯수 표시 및 아이콘(닫힌 봉투)/색 지정, 수신 날짜/시간 출력
                - 읽은 메일 아이콧(열린 봉투)/색 지정, 수신 날짜/시간 출력
                - check box로 여러개 메일 선택 후 읽음 기능
                - 하나의 메일만 답변 기능 (수신자, 발신자, 제목, 원본 내용 자동 입력)
                - check box로 여러개 메일 삭제 기능
        - 1.3) 보낸 메일함 페이지 : 내가 보낸 메일 목록 Retrieve (클릭 시, 내용 확인 가능)
        - 1.4) 휴지통 페이지 : 삭제한 메일 목록 Retrieve (클릭 시, 내용 확인 가능)
    
    - 2) 관리자 : 김주희
    - 3) 전사게시판 : 양은영
    - 4) 업무등록 : 이재원
    - 5) 근태관리 및 예약 : 이지은
    - 6) 채팅 : 정수연
  
### 3. 개발환경
    - OS            :   Windows 10 pro
    - JDK           :   Java SE 8 (Oracle JDK 1.8)
    - CM            :   Github
    - Tools         :   Spring Tool Suite 4 /SQLDeveloper
    - 라이브러리    :   java-json.jar / log4j-1.2.17.jar / ojdbc6.jar
    - Front-end     :   JavaScript / Jquery / JSP / Ajax / Html5 / Bootstrap / CSS
    - Back-end      :   Java / Servlets / Oracle / Apache Maven / Mybatis

### 4. 개발아키텍쳐 : MVC
![April_WBS](https://github.com/HYKim8/April/blob/master/aprilPrj/src/main/webapp/WEB-INF/doc/April_MVC.png "April_MVC")  

### 5. 프로젝트 화면 구성
1. 업무 연락 : 김민지
    + Email Alarm 기능 : 최근 30분 이내에 수신 받은 업무 연락(메일)을 상단바 아이콘에 띄우기  
    
    ![April_메일_받은메일_알람.png](https://github.com/MIN-04/Groupware-Project/blob/master/GroupwarePrj/src/main/webapp/WEB-INF/doc/April_%EB%A9%94%EC%9D%BC_%EB%B0%9B%EC%9D%80%EB%A9%94%EC%9D%BC_%EC%95%8C%EB%9E%8C.png "April_메일_받은메일_알람.png")
    
    + 받은 메일함  
    
    ![April_메일_받은메일함.png](https://github.com/MIN-04/Groupware-Project/blob/master/GroupwarePrj/src/main/webapp/WEB-INF/doc/April_%EB%A9%94%EC%9D%BC_%EB%B0%9B%EC%9D%80%EB%A9%94%EC%9D%BC%ED%95%A8.png "April_메일_받은메일함.png")
    
    + 보낸 메일함  
    
    ![April_메일_보낸메일함.png](https://github.com/MIN-04/Groupware-Project/blob/master/GroupwarePrj/src/main/webapp/WEB-INF/doc/April_%EB%A9%94%EC%9D%BC_%EB%B3%B4%EB%82%B8%EB%A9%94%EC%9D%BC%ED%95%A8.png "April_메일_보낸메일함.png")
    
    + 답장  
    
    ![April_메일_답장.png](https://github.com/MIN-04/Groupware-Project/blob/master/GroupwarePrj/src/main/webapp/WEB-INF/doc/April_%EB%A9%94%EC%9D%BC_%EB%8B%B5%EC%9E%A5.png "April_메일_답장.png")
    
    + 휴지통  
    
    ![April_메일_휴지통.png](https://github.com/MIN-04/Groupware-Project/blob/master/GroupwarePrj/src/main/webapp/WEB-INF/doc/April_%EB%A9%94%EC%9D%BC_%ED%9C%B4%EC%A7%80%ED%86%B5.png "April_메일_휴지통.png")
    
2. 관리자 : 김주희
    + 대쉬보드  
    
    ![April_대쉬보드1.png](https://github.com/MIN-04/Groupware-Project/blob/master/GroupwarePrj/src/main/webapp/WEB-INF/doc/April_%EB%8C%80%EC%89%AC%EB%B3%B4%EB%93%9C1.png "April_대쉬보드1.png")
    
    ![April_대쉬보드2.png](https://github.com/MIN-04/Groupware-Project/blob/master/GroupwarePrj/src/main/webapp/WEB-INF/doc/April_%EB%8C%80%EC%89%AC%EB%B3%B4%EB%93%9C2.png "April_대쉬보드2.png")
    
    + 조직데이터  
    
    ![April_조직 데이터.png](https://github.com/MIN-04/Groupware-Project/blob/master/GroupwarePrj/src/main/webapp/WEB-INF/doc/April_%EC%A1%B0%EC%A7%81%20%EB%8D%B0%EC%9D%B4%ED%84%B0.png "April_조직 데이터.png")
    
3. 전사게시판 : 양은영
    + 전사게시판  
    
    ![April_전사게시판.png](https://github.com/MIN-04/Groupware-Project/blob/master/GroupwarePrj/src/main/webapp/WEB-INF/doc/April_%EC%A0%84%EC%82%AC%EA%B2%8C%EC%8B%9C%ED%8C%90.png "April_전사게시판.png")

4. 업무등록 : 이재원
    + TODO  
    
    ![April_TODO.png](https://github.com/MIN-04/Groupware-Project/blob/master/GroupwarePrj/src/main/webapp/WEB-INF/doc/April_TODO.png "April_TODO.png")
    
5. 근태관리 및 예약 : 이지은
    + 근태관리
    
    ![April_근태관리.png](https://github.com/MIN-04/Groupware-Project/blob/master/GroupwarePrj/src/main/webapp/WEB-INF/doc/April_%EA%B7%BC%ED%83%9C%EA%B4%80%EB%A6%AC.png "April_근태관리.png")

6. 채팅 : 정수연
    + Chat  
    
    ![April_Chat.png](https://github.com/MIN-04/Groupware-Project/blob/master/GroupwarePrj/src/main/webapp/WEB-INF/doc/April_Chat.png "April_Chat.png")
    
### 6. 요구사항정의서
![April_WBS](https://github.com/HYKim8/April/blob/master/aprilPrj/src/main/webapp/WEB-INF/doc/APRIL_%EC%9A%94%EA%B5%AC%EC%82%AC%ED%95%AD%EC%A0%95%EC%9D%98%EC%84%9C(SRS).PNG "April_SRS")  

### 7. ERD
![April_ERD.png](https://github.com/MIN-04/Groupware-Project/blob/master/GroupwarePrj/src/main/webapp/WEB-INF/doc/April_ERD.png "April_ERD.png")  

### 8. WBS
![April_WBS](https://github.com/HYKim8/April/blob/master/aprilPrj/src/main/webapp/WEB-INF/doc/April_WBS.png "April_WBS")


