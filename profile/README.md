# TripTory <img src="https://github.com/user-attachments/assets/8e54ca2e-8b58-4c18-8c41-d477be83fb6d" width="100" align="left" />
행의 순간을 더 간편하고 아름답게 기억할 수 있도록, 생성형AI여행기록 서비스

<br/> 

<img src="https://github.com/user-attachments/assets/b5a3f88e-50ad-4331-abe0-a8539dde3f7e">

<br/>

<h2>🎇 기능 소개</h2>

### 🖐 회원가입 및 로그인
* OAuth를 통해 카카오, 네이버, 구글 회원가입 및 로그인이 가능합니다.

### 🧳 여행 등록하기
* 대표사진, 여행 이름, 여행 기간, 지역을 입력해 여행을 등록합니다.
* react-calendar 라이브러리를 사용해 여행 기간 선택 컴포넌트를 구현했습니다.
* 여행 수정 및 삭제가 가능합니다.

### 📝 일기 작성하기
* 메인 페이지의 여행 아이템을 클릭해 일기 리스트를 확인할 수 있습니다. 
* '**일기 등록하기**'를 통해 일기를 작성할 수 있으며 사진 첨부가 가능합니다.
* 일기 수정 및 삭제가 가능합니다.

### 👭 친구 초대하기, 친구 여행 참여하기
* '**일행 추가**' 버튼을 통해 여행에 친구를 초대할 수 있습니다. '일행 추가' 시 랜덤 코드가 부여되며, 친구들은 이 코드를 통해 여행에 들어올 수 있습니다.
* 메인 페이지에 '**여행 추가하기**' 버튼을 클릭하면 나오는 '**친구 여행 참여하기**' 를 통해 친구 여행에 참여할 수 있습니다. 친구에게 받은 랜덤 코드를 입력하면 참여가 완료됩니다.
* 초대된 여행에도 일기를 작성할 수 있으며 일기 내용은 친구들과 공유됩니다. 
  
### 🗺 나의 여행 지도
* 내가 포함된 여행들을 지도로 모아볼 수 있습니다.
* 해당 지역 위에 대표 사진이 포함된 마커가 떠있고, 마커 클릭 시 바텀시트로 여행의 대표 정보들이 표시됩니다.
* '**여행 보러가기**' 버튼을 통해 여행 페이지로 이동할 수 있습니다.

### 📆 내 캘린더
* 내가 참여한 여행 속 일기들을 날짜별로 모아볼 수 있습니다.
* 각 날짜의 일기에 첨부된 사진이 대표 이미지로 표시됩니다.
* 날짜를 눌러 원하는 일기로 넘어갈 수 있습니다.

### 🏷 태그 별 사진 보기
* 일기에 첨부된 사진들은 ai를 통해 자동으로 태그가 부여됩니다.
* 부여된 태그에 따라 사진첩이 만들어지며 메인 페이지에서 확인할 수 있습니다.
  
### 👀 마이 페이지
* 내 정보(프로필 사진, 이름)를 수정할 수 있습니다.
* 로그아웃하거나 회원 탈퇴할 수 있으며 회원 탈퇴 시 회원과 관련된 모든 정보가 DB에서 영구 삭제됩니다.

<br/>
<h2>👥 팀원</h2>

<table align="center">
    <tr align="center">
      <td style="min-width: 100px;">
            <a href="https://github.com/hummingbbird">
              <img src="https://github.com/hummingbbird.png" width="100" alt="프로필사진">
              <br />
              <b>이채영</b>
            </a>
        </td>
      <td style="min-width: 100px;">
            <a href="https://github.com/seo0o519">
              <img src="https://github.com/seo0o519.png" width="100" alt="프로필사진">
              <br />
              <b>강서영</b>
            </a>
        </td>
      <td style="min-width: 100px;">
            <a href="https://github.com/HeeNamgoong">
              <img src="https://github.com/HeeNamgoong.png" width="100" alt="프로필사진">
              <br />
              <b>남궁희</b>
            </a>
        </td>
      <td style="min-width: 100px;">
            <a href="https://github.com/hyni03">
              <img src="https://github.com/hyni03.png" width="100" alt="프로필사진">
              <br />
              <b>김은지</b>
            </a>
        </td>
        <td style="min-width: 100px;">
            <a href="https://github.com/mjk25">
              <img src="https://github.com/mjk25.png" width="100" alt="프로필사진">
              <br />
              <b>김민주</b>
            </a>
        </td>
    </tr>
    <tr align="center">
      <td>
            TL, Frontend <br/>
      </td>
       <td>
            Frontend <br/>
      </td>
       <td>
            Frontend, AI <br/>
      </td>
      <td>
            Backend <br/>
      </td>
      <td>
            Backend <br/>
      </td>
    </tr>
</table>

</br>

<h2>🛠 기술 스택</h2>

### 🖥 Frontend
<div align="center">

| 역할 | 종류 |
| -------------------- | ----- |
| Library | ![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=black) |
| Programming Language | ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white)|
| Styling | ![Styled Components](https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white)| 
|State Management|![Recoil](https://img.shields.io/badge/Recoil-007af4.svg?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyBpZD0iQ2FscXVlXzEiIGRhdGEtbmFtZT0iQ2FscXVlIDEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgdmlld0JveD0iMCAwIDI1NS4yMSA2MjMuOTEiPjxkZWZzPjxzdHlsZT4uY2xzLTF7ZmlsbDp3aGl0ZX08L3N0eWxlPjwvZGVmcz48cGF0aCBjbGFzcz0iY2xzLTEiIGQ9Im03NC42MiAyNzcuNDYgMS4yNC0uMTMgMzQuNzgtMy4yOC01My40Ny01OC42NkE5Ni40NyA5Ni40NyAwIDAgMSAzMiAxNTAuM0gzYTEyNS4zIDEyNS4zIDAgMCAwIDMyLjggODQuNTdaTTE3Ny4xMyAzNDdsLTM2IDMuNCA1My4zMiA1OC41MUE5Ni40MSA5Ni40MSAwIDAgMSAyMTkuNjMgNDc0aDI4LjkyYTEyNS4yOCAxMjUuMjggMCAwIDAtMzIuNzYtODQuNTdaIi8+PHBhdGggY2xhc3M9ImNscy0xIiBkPSJNMjUzLjY5IDIzMS42OGMtNi4zMy0zMS4zLTMwLjg5LTU0LjA5LTYyLjU3LTU4LjA3bC02LjM1LS43OWE0OS42MSA0OS42MSAwIDAgMS00My4zNS00OS4xM3YtMjBhNTIuNzUgNTIuNzUgMCAxIDAtMjguOTEtLjM2djIwLjM4YTc4LjU2IDc4LjU2IDAgMCAwIDY4LjY1IDc3LjgybDYuMzYuOGMyMy4yNCAyLjkyIDM0Ljc4IDIwIDM3LjgzIDM1LjFzLS45MyAzNS4zMi0yMS4yMiA0N2E3My44MSA3My44MSAwIDAgMS0zMC4wNiA5LjYybC05NS42NiA5YTEwMi40NSAxMDIuNDUgMCAwIDAtNDEuOCAxMy4zOEM5IDMzMi40NS00LjgxIDM2MyAxLjUyIDM5NC4yOXMzMC44OSA1NC4wOCA2Mi41NyA1OC4wNmw2LjM1LjhhNDkuNiA0OS42IDAgMCAxIDQzLjM1IDQ5LjEydjE4YTUyLjc1IDUyLjc1IDAgMSAwIDI4LjkxLjI2di0xOC4yNmE3OC41NSA3OC41NSAwIDAgMC02OC42NS03Ny44MWwtNi4zNi0uOGMtMjMuMjQtMi45Mi0zNC43OC0yMC4wNS0zNy44My0zNS4xMXMuOTMtMzUuMzIgMjEuMjItNDdhNzMuNjggNzMuNjggMCAwIDEgMzAuMDYtOS42M2w5NS42Ni05YTEwMi40NSAxMDIuNDUgMCAwIDAgNDEuOC0xMy4zOGMyNy42NS0xNi4wMiA0MS40LTQ2LjU0IDM1LjA5LTc3Ljg2WiIvPjwvc3ZnPg==&logoColor=white)| 
| Formatting | ![ESLint](https://img.shields.io/badge/eslint-4B32C3.svg?style=for-the-badge&logo=eslint&logoColor=white) ![Prettier](https://img.shields.io/badge/prettier-F7B93E.svg?style=for-the-badge&logo=prettier&logoColor=white) |
| Package Manager | ![Yarn](https://img.shields.io/badge/Yarn-2C8EBB.svg?style=for-the-badge&logo=Yarn&logoColor=white) |
| Version Control | ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) |

</div>

</br>

### 🖥 Backend

<div align="center">

| 역할 | 종류 |
| -------------------- | ----- |
| Programming Language | ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white)|
|Framework| ![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=Express&logoColor=white)|
|Build Tool|  |
|API| ![Rest](https://img.shields.io/badge/Rest_API-000000?style=for-the-badge&logo=iRobot&logoColor=white)
|Database| ![MongoDB](https://img.shields.io/badge/Mongo_DB-47A248?style=for-the-badge&logo=MongoDB&logoColor=white)|

</div>

</br>
<h2>📂 폴더구조</h2>
<details>
<summary>프론트엔드</summary>
<div markdown="1">

```
📦TripTory_client
 ┣ 📂AI
 ┃ ┗ 📜ImageTagAnalyze.py
 ┣ 📂public
 ┣ 📂src
 ┃ ┣ 📂assets
 ┃ ┃ ┣ 📂fonts
 ┃ ┃ ┣ 📂icons
 ┃ ┃ ┗ 📂images
 ┃ ┣ 📂components
 ┃ ┃ ┗ 📂common
 ┃ ┃ ┃ ┣ 📂map
 ┃ ┣ 📂data
 ┃ ┣ 📂layout
 ┃ ┣ 📂pages
 ┃ ┣ 📂recoil
 ┃ ┣ 📂routes
 ┃ ┃ ┗ 📜router.js
 ┃ ┣ 📂styles
 ┃ ┃ ┣ 📜color.js
 ┃ ┃ ┗ 📜globalStyle.js
 ┃ ┣ 📜App.css
 ┃ ┣ 📜App.js
 ┃ ┣ 📜App.test.js
 ┃ ┣ 📜index.css
 ┃ ┣ 📜index.js
 ┃ ┣ 📜reportWebVitals.js
 ┃ ┗ 📜setupTests.js
 ┣ 📜.eslintignore
 ┣ 📜.eslintrc.yml
 ┣ 📜.gitignore
 ┣ 📜.gitmessage(ko).txt
 ┣ 📜.gitmessage.txt
 ┣ 📜.prettierignore
 ┣ 📜.prettierrc
 ┣ 📜LICENSE
 ┣ 📜netlify.toml
 ┣ 📜package.json
 ┣ 📜README.md
 ┗ 📜yarn.lock
```
</div>
</details>

<details>
<summary>백엔드</summary>
<div markdown="1">

```
📦TripTory_server
 ┣ 📂.git
 ┣ 📂src
 ┃ ┣ 📂AI
 ┃ ┣ 📂diary
 ┃ ┣ 📂login
 ┃ ┣ 📂travel
 ┃ ┣ 📂user
 ┃ ┗ 📜oauth.js
 ┣ 📜.gitignore
 ┣ 📜index.js
 ┣ 📜package-lock.json
 ┣ 📜package.json
 ┗ 📜README.md
```
</div>
</details>
