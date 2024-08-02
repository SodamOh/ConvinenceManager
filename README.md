# ConvinenceManager
편의점 점포 관리 시스템

[주요 기능]

1. 회원 관리 및 로그인아웃
  1) 회원가입   
    - 점포코드/아이디/비밀번호로 가입    
    - 비밀번호는 8~12자 이내의 영문자/숫자/특수문자 포함해야 가능   
    - 가입시 비밀번호는 인코딩하여 저장
  2) 로그인/로그아웃    
    - 앱 접근시 회원가입 및 관리자 승인된 아이디만 로그인 가능   
    - 로그인시 토큰 발행
    - 로그아웃 실행 또는 일정 시간 미사용시 자동 로그아웃(토큰 만료)  

2. 매출관리 ➜ 관리자 CRUD 가능, 사용자(회원)은 조회만 가능   
  - 일별 매출 현황: 조회 연월 내 1일부터 조회시점까지의 매출 조회  
  - 실시간 매출 조회 :    
    ① 시간대별 조회 : 조회 연월일의 1시간 기준 시간대별 매출 조회     
    ② 분류별 조회 : 조회 연월일의 상품 대분류별 실시간 매출 조회  

3. 발주 관리 ➜ 사용자 기준 CRUD 모두 가능 
  - 상품 리스트 발주 : 분류별 현 재고 조회 및 발주 기능 
  - 발주 입력 시 오전 09시 기준 발주 마감 및 재고 입고 처리 
 
4. 재고 관리 ➜ 관리자 CRUD 가능, 사용자(회원)은 조회만 가능 
  - 분류별 재고 현황 조회

[기술 스택] 
  - Java
  - Spring boot(gradle)
  - mySQL

[ERD]
![image](https://github.com/user-attachments/assets/0021011a-8eed-437a-af29-5c221cfea019)


[향후 계획]
  - 정산 관리 시스템 추가
  - 검품 시스템 추가 

