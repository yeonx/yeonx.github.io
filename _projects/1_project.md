---
layout: page
title: 그루밍 무드
description: 감정을 어루만지는 AI 일기
img: assets/img/groomingmood.png
importance: 1
category: yeonhee's project
---


<h5>👩🏻‍💻 역할 </h5> `팀장` `백엔드` `프론트엔드` `챗봇` `CI/CD구축`

<br/><br/>
<h5>📅 개발기간 </h5> `22.09` ~  `22.12`

<br/><br/>
<h5>🛠 기술스택 </h5> 
백엔드 : `JAVA 17` `SPRINGBOOT` `queryDSL` `JPA` `MySQL` <br/>
프론트엔드 :  `REACT` `JAVASCRIPT` `CSS` <br/>
AI : `KoBERT` `STT`<br/>
인프라 : `DOCKER` `GITACTION` `AWS EC2` `AWS RDBMS` <br/>
협업 : `GITHUB` `NOTION`

<br/><br/>
<h5>📢 참고 </h5> 
- 세종대학교 졸업프로젝트 (캡스톤디자인)
- 팀원 : 3명

<br/><br/>
<h5>📌 GitHub</h5>
<div class="row">
<div class="repo p-2 text-center">
  <a href="https://github.com/Grooming-Mood/server">
    <img class="repo-img-light w-100" alt="Grooming-Mood/server" src="https://github-readme-stats.vercel.app/api/pin/?username=Grooming-Mood&repo=server&theme={{ site.repo_theme_light }}&show_owner=true">
    <img class="repo-img-dark w-100" alt="{{ include.repository }}" src="https://github-readme-stats.vercel.app/api/pin/?username=Grooming-Mood&repo=server&theme={{ site.repo_theme_dark }}&show_owner=true">
  </a>
  </div>
  <div class="repo p-2 text-center">
  <a href="https://github.com/Grooming-Mood/front">
    <img class="repo-img-light w-100" alt="Grooming-Mood/front" src="https://github-readme-stats.vercel.app/api/pin/?username=Grooming-Mood&repo=front&theme={{ site.repo_theme_dark }}&show_owner=true">
    <img class="repo-img-dark w-100" alt="{{ include.repository }}" src="https://github-readme-stats.vercel.app/api/pin/?username=Grooming-Mood&repo=front&theme={{ site.repo_theme_dark }}&show_owner=true">
  </a>
  </div>
</div>

<br/><br/>
<h5>🏆 수상</h5>
- 제 14회 창의설계경진대회 `우수상` 수상
- 제 11회 교내 공학교육인증 창의설계 경진대회 `장려상` 수상
- 2022-2 창의 학습공동체 `대상` 수상

<br/><br/>
<h5>📌 서비스 이용 방법</h5>

    ---
    1. 카메라를 보며 오늘 하루를 기록합니다.
    2. STT를 통해 일기는 자동으로 기록됩니다.
    3. AI가 표정과 목소리를 통해 감정을 자동으로 판단해줍니다.
    4. 판단한 감정에 따라 일기를 자동으로 꾸며줍니다.
    5. 감정에 따라 영화를 추천해줍니다.
    6. 챗봇을 통해 감정상담을 받을 수 있습니다.
    7. 다른 사람들의 일기를 보며 감정에 공감할 수 있습니다.
    ---

<br/><br/>

<h5>🖥️ 주요 화면 구성</h5>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/일기작성.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    일기 작성 페이지 (표정인식, 목소리인식 및 STT)
</div>

<div class="row">
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.html path="assets/img/그저그럼.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.html path="assets/img/기쁨.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.html path="assets/img/화남.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.html path="assets/img/슬픔.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    감정 판단 결과에 따라 일기를 꾸며줌 -> 배경색과 글꼴 그리고 캐릭터
</div>

<div class="row">
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.html path="assets/img/영화추천_그저그럼.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.html path="assets/img/영화추천_기쁨.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.html path="assets/img/영화추천_화남.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.html path="assets/img/영화추천_슬픔.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    감정 판단 결과에 따라 영화 추천
</div>



<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-2 mt-md-0">
        {% include figure.html path="assets/img/chatbot1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-2 mt-md-0">
        {% include figure.html path="assets/img/chatbot2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    챗봇을 통한 감정 상담
</div>

<br/><br/>
<h5>🛠️ 아키텍처</h5>
<div class="row">
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.html path="assets/img/groomingmood아키텍처.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
