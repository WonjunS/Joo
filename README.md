# 쇼핑몰 개발 프로젝트

## 🍻 로고

<img src="https://user-images.githubusercontent.com/126144148/254469373-67430ae5-2fc7-4eca-949f-b63a809fca00.png">

**당신을 위한 완벽한 전통주!**


전국 각지의 술들이 궁금하지 않으신가요?

편의점에는 없어요. 마트에도 없습니다.

색다른 술이 먹고 싶은데.., 특별한 날에 뭐 먹지?

주랑주랑, 최적의 선택입니다

<br/>

## 🌈 개요

- **프로젝트 명칭**: 주랑주랑
- **제작 기간**: 2023년 6월 1일 ~ 2023년 6월 22일
- **참여 인원**: 7명
- **개발 언어**: Java
- **프로젝트 소개**: 주랑주랑은 우리나라의 전통주를 판매하는 온라인 쇼핑몰 사이트입니다. 우리가 흔히 접할 수 없는 우리나라 전국 각지의 색다른 술을 판매하기 위해서 이 쇼핑몰을 기획하게 되었습니다. 프로젝트를 진행하면서 그동안 배웠던 CRUD 작업을 포함한 쇼핑몰에 적용할 수 있는 다양한 기능들을 구현해보기 위해 이 프로젝트를 진행하게 되었습니다.
- **역할**: 팀장
- **개발 파트**:
  - 로그인/회원가입
  - 회원 관련 CRUD
  - 결제 기능


<br/>

## 기술 스택
**Back-End**
- Java 17
- Spring 5.1.5
- Spring Security
- MyBatis


**Front-End**
- JSP
- HTML / CSS
- JavaScript
- Bootstrap 5.3.0  


**Database**
- Oracle DB


**Build Tool**
- Maven

<br/>

## 데이터베이스 설계 (ERD)
![project_erd](https://github.com/WonjunS/Shopping-Mall/assets/93713151/be867310-1f1a-4f92-97e9-fc1f5bdb21f9)

<br/>

## 실행 화면 
<details><summary>메인 페이지</summary>
  
  #### 메인화면

  ![image](https://github.com/WonjunS/Shopping-Mall/assets/93713151/75fe4a00-5db4-40ec-8ecd-bd937a44ea3b)

  
  #### 상품 리스트

  ![image](https://github.com/WonjunS/Shopping-Mall/assets/93713151/83418d34-5d94-4676-9836-6023bbeaf184)


</details>  


<details><summary>회원</summary>
  
  #### 회원가입
  
  쇼핑몰의 회원가입 페이지 입니다.

  
  위 사진들은 회원가입 페이지에서의 예외 처리 및 이메일 인증 기능을 확인할 수 있습니다.
  

  #### 로그인
  
  쇼핑몰의 로그인 페이지 입니다.
  ![image](https://github.com/WonjunS/Shopping-Mall/assets/93713151/90000cd7-e04c-4261-88cd-0d7ccee4d7ad)

  
  
  #### 회원정보
  
  회원정보를 확인하는 페이지입니다. 수정하기 버튼을 클릭해서 회원정보를 수정할 수 있습니다.

  ![image](https://github.com/WonjunS/Shopping-Mall/assets/93713151/a613f95b-73c2-421e-8484-999da66b13b6)


  #### 리뷰 작성 내역

  회원은 본인이 작성한 리뷰 내역을 조회할 수 있습니다.

  ![image](https://github.com/WonjunS/Shopping-Mall/assets/93713151/f41689b5-fe6b-45ce-9824-e5e10ce8a29c)

  
</details>  


<details><summary>상품</summary>
  
  #### 상품 등록 페이지
  
  상품을 등록하는 페이지입니다. 상품의 이미지는 최대 5장까지 업로드 가능하며 상품을 등록하기 위해서는 이름, 가격, 수량, 최소 1장의 이미지등의 데이터를 입력해야합니다.
  
  
  #### 상품 수정 페이지
  
  상품을 수정하는 페이지입니다. 상품 리스트에서 상품 이름을 클릭하면 수정 페이지로 이동합니다.


  #### 상품 디테일 페이지

  ![image](https://github.com/WonjunS/Shopping-Mall/assets/93713151/1ee7ce9c-fa11-4652-b1d0-384e90cf044e)


</details>


<details><summary>문의</summary>

  #### 문의 리스트

  회원은 자신이 작성한 상품 문의 내역을 확인할 수 있습니다. 관리자가 해당 사용자가 작성한 문의에 대한 답변을 작성하면 답변여부 칸에 리뷰에 대한 답변 내용을 확인할 수 있습니다.
  
  ![image](https://github.com/WonjunS/Shopping-Mall/assets/93713151/ca2b7c80-ad62-4db8-aa29-42b9af7aae99)


  #### 문의 상세보기

  ![image](https://github.com/WonjunS/Shopping-Mall/assets/93713151/113ac05e-c2e0-4e9b-a163-5c4cb8fc37a5)

  
</details>


<details><summary>주문</summary>

  #### 장바구니
  
  현재 장바구니에 담긴 상품들을 확인 할 수 있습니다. 체크박스로 주문할 상품들을 고를수 있으며 수량도 조절할 수 있습니다. X 버튼을 누르면 상품을 제거할 수 있고, 상품을 다 고르면 우측 하단에 총 주문 금액이 표시됩니다.

  ![image](https://github.com/WonjunS/Shopping-Mall/assets/93713151/7dd2d763-a709-421f-8d22-0b1836a989f3)


  #### 주문 페이지

  ![image](https://github.com/WonjunS/Shopping-Mall/assets/93713151/5206fd43-b6dd-4979-8a47-fad6fff43689)


  
  #### 결제
  회원은 신용카드 결제 또는 카카오페이 중에 본인이 선호하는 방식으로 결제를 할 수 있습니다.

  ![image](https://github.com/WonjunS/Shopping-Mall/assets/93713151/5c9a522b-2be6-4be2-8c78-a6e9a3d38411)

 
  
  #### 주문내역
  
  사용자가 본인이 주문 내역을 리스트 형태로 확인할 수 있습니다. "배송 조회" 버튼을 클릭하면 주문의 현재 배송상태를 모달 창 형태로 확인할 수 있습니다. 사용자가 상품을 수령한 후 "구매 확정" 버튼을 클릭하면 주문이 완료되며 주문을 취소할 수 없게 됩니다. 구매 확정할 경우, 사용자는 본인이 주문한 상품에 대한 리뷰를 작성할 수 있습니다.

  ![image](https://github.com/WonjunS/Shopping-Mall/assets/93713151/5ab6479d-7c47-46e6-ad17-698cef367e78)
  
  
</details>


<details><summary>관리자</summary>

  #### 관리자 메인 페이지
  
  현재 장바구니에 담긴 상품들을 확인 할 수 있습니다. 체크박스로 주문할 상품들을 고를수 있으며 수량도 조절할 수 있습니다. X 버튼을 누르면 상품을 제거할 수 있고, 상품을 다 고르면 우측 하단에 총 주문 금액이 표시됩니다.
  
  
</details>


## 보완사항 및 후기
### 향후 추가하고 싶은 기능
- 관리자 페이지에서 상품 추가시 이미지 파일 등록 기능
- 네이버, 구글 같은 타 사이트 계정을 통한 소셜 로그인 구현 


### 느낀점
팀장으로서 그룹을 이끌며 프로젝트를 진행하게 되어 많은 부담감도 있었고, 초반에는 여러 시행착오도 있었지만, 많은 것을 배울 수 있었던 좋은 기회였던 것 같습니다. 다른 팀원들을 도와주면서 아는 부분도 복습하고, 코딩 외적인 부분에서도 팀을 리드하며 전보다 더 발전할 수 있는 계기가 되었습니다. 3주 간의 짧으면서도 긴 시간 동안 팀원들과 소통하고 협동하여 성공적으로 끝마친 첫 그룹 프로젝트였기에 많은 성취감을 느꼈습니다.
