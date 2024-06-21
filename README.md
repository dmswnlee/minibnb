# minibnb
숙박시설 예약 서비스


<br>

## 프로젝트 소개

🗂️ 배포한 사이트

[minibnb](https://minibnb.shop/)

🚨 주의! 회원가입 시 이미지 업로드는 아직 미구현이므로 이미지는 선택하지 않으셔도 됩니다. 회원가입 시 프로필 이미지는 "피카츄"입니다. 오류가 아니니 놀라지 마세요!

<br>

🗂️ PR 주소

[PR확인하기](https://github.com/humanpear/KDT_Mini_team1/pulls?q=is%3Apr+is%3Aclosed)

<br>

🗂️ 프로젝트 기간

24.03.18 ~ 24.04.05


<br>

🗂️ 사용 기술

React.js / TypeScript / tailwind css / React Query / zustand

<br>

🗂️ 팀원 소개
<table>
  <tr>
    <td align="center">
        <img src="https://github.com/humanpear/KDT_Mini_team1/assets/102540636/7d0db36f-57eb-414b-a6e6-6031c70429b0" width="150px;" alt=""/><br />
        <sub><b>임현성</b><br></sub>
    </td>
    <td align="center">
        <img src="https://github.com/dmswnlee/pay-system/blob/feat-eunjoo/src/assets/img/lej.png?raw=true" width="150px;" alt=""/><br />
        <sub><b>이은주</b><br></sub>
    </td>
    <td align="center">
        <img src="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2Fc3LgRw%2FbtsH9JU0PEG%2FEYulcbcOYyZKFQtMFgsQY1%2Fimg.png" width="150px;" alt=""/><br />
        <sub><b>박인배</b><br></sub>
    </td>
  </tr>
</table>

<br>

🗂️ 디렉토리 구조
```react
src
|-- components
|    |-- 기능A   
|      |-- file a
|-- utils  
|-- types   
|   |-- product.ts
|-- UI
|   |-- Modal.tsx
|   |-- Button.tsx
|-- pages
|   |-- HomePage.tsx
|   |-- SignupPage.tsx
|   |-- LoginPage.tsx
|   |-- ProductDetailPage.tsx
|   |-- CartPage.tsx
|   |-- MyPage.tsx
|   |-- OrderDetailPage.tsx
|   |-- PaymentPage.tsx
|   |-- OrderCompletePage.tsx
|-- store
|-- hooks
|-- icons
|-- context
```

<br>

## 기능구현

<br>

<table>
   <tr>
      <td align="center">로그인</td>
      <td align="center">홈페이지</td>
   </tr>
   <tr>
      <td  align="center"><img src="https://github.com/humanpear/KDT_Mini_team1/assets/102540636/8eeab8b5-825b-48cd-b8a0-dbdf423ce324" width="400" height="300"/> </td>
      <td  align="center"><img src="https://blog.kakaocdn.net/dn/cgdOEp/btsH8UwfPQ3/5LxkkfZTKKW7M0iSWfaHcK/img.gif" width="400" height="300"/> </td>
   </tr>
   <tr>
      <td  align="center">로그인 폼을 통해 로그인 및 회원가입</td>
      <td  align="center">숙박시설 전체조회 및 카테고리 필터링</td>
   </tr>
</table>

<table>
   <tr>
      <td align="center">숙박시설 상세페이지</td>
      <td align="center">예약요청 페이지</td>
   </tr>
   <tr>
      <td  align="center"><img src="https://blog.kakaocdn.net/dn/JIbZi/btsH8AZjBqs/gHdE4iXbhqvpabBytYN5Mk/img.gif" width="400" height="300"/> </td>
      <td  align="center"><img src="https://blog.kakaocdn.net/dn/q5jkC/btsH9LL3OX8/qEaGqrgaZOVlBQ7WdXtAt0/img.gif" width="400" height="300"/></td>
   </tr>
   <tr>
      <td  align="center">객실형태, 체크인, 체크아웃, 인원 옵션 선택 후 예약하기 <br /> 혹은 장바구니 담기 가능</td>
      <td  align="center">선택한 옵션 내역 확인 및 수정 가능, 약관 동의 후 예약요청</td>
   </tr>
</table>

<table>
   <tr>
      <td align="center">예약완료 페이지</td>
      <td align="center">장바구니 페이지</td>
   </tr>
   <tr>
      <td  align="center"><img src="https://blog.kakaocdn.net/dn/q5jkC/btsH9LL3OX8/qEaGqrgaZOVlBQ7WdXtAt0/img.gif" width="400" height="300"/></td>
      <td  align="center"><img src="https://github.com/humanpear/KDT_Mini_team1/assets/102540636/b6a6d213-3605-4d1a-ad60-aded656a6f76" width="400" height="300"/></td>
   </tr>
   <tr>
      <td  align="center">예약 확정 및 예약 내역 확인</td>
      <td  align="center">장바구니 담기 한 숙박시설 리스트 확인 및 주문 가능</td>
   </tr>
</table>

<table>
   <tr>
      <td align="center">마이페이지</td>
   </tr>
   <tr>
      <td  align="center"><img src="https://blog.kakaocdn.net/dn/zXP6m/btsH8TD6wh4/KmTgEilq877O8n0iZOd5Z0/img.gif" width="400" height="300"/></td>
   <tr>
      <td  align="center">내 정보, 예약내역 확인 가능</td>
   </tr>
</table>

<br>

## 팀원 별 구현기능

<br>

<img src="https://img.shields.io/badge/임현성-FF4154?style=flat&logo=&logoColor=white" />

- SignupPage - /signup
  - 회원가입
- LoginPage - /login
  - 로그인
- PaymentPage - /payment/:id
  - 만 14세 이상 이용 동의 ~~
  - 결제하기 ⇒ 상품 주문 처리
- OrderCompletePage - /payment/:id/complete
  - 결제 성공 시 주문 결과 출력
- OrderDetailPage - /order/:id
  - 주문 내역 페이지를 통해 내역 확인 (상세)
- CartPage - /cart
  - 장바구니 항목 조회
  - 장바구니 항목 삭제
- 기타
  - 라우트 관리 

<br>

<img src="https://img.shields.io/badge/이은주-764ABC?style=flat&logo=&logoColor=white" />

- homePage - /home
  - 전체 숙박 상품 목록 조회
  - 카테고리 분류
  - 무한 스크롤
- ProductDetailPage - /product:id
  - 개별 숙박 상품 상세 소개
  - 상품 선택 시 장바구니 담기 선택
  - 숙박 상품 옵션 선택
  - 바로 결제

<br>

<img src="https://img.shields.io/badge/박인배-F24E1E?style=flat&logo=&logoColor=white" />

- MyPage - /mypage
  - 회원 정보 조회
  - 예약 내역(주문 내역) 조회
- 기타
  - 깃허브 레파지토리 관리
  - 배포 및 환경변수 설정

<br>

## 브랜치 컨벤션
- main
    - develop
        - feature/a
        - feature/b
        - feature/c

<br>

## 커밋 컨벤션

- Add : 파일 생성
    - ex) Add : Member Entity 생성
- Feat : 기능 추가
    - ex) Feat : 회원가입 기능 추가
- Modify : 해당 기능 코드 수정
    - ex) Modify : 회원가입 검증 수정
- Fix : 버그 수정 (디버깅)
    - ex) Fix : 로그아웃 후 이동하는 페이지 변경
- Comment : 주석만 건드렸을 때
- Rename : 파일, 폴더명 수정 or 이동만 했을 때
- Remove : 파일 삭제만 했을 때
- Build : 빌드 관련 수정 (dependency 수정 등)
- Chore : import 정리, 포맷 정리 등 (필요하면 마지막에 쭉 돌리면 될 듯)
- Layout : Layout 구조 변경
- Lib : Library 변경 사항

