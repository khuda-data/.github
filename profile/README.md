 <!--
# 제2회 KHUDA 데이터톤: *KHU'DATA*

이 GitHub는 **제2회 KHUDA 데이터톤**에 참가한 팀들의 모든 결과물을 모아두기 위한 공간입니다.

---

## 🎯 행사 개요

경희대학교 데이터 분석·AI 동아리 **KHUDA**가 주최하는 **2회차 데이터톤**입니다.  
다양한 학교의 학생들이 팀을 이루어 실생활 문제를 데이터로 해결하며,  
데이터 활용 역량과 협업 능력을 함께 키우는 것을 목표로 합니다.  

- 데이터 기반 문제 해결 능력 강화  
- 팀워크 및 커뮤니케이션 스킬 향상  
- 타 학교 학생들과의 네트워킹  
- 푸짐한 시상 및 상금 기회  

---

## 🤝 후원사

이번 데이터톤은 아래 후원사들의 지원으로 더욱 풍성하게 진행됩니다:

- **Perplexity**  
- **Monster Energy**  
- **한빛미디어**

---

## 📂 결과물 제출

각 팀은 팀 전용 Repository를 생성하고 완성된 결과물을 업로드 해주세요.

---

![제2회 KHUDA 데이터톤 포스터](https://github.com/user-attachments/assets/b93c04da-2b10-4630-8011-de30f59f2104)


-->
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>KHUDA 8th</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    @keyframes fade-in {
      from { opacity: 0; transform: translateY(10px); }
      to { opacity: 1; transform: translateY(0); }
    }
    @keyframes slide-up {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
    .animate-fade-in { animation: fade-in 0.8s ease-out; }
    .animate-slide-up { animation: slide-up 1s ease-out; }
  </style>
</head>
<body class="bg-black text-white font-sans px-6 py-10">

  <!-- Header -->
  <div class="text-center space-y-2 animate-fade-in">
    <h1 class="text-4xl font-bold tracking-tight">Kyung Hee University Data Analysis</h1>
    <p class="text-lg text-gray-300">
      <strong>KHUDA</strong>는 <strong>K</strong>yung <strong>H</strong>ee <strong>U</strong>niversity <strong>D</strong>ata <strong>A</strong>nalysis의 약자로,
      경희대학교 데이터 분석/AI 중앙동아리입니다.<br/>
      팀원과 함께 <strong class="text-white">성장</strong>하며, 본인의 한계를 <strong class="text-white">뛰어넘는</strong> 문화를 추구합니다.
    </p>
    <div class="flex justify-center gap-4 pt-4">
      <a href="https://www.instagram.com/khu_da.official" target="_blank">
        <img src="https://img.shields.io/badge/Instagram-E4405F?style=flat&logo=Instagram&logoColor=white"/>
      </a>
      <a href="https://github.com/khuda-data" target="_blank">
        <img src="https://img.shields.io/badge/Github-000000?style=flat&logo=Github&logoColor=white"/>
      </a>
      <a href="https://www.notion.so/KHUDA-8th-AI-KHUDA-236ca0f7fa4780aa889cc03ad5e02a97" target="_blank">
        <img src="https://img.shields.io/badge/Notion-02458D?style=flat&logo=Notion&logoColor=white"/>
      </a>
    </div>
  </div>

  <!-- Logo -->
  <div class="text-center mt-16 animate-slide-up">
    <h2 class="text-3xl font-bold mb-4">KHUDA 8th</h2>
    <img src="https://github.com/user-attachments/assets/7b28e1fe-02fa-481d-9315-960527ee3945" alt="KHUDA Logo" class="mx-auto w-40 mb-8"/>
  </div>

  <!-- Tracks -->
  <div class="mt-10 animate-fade-in">
    <h3 class="text-2xl font-semibold text-center mb-6">🔥 Advanced Tracks (심화 트랙)</h3>
    <p class="text-center text-gray-300 mb-10">
      KHUDA에서는 보다 심층적인 학습과 실전 프로젝트 경험을 제공하기 위해 <strong>5개의 심화 트랙</strong>을 운영합니다.
    </p>

    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6 max-w-5xl mx-auto">
      <div class="bg-gray-900 rounded-2xl p-5 shadow-lg hover:scale-105 transition-transform">
        <h4 class="text-xl font-bold">👁️ Computer Vision</h4>
        <p class="text-gray-300">이미지/영상 데이터 분석, CNN 및 최신 Vision 모델 학습, 논문 발제</p>
      </div>
      <div class="bg-gray-900 rounded-2xl p-5 shadow-lg hover:scale-105 transition-transform">
        <h4 class="text-xl font-bold">💼 Data Business</h4>
        <p class="text-gray-300">비즈니스 인사이트 기반 데이터 분석 및 전략적 접근</p>
      </div>
      <div class="bg-gray-900 rounded-2xl p-5 shadow-lg hover:scale-105 transition-transform">
        <h4 class="text-xl font-bold">🌐 Data Engineering</h4>
        <p class="text-gray-300">데이터 수집, 파이프라인 구축, ETL, DB 설계 등 데이터 인프라 실무</p>
      </div>
      <div class="bg-gray-900 rounded-2xl p-5 shadow-lg hover:scale-105 transition-transform">
        <h4 class="text-xl font-bold">💵 Finance</h4>
        <p class="text-gray-300">금융 시장 데이터 분석, 리스크 모델링, 기술적 지표 기반 전략</p>
      </div>
      <div class="bg-gray-900 rounded-2xl p-5 shadow-lg hover:scale-105 transition-transform sm:col-span-2 lg:col-span-1">
        <h4 class="text-xl font-bold">💬 NLP</h4>
        <p class="text-gray-300">언어 모델, LLM, 딥러닝 기반 자연어처리 모델 구현 및 실습</p>
      </div>
    </div>

    <p class="text-center text-gray-400 text-sm mt-6">
      각 트랙에서는 <strong>세션, 프로젝트, 코드 리뷰</strong> 등을 통해 실력을 체계적으로 쌓을 수 있습니다.  
      <br/>📌 <a href="https://www.notion.so/KHUDA-8th-AI-KHUDA-236ca0f7fa4780aa889cc03ad5e02a97" class="underline text-blue-400">자세한 내용은 노션에서 확인</a>
    </p>
  </div>

  <!-- 활동 내역 -->
  <div class="mt-16 animate-slide-up">
    <h3 class="text-2xl font-bold text-center mb-6">📚 KHUDA 활동 내역</h3>
    <div class="space-y-4 text-center text-base text-gray-300">
      <p>
        <strong>KHUDA-7th (25.03.04 ~ 25.07.09)</strong><br/>
        <a href="https://www.notion.so/KHUDA-7th-AI-KHUDA-17778008bf5880a7b78fe2c880a07b9f?pvs=4" target="_blank">
          <img src="https://img.shields.io/badge/Notion-02458D?style=flat&logo=Notion&logoColor=white"/>
        </a>
      </p>
      <p>
        <strong>KHUDA-6th (24.07.24 ~ 24.11.27)</strong><br/>
        <a href="https://boiled-stitch-a9a.notion.site/KHUDA-6th-AI-KHUDA-0a06a7da42a748a9b9ac3fa98646f61b?pvs=74" target="_blank">
          <img src="https://img.shields.io/badge/Notion-02458D?style=flat&logo=Notion&logoColor=white"/>
        </a>
      </p>
      <p>
        <strong>KHUDA-5th (24.01.29 ~ 24.05.27)</strong><br/>
        <a href="https://simple-board-99d.notion.site/c73b4ccb4b4f474198db0d931fa276fd?v=2c9c18f900eb40c0a3324a31a6cc1ef6" target="_blank">
          <img src="https://img.shields.io/badge/Notion-02458D?style=flat&logo=Notion&logoColor=white"/>
        </a>
      </p>
      <p>
        <strong>KHUDA-4th (23.07.28 ~ 23.12.06)</strong><br/>
        <a href="https://khuda.notion.site/KHUDA-4th-AI-KHUDA-4-45e8834854dc4402b00b9622c3aa68ee?pvs=4" target="_blank">
          <img src="https://img.shields.io/badge/Notion-02458D?style=flat&logo=Notion&logoColor=white"/>
        </a>
      </p>
    </div>
  </div>

</body>
</html>
