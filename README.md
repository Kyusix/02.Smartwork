# ◈ Smartwork (내부업무 모듈)
### ■ 개요
 - 내부 업무정보시스템의 역할 및 도입 기대효과 (예시 : 유지보수계약관리/기술지원 관리업무)

   ![00  내부 업무정보시스템의 역할](https://github.com/user-attachments/assets/8ecf7ea6-e931-437f-9760-b979afa3cb3b)

 - UI/UX GUI 툴 이용하여 사용자화면 구성 (예시 : 유지보수계약관리)

   ![01  UXUI툴 수정화면](https://github.com/user-attachments/assets/9cb28271-8de8-4a35-83f8-4e08eb64c2ae)


- 구성한 필드에 고유값(NAME or ID)부여한 뒤 jQuery java 라이브러리 기반 스크립트를 통해 의도한 동작적용

   ![02  필드값수정화면](https://github.com/user-attachments/assets/badb4078-5c8b-46a5-8e7a-4d3019da9cca)


- 스크립트 작성 적용예시 (예시업무 : 유지보수계약관리)  
  : 각 결재서식 별 적용된 소스코드 전문은 'Smartwork/업무명' 소스공유
 
   ![03  스크립트 적용화면](https://github.com/user-attachments/assets/7316730c-8d23-45fd-80ed-4848a369ff28)

- 구현된 목표시스템 데이터 입력 사용자 화면 예시 (예시업무 : 유지보수계약관리)

   ![04  유지보수계약관리 사용자화면](https://github.com/user-attachments/assets/6a5b55d2-06be-48eb-b1ff-e64955e6ff72)

- 구현된 목표시스템 입력된 데이터 목록화면 예시 (예시업무 : 유지보수계약관리)

   ![05  목록데이터](https://github.com/user-attachments/assets/6f4104a9-1a7e-4d47-b65b-60d2acbd9be9)

- 구현된 목표시스템 데이터 적재 집계 총괄표 예시 (예시업무 : 유지보수계약관리)  
  : 집계는 목록데이터 활용하여 웹스프레드시트 내 엑셀 배치함수 활용

   ![06  웹스프레드시트](https://github.com/user-attachments/assets/83cb0ee8-badb-4500-a8c4-e53de99c4f11)


### ■ 적용효과
- 특정 필드에 정해진 입력 데이터 속성 값만 입력되거나 일부 기초데이터 항목만 입력할 수 있도록 사용자 통제  
  : ex) Date, Int 등
  
- 문자열 뿐만 아니라 Radio, Select, Check, Calendar(Date) 등 사용자 입력한 필드값으로 다른 필드 값을 자동생성  
  : ex) 수량, 단가 입력한 값을 기반으로 총액 및 요율 등 관리목적 필드값 자동계산  
  : ex) 시작일/종료일 선택값을 기반으로 계약기간 월수/일수 자동계산 (투입인력 MM 산출 기초값)
  
- 데이터 중앙화를 통해 엑셀오프라인 업무처리구조 개선하여 부서간 데이터 불일치 방지  
  : 시스템 내 목록화 및 웹 스프레드시트 활용한 통계 자동배치 업데이트 프로세스 적용  
  : 유관부서 담당자 시스템 데이터 접근권한 부여하여 개별관리를 방지  
  : 데이터 필드 CRUD 로그(내역) 관리로 담당자 부재/변경 시 업무연속성 확보

- 개별 데이터 필드 값 적재된 DB 테이블 내부통제관리 이기종 정보시스템(ERP, PMS, SW솔루션 등) 정보연계

#

### ■ 구현된 시스템 사용자 화면 예시 (업무명 클릭)

<details>   
  <summary>01.고객정보관리</summary>
  <br>
  <img src="https://github.com/user-attachments/assets/85319ee3-2548-4829-b506-bdc476d7bb22">
</details>

<details>
  <summary>02.영업카드관리  </summary>
   <br>
   <img src="https://github.com/user-attachments/assets/51e20293-bf3a-4171-98da-d8d771809b08">
   <img src="https://github.com/user-attachments/assets/3a72d7a5-5bc2-4b88-a693-d0fad7bc03a3">
   <img src="https://github.com/user-attachments/assets/d61e9c7f-1b71-4aed-bbfe-6eaec9aa7f21">
</details>

<details>
  <summary>03.유지보수계약관리  </summary>
   <br>
   <img src="https://github.com/user-attachments/assets/5784c4d5-2672-4236-bc1a-8f63c4578df0">
   <img src="https://github.com/user-attachments/assets/bd9eb2e6-7623-4796-ba66-10d763c83733">
</details>

<details>
  <summary>04.라이선스신청  </summary>
   <br>
   <img src="https://github.com/user-attachments/assets/826ab9a8-bf8c-4651-88ac-f78b5f4d9ecf">
</details>

<details>
  <summary>05.라이선스발급  </summary>
   <br>
   <img src="https://github.com/user-attachments/assets/9e526129-aa61-4f18-8442-5751c1fe7d32">
</details>

<details>
  <summary>06.프로젝트현황관리  </summary>
   <br>
   <img src="https://github.com/user-attachments/assets/9d33dd1b-faf9-43a8-a6c9-13c62f4759b8">
   <img src="https://github.com/user-attachments/assets/5d4bc5fc-569a-4894-971d-02caaf602b40">
</details>

<details>
  <summary>07.경조금지급신청  </summary>
   <br>
   <img src="https://github.com/user-attachments/assets/46529f4b-e0c6-4854-8d85-8eb6c8a10e4e">
</details>

#### - 끝 -
