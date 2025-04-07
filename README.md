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
      <td>개발 기간 🗓️</td>
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
          <li>머신 러닝, Python 등 데이터 분석 관련 전문 도서 서비스 </li>  
          <li>도서의 상세 설명을 통해, 학습에 필요한 원활한 정보 제공 </li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

# ■ 목차 
  1. 소개
  2. 프로젝트 진행 관리
  2. 사용 기술 스택 (Stacks)
  3. 화면 구성
  4. ER Diagram
  5. Use case Diagram

# ■ 프로젝트 진행 관리 
![image](https://github.com/user-attachments/assets/e9f1e491-7ddd-49cc-9423-8a23135b8fa2)

<br>

# ■ Stacks 
<div style="text-align: left;">
<h3> ▪ Environment</h3>
<br>
<div style="display: flex; flex-wrap: wrap; gap: 10px; align-items: center;">
<img src="https://img.shields.io/badge/visual studio code-008FC7?style=for-the-badge&logo=visual studio code&logoColor=white">
<img src="https://img.shields.io/badge/jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white">
<img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
<img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
</div>

<h3> ▪ Frontend</h3>
<div style="display: flex; flex-wrap: wrap; gap: 10px; align-items: center;">
<img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
<img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white">
<img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
<img src="https://img.shields.io/badge/bootstrap 5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white">
<img src="https://img.shields.io/badge/chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white">
<img src="https://img.shields.io/badge/plotly.js-3b4cc0?style=for-the-badge&logo=plotly&logoColor=white">
<img src="https://img.shields.io/badge/ajax (jQuery)-0769AD?style=for-the-badge&logo=jquery&logoColor=white">
</div>

<h3> ▪ Backend</h3>
<div style="display: flex; flex-wrap: wrap; gap: 10px; align-items: center;">
<img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/flask-000000?style=for-the-badge&logo=flask&logoColor=white">
<img src="https://img.shields.io/badge/langchain-00A6FF?style=for-the-badge&logo=langchain&logoColor=white">
</div>

<h3> ▪ Database & Storage</h3>
<div style="display: flex; flex-wrap: wrap; gap: 10px; align-items: center;">
<img src="https://img.shields.io/badge/faiss vector DB-008000?style=for-the-badge&logo=faiss&logoColor=white">
</div>

<h3> ▪ Machine Learning & AI</h3>
<div style="display: flex; flex-wrap: wrap; gap: 10px; align-items: center;">
<img src="https://img.shields.io/badge/numpy-013243?style=for-the-badge&logo=numpy&logoColor=white">
<img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white">
<img src="https://img.shields.io/badge/matplotlib-11557c?style=for-the-badge&logo=matplotlib&logoColor=white">
<img src="https://img.shields.io/badge/scikit learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white">
<img src="https://img.shields.io/badge/word2vec-FFCC00?style=for-the-badge&logo=google&logoColor=black">
<img src="https://img.shields.io/badge/faiss-008000?style=for-the-badge&logo=facebook&logoColor=white">
<img src="https://img.shields.io/badge/HuggingFaceEmbeddings-FF9900?style=for-the-badge&logo=huggingface&logoColor=black">
<img src="https://img.shields.io/badge/cosine similarity-663399?style=for-the-badge&logo=mathworks&logoColor=white">
<img src="https://img.shields.io/badge/transformers-DC143C?style=for-the-badge&logo=ai&logoColor=white">
<img src="https://img.shields.io/badge/genai-FF66CC?style=for-the-badge&logo=google&logoColor=white">
<img src="https://img.shields.io/badge/youtube api-FF0000?style=for-the-badge&logo=youtube&logoColor=white">
</div>
<br>
<br>

# ■ 화면 구성 

<div style="display: flex; flex-direction: column; gap: 20px;">
  <h3> ▪ 메인 화면 페이지</h3>
  <div style="display: flex; align-items: center; gap: 20px;">
    <img src="cos/static/images/main_1.png" alt="메인 화면 페이지" style="width:300px; height:200px; border-radius: 5px;">
    <img src="cos/static/images/main_3.png" alt="메인 화면 페이지" style="width:300px; height:200px; border-radius: 5px;">
  </div>

  <h3> ▪ 성분 추천 결과 페이지</h3>
  <div style="display: flex; align-items: center; gap: 20px;">
    <img src="cos/static/images/results.png" alt="성분 추천 결과 페이지" style="width:300px; height:200px; border-radius: 5px;">
    <img src="cos/static/images/visualization_1.png" alt="추천 결과 시각화 페이지" style="width:300px; height:200px; border-radius: 5px;">
  </div>

  <h3> ▪ 추천 결과 시각화 페이지</h3>
  <div style="display: flex; align-items: center; gap: 20px;">
    <img src="cos/static/images/visualization_2.png" alt="추천 결과 시각화 페이지" style="width:600px; height:400px; border-radius: 5px;">
  </div>

  <h3> ▪ Chatbot</h3>
  <div style="display: flex; align-items: center; gap: 20px;">
    <img src="cos/static/images/chatbot_after_1.png" alt="chatbot" style="width:300px; height:200px; border-radius: 5px;">
    <img src="cos/static/images/chatbot_after_2.png" alt="chatbot" style="width:300px; height:200px; border-radius: 5px;">
  </div>
  
</div>
<br>


# ■ Data flow Diagram
<div>
  <img src="cos/static/images/Data flow.webp" style="width:auto; height:600px; border-radius: 5px; border: 2px solid black;">
<br>
</div>

# ■ Use case Diagram
<div>
  <img src="cos/static/images/user flow.webp" style="width:600px; height:400px; border-radius: 5px; border: 2px solid black;"><br>
</div>
