<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <title>세무인사이드</title>
  <style>
    * {
      box-sizing: border-box;
    }
    html, body {
      margin: 0;
      padding: 0;
      height: 100%;
      background-color: #2d2a3a;
      font-family: 'Noto Sans KR', sans-serif;
      display: flex;
      align-items: center;
      justify-content: center;
    }
    .center-wrap {
      text-align: center;
      animation: fadeIn 1.2s ease forwards;
    }
    .logo {
      width: 100px;
      height: 100px;
      border-radius: 50%;
      background-color: #fff;
      display: flex;
      align-items: center;
      justify-content: center;
      margin: 0 auto 24px auto;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    .logo img {
      width: 70px;
      height: 70px;
    }
    .title {
      font-size: 2.2rem;
      font-weight: bold;
      color: white;
      margin-bottom: 30px;
    }
    .desc {
      background: #fff;
      border-radius: 12px;
      padding: 30px;
      max-width: 430px;
      margin: 0 auto;
      box-shadow: 0 2px 12px rgba(0,0,0,0.1);
      animation: fadeIn 1.6s ease forwards;
    }
    .desc-title {
      font-size: 1.2rem;
      font-weight: bold;
      margin-bottom: 16px;
    }
    .desc ul {
      list-style: none;
      padding: 0;
      margin: 0;
      text-align: left;
      font-size: 1.05rem;
    }
    .desc li {
      margin-bottom: 12px;
      line-height: 1.5;
    }
    .desc li::before {
      content: '✅';
      margin-right: 8px;
      color: #219653;
    }
    .btn {
      display: inline-block;
      background-color: #2d2a3a;
      color: #fff;
      padding: 14px 30px;
      font-size: 1.1rem;
      border: none;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
      margin-top: 24px;
      transition: background 0.2s ease;
    }
    .btn:hover {
      background-color: #1a1822;
    }

    @keyframes fadeIn {
      0% { opacity: 0; transform: translateY(30px); }
      100% { opacity: 1; transform: translateY(0); }
    }

    @media (max-width: 600px) {
      .desc {
        padding: 20px;
        max-width: 95vw;
      }
      .title {
        font-size: 1.6rem;
      }
    }
  </style>
</head>
<body>
  <div class="center-wrap">
    <div class="logo">
      <img src="https://em-content.zobj.net/source/microsoft-teams/363/owl_1f989.png" alt="owl" />
    </div>
    <div class="title">세무인사이드</div>
    <div class="desc">
      <div class="desc-title">세무인사이드 핵심 문장 3가지</div>
      <ul>
        <li>"지금, 나의 세무 실력을 점검할 시간입니다."</li>
        <li>"성장은 반복 속에서, 실력은 확인 속에서 만들어집니다."</li>
        <li>"우리는 점수를 넘어, 신뢰받는 전문가를 준비합니다."</li>
      </ul>
      <a class="btn" href="https://www.notion.so/231a2002c7578000974cc8fc086a7a91" target="_blank">시험보러가기</a>
    </div>
  </div>
</body>
</html>
