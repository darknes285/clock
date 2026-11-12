  <style>
    .pp-wrap {
      max-width: 820px;
      margin: 0 auto;
      padding: 20px;
      font-family: "맑은 고딕", "Malgun Gothic", "Apple SD Gothic Neo", sans-serif;
      color: #2c3e50;
      line-height: 1.7;
    }
    .pp-hero {
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
      color: #fff;
      padding: 40px 30px;
      border-radius: 20px;
      text-align: center;
      margin-bottom: 30px;
      box-shadow: 0 10px 30px rgba(102, 126, 234, 0.3);
    }
    .pp-hero h1 {
      margin: 0 0 10px;
      font-size: 28px;
      font-weight: 800;
      color: #fff;
    }
    .pp-hero .subtitle {
      font-size: 15px;
      opacity: 0.95;
      margin: 8px 0 0;
    }
    .pp-hero .updated {
      display: inline-block;
      margin-top: 16px;
      padding: 6px 16px;
      background: rgba(255,255,255,0.2);
      border-radius: 999px;
      font-size: 13px;
      backdrop-filter: blur(4px);
    }
    .pp-card {
      background: #fff;
      border: 1px solid #e8ecf1;
      border-radius: 14px;
      padding: 24px 28px;
      margin-bottom: 18px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.04);
    }
    .pp-card h2 {
      margin: 0 0 14px;
      font-size: 20px;
      color: #2d3e62;
      display: flex;
      align-items: center;
      gap: 10px;
      border-bottom: 2px solid #f0f4ff;
      padding-bottom: 10px;
    }
    .pp-card h2 .icon {
      font-size: 24px;
    }
    .pp-card p {
      margin: 10px 0;
      font-size: 15px;
    }
    .pp-highlight {
      background: linear-gradient(135deg, #a7f3d0 0%, #6ee7b7 100%);
      color: #064e3b;
      padding: 12px 18px;
      border-radius: 10px;
      font-weight: 700;
      margin: 12px 0;
      display: inline-block;
    }
    .pp-no-list {
      background: #fef3f2;
      border-left: 4px solid #f87171;
      padding: 14px 20px;
      border-radius: 8px;
      margin: 14px 0;
    }
    .pp-no-list ul {
      margin: 8px 0;
      padding-left: 22px;
    }
    .pp-no-list li {
      margin: 6px 0;
      color: #7f1d1d;
    }
    .pp-yes-box {
      background: #f0fdf4;
      border-left: 4px solid #22c55e;
      padding: 14px 20px;
      border-radius: 8px;
      margin: 14px 0;
    }
    .pp-yes-box p {
      color: #14532d;
      margin: 0;
      font-weight: 600;
    }
    .pp-compliance {
      display: flex;
      gap: 12px;
      flex-wrap: wrap;
      margin: 16px 0;
    }
    .pp-badge {
      background: linear-gradient(135deg, #3b82f6 0%, #1d4ed8 100%);
      color: #fff;
      padding: 10px 18px;
      border-radius: 999px;
      font-size: 14px;
      font-weight: 700;
      box-shadow: 0 4px 12px rgba(59, 130, 246, 0.3);
    }
    .pp-divider {
      text-align: center;
      margin: 40px 0 30px;
      color: #94a3b8;
      font-size: 14px;
      letter-spacing: 3px;
    }
    .pp-divider::before, .pp-divider::after {
      content: "";
      display: inline-block;
      width: 60px;
      height: 1px;
      background: #cbd5e1;
      vertical-align: middle;
      margin: 0 15px;
    }
    .pp-contact {
      background: linear-gradient(135deg, #fef3c7 0%, #fde68a 100%);
      padding: 24px 28px;
      border-radius: 14px;
      margin-top: 20px;
    }
    .pp-contact h2 {
      color: #78350f;
      border-bottom: 2px solid rgba(146, 64, 14, 0.2);
    }
    .pp-contact p {
      color: #78350f;
      margin: 8px 0;
    }
    .pp-contact a {
      color: #b45309;
      text-decoration: none;
      font-weight: 600;
      border-bottom: 1px dashed #b45309;
    }
    .pp-contact a:hover {
      color: #78350f;
    }
    @media (max-width: 600px) {
      .pp-hero { padding: 30px 20px; }
      .pp-hero h1 { font-size: 22px; }
      .pp-card { padding: 20px; }
      .pp-card h2 { font-size: 18px; }
    }
  </style>

  <div class="pp-wrap">

    <!-- Hero -->
    <div class="pp-hero">
      <div style="font-size: 50px; margin-bottom: 10px;">🕐</div>
      <h1>우리 아이 시계 배우기</h1>
      <p class="subtitle">개인정보처리방침 (Privacy Policy)</p>
      <div class="updated">📅 최종 수정일: 2026년 11월 12일</div>
    </div>

    <!-- 1. 개요 -->
    <div class="pp-card">
      <h2><span class="icon">👋</span> 1. 개요</h2>
      <p>
        "우리 아이 시계 배우기"(이하 "본 앱")는 어린이와 가족이 시간 읽기를 재미있게 학습할 수 있도록 제작된 교육용 애플리케이션입니다.
      </p>
      <div class="pp-highlight">
        ✨ 본 앱은 어떠한 개인정보도 수집·저장·공유하지 않습니다.
      </div>
    </div>

    <!-- 2. 수집 정보 -->
    <div class="pp-card">
      <h2><span class="icon">🚫</span> 2. 수집하는 정보</h2>
      <p>본 앱은 다음을 포함한 <strong>어떠한 사용자 정보도 수집하지 않습니다</strong>:</p>
      <div class="pp-no-list">
        <ul>
          <li>이름, 이메일, 전화번호 등 개인 식별 정보</li>
          <li>위치 정보 (GPS, Wi-Fi, 기지국 등)</li>
          <li>연락처, 사진, 동영상, 파일</li>
          <li>기기 식별자 (광고 ID, 기기 ID 등)</li>
          <li>앱 사용 통계, 크래시 로그, 분석 데이터</li>
          <li>쿠키, 로컬 스토리지 추적 정보</li>
        </ul>
      </div>
    </div>

    <!-- 3. 네트워크 -->
    <div class="pp-card">
      <h2><span class="icon">📡</span> 3. 네트워크 사용</h2>
      <div class="pp-yes-box">
        <p>🔒 본 앱은 인터넷에 전혀 연결되지 않습니다.</p>
      </div>
      <p>
        모든 콘텐츠(시계 그래픽, 학습 음성, 레슨 내용)는 앱 설치 파일에 포함되어 있으며,
        외부 서버와의 통신을 <strong>일절 수행하지 않습니다</strong>.
      </p>
    </div>

    <!-- 4. 제3자 -->
    <div class="pp-card">
      <h2><span class="icon">🛡️</span> 4. 제3자 서비스 및 광고</h2>
      <p>본 앱은:</p>
      <div class="pp-no-list">
        <ul>
          <li><strong>광고를 표시하지 않습니다</strong></li>
          <li><strong>분석 도구(Google Analytics, Firebase 등)를 사용하지 않습니다</strong></li>
          <li><strong>제3자 SDK나 외부 라이브러리를 통한 데이터 수집이 없습니다</strong></li>
          <li><strong>소셜 미디어 플러그인이 없습니다</strong></li>
        </ul>
      </div>
    </div>

    <!-- 5. 어린이 보호 -->
    <div class="pp-card">
      <h2><span class="icon">👶</span> 5. 어린이 개인정보 보호</h2>
      <div class="pp-compliance">
        <span class="pp-badge">🇺🇸 COPPA 준수</span>
        <span class="pp-badge">🇪🇺 GDPR-K 준수</span>
        <span class="pp-badge">👨‍👩‍👧 Play Families Policy</span>
      </div>
      <p>
        본 앱은 어린이를 포함한 모든 연령대를 대상으로 하며,
        <strong>미국 아동 온라인 개인정보 보호법(COPPA)과 유럽 일반 개인정보 보호규정(GDPR-K)을 완전히 준수</strong>합니다.
      </p>
      <div class="pp-yes-box">
        <p>💚 본 앱은 13세 미만 어린이를 포함한 어떤 사용자로부터도 개인정보를 수집하지 않으므로, 데이터가 공유되거나 유출될 위험이 없습니다.</p>
      </div>
    </div>

    <!-- 6. 권한 -->
    <div class="pp-card">
      <h2><span class="icon">🔐</span> 6. 앱 권한</h2>
      <p>본 앱은 다음 권한을 <strong>요청하지 않습니다</strong>:</p>
      <div class="pp-no-list">
        <ul>
          <li>인터넷 접속 권한 (INTERNET)</li>
          <li>위치 권한</li>
          <li>카메라 / 마이크 / 저장소 권한</li>
          <li>연락처 / 캘린더 권한</li>
        </ul>
      </div>
      <p>
        단, 학습 음성 안내를 위해 <strong>안드로이드 운영체제에 내장된 Text-to-Speech(TTS) 엔진</strong>을 사용하며,
        이 과정은 전적으로 기기 내부에서 처리되어 외부로 전송되지 않습니다.
      </p>
    </div>

    <!-- 7. 변경 -->
    <div class="pp-card">
      <h2><span class="icon">📝</span> 7. 개인정보처리방침의 변경</h2>
      <p>
        본 방침이 변경될 경우, 변경 사항을 본 페이지에 게시하며 최종 수정일을 갱신합니다.
        중요한 변경이 있을 경우 앱 업데이트를 통해 알려드립니다.
      </p>
    </div>

    <!-- 8. 문의 (강조 박스) -->
    <div class="pp-card pp-contact">
      <h2><span class="icon">💌</span> 8. 문의</h2>
      <p>본 개인정보처리방침에 대한 문의사항이 있으시면 아래로 연락 주시기 바랍니다:</p>
      <p>
        <strong>📧 이메일</strong>: <a href="mailto:uskim850530@gmail.com">uskim850530@gmail.com</a><br/>
        <strong>👤 개발자</strong>: USKIM<br/>
        <strong>🌐 블로그</strong>: <a href="https://omk-study.blogspot.com/">omk-study.blogspot.com</a>
      </p>
    </div>

    <div class="pp-divider">ENGLISH VERSION</div>

    <!-- English Hero -->
    <div class="pp-hero" style="background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%); box-shadow: 0 10px 30px rgba(245, 87, 108, 0.3);">
      <div style="font-size: 50px; margin-bottom: 10px;">🕐</div>
      <h1>Kids Clock Learning</h1>
      <p class="subtitle">Privacy Policy</p>
      <div class="updated">📅 Last Updated: November 12, 2026</div>
    </div>

    <!-- 1. Overview -->
    <div class="pp-card">
      <h2><span class="icon">👋</span> 1. Overview</h2>
      <p>
        "Kids Clock Learning" ("the App") is an educational application designed to help children and families learn how to tell time in a fun way.
      </p>
      <div class="pp-highlight">
        ✨ The App does not collect, store, or share any personal information.
      </div>
    </div>

    <!-- 2. Data -->
    <div class="pp-card">
      <h2><span class="icon">🚫</span> 2. Information We Collect</h2>
      <p>The App <strong>does not collect any user information</strong>, including:</p>
      <div class="pp-no-list">
        <ul>
          <li>Personally identifiable information (name, email, phone)</li>
          <li>Location data (GPS, Wi-Fi, cell tower)</li>
          <li>Contacts, photos, videos, or files</li>
          <li>Device identifiers (Advertising ID, Device ID)</li>
          <li>App usage statistics, crash logs, or analytics</li>
          <li>Cookies or local storage tracking data</li>
        </ul>
      </div>
    </div>

    <!-- 3. Network -->
    <div class="pp-card">
      <h2><span class="icon">📡</span> 3. Network Usage</h2>
      <div class="pp-yes-box">
        <p>🔒 The App does not connect to the internet at all.</p>
      </div>
      <p>
        All content (clock graphics, learning voice, lesson contents) is bundled within the app installation file,
        and no communication with external servers is performed.
      </p>
    </div>

    <!-- 4. Third-Party -->
    <div class="pp-card">
      <h2><span class="icon">🛡️</span> 4. Third-Party Services and Advertising</h2>
      <p>The App:</p>
      <div class="pp-no-list">
        <ul>
          <li><strong>Does not display advertisements</strong></li>
          <li><strong>Does not use analytics tools (Google Analytics, Firebase, etc.)</strong></li>
          <li><strong>Does not collect data through third-party SDKs</strong></li>
          <li><strong>Does not include social media plugins</strong></li>
        </ul>
      </div>
    </div>

    <!-- 5. Children -->
    <div class="pp-card">
      <h2><span class="icon">👶</span> 5. Children's Privacy</h2>
      <div class="pp-compliance">
        <span class="pp-badge">🇺🇸 COPPA Compliant</span>
        <span class="pp-badge">🇪🇺 GDPR-K Compliant</span>
        <span class="pp-badge">👨‍👩‍👧 Play Families Policy</span>
      </div>
      <p>
        The App is designed for all age groups including children, and fully complies with the
        <strong>Children's Online Privacy Protection Act (COPPA)</strong> and
        <strong>General Data Protection Regulation for Kids (GDPR-K)</strong>.
      </p>
      <div class="pp-yes-box">
        <p>💚 Since no data is collected from any user (including children under 13), there is no risk of sharing or breach.</p>
      </div>
    </div>

    <!-- 6. Permissions -->
    <div class="pp-card">
      <h2><span class="icon">🔐</span> 6. App Permissions</h2>
      <p>The App <strong>does not request</strong>:</p>
      <div class="pp-no-list">
        <ul>
          <li>Internet access (INTERNET)</li>
          <li>Location</li>
          <li>Camera / Microphone / Storage</li>
          <li>Contacts / Calendar</li>
        </ul>
      </div>
      <p>
        For voice-guided learning, the App uses the <strong>built-in Android Text-to-Speech (TTS) engine</strong>,
        which is processed entirely on-device.
      </p>
    </div>

    <!-- 7. Changes -->
    <div class="pp-card">
      <h2><span class="icon">📝</span> 7. Changes to This Privacy Policy</h2>
      <p>
        If this policy changes, we will post updates on this page and update the Last Updated date.
        For significant changes, we will notify users through app updates.
      </p>
    </div>

    <!-- 8. Contact -->
    <div class="pp-card pp-contact">
      <h2><span class="icon">💌</span> 8. Contact</h2>
      <p>If you have any questions about this Privacy Policy, please contact us:</p>
      <p>
        <strong>📧 Email</strong>: <a href="mailto:uskim850530@gmail.com">uskim850530@gmail.com</a><br/>
        <strong>👤 Developer</strong>: USKIM<br/>
        <strong>🌐 Blog</strong>: <a href="https://omk-study.blogspot.com/">omk-study.blogspot.com</a>
      </p>
    </div>

  </div>
