# ■ 프로젝트명: daon

# ■ Daon 데이터 분석 도서 서비스

<table>
  <thead>
    <tr>
      <th>항목</th>
      <th>내용</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>개발 기간 </td>
      <td>2024년 12월 05일 ~ 2024년 12월 20일</td>
    </tr>
    <tr>
      <td>팀 구성</td>
      <td>이한세 외 6명</td>
    </tr>
    <tr>
      <td>프로젝트 목표</td>
      <td>
        <ul>        
          <li>머신 러닝, Python 등 데이터 분석 관련 전문 도서 서비스</li>  
          <li>도서의 상세 설명을 통해 학습에 필요한 원활한 정보 제공</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>



## ■ 목차  
1. 소개  
2. 프로젝트 진행 관리  
3. 사용 기술 스택 (Stacks)  
4. 화면 구성  
5. ER Diagram  
6. Use Case Diagram  



## ■ 프로젝트 진행 관리  
![image](https://github.com/user-attachments/assets/e711f654-7cd1-40d8-8636-98c97f8ba907)

## ■  Skill & Tools

### ▪ Language
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
</p>

### ▪ Backend
<p>
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white"/>
  <img src="https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyMySQL-00758F?style=for-the-badge&logo=mysql&logoColor=white"/>
</p>

### ▪ Frontend
<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white"/>
</p>

### ▪ Dev Tools
<p>
  <img src="https://img.shields.io/badge/VS Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"/>
  <img src="https://img.shields.io/badge/venv-3C3C3C?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/DBeaver-372923?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/UML-0D1839?style=for-the-badge&logo=uml&logoColor=white"/>
</p>




## ■ 화면 구성

### ▪ 장바구니 페이지  
![장바구니 페이지](https://github.com/user-attachments/assets/2d90fc35-6409-4d4e-8327-f7464d0fe106)

- 장바구니 담기 및 리스트, 수량 수정


## ■ ER Diagram

  <img src="https://raw.githubusercontent.com/Kim-Mi-Gyeong/daon_mini/main/er diagram.png" width="500"/>

- **user**: 사용자 정보 (id, username, password, email 등)
- **products**: 도서 정보 (id, 이름, 가격, 설명, 이미지)
- **cart**: 장바구니 정보 (user 연결, 제품 연결, 수량, 가격)


## ■ Use Case Diagram

  <img src="https://raw.githubusercontent.com/Kim-Mi-Gyeong/daon_mini/main/use case diagram.png" width="720"/>

- 비회원은 회원가입, 상품 목록 조회, 검색, 상세 확인이 가능
- 회원은 로그인 후 장바구니 담기, 수량 수정 기능 제공
- 관리자는 상품, 회원, 장바구니 전체를 통합 관리


