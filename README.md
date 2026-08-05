[portfolio_updated (1).html](https://github.com/user-attachments/files/30725005/portfolio_updated.1.html)
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>수학과 데이터 분석가 포트폴리오</title>
    <style>
        /* 어두운 배경 및 미니멀 스타일 설정 */
        body {
            background-color: #121212;
            color: #e0e0e0;
            font-family: 'Pretendard', -apple-system, BlinkMacSystemFont, system-ui, Roboto, 'Helvetica Neue', 'Segoe UI', 'Apple SD Gothic Neo', 'Noto Sans KR', 'Malgun Gothic', sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        header {
            padding: 120px 20px 80px;
            text-align: center;
        }
        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 20px;
            border: 3px solid #333;
        }
        h1 {
            font-size: 2.8rem;
            font-weight: 700;
            margin-bottom: 15px;
            color: #ffffff;
            letter-spacing: -1px;
        }
        .subtitle {
            font-size: 1.1rem;
            color: #aaaaaa;
            margin-bottom: 30px;
            font-weight: 300;
        }
        section {
            max-width: 800px;
            margin: 0 auto 80px;
            padding: 0 20px;
        }
        h2 {
            font-size: 1.8rem;
            border-bottom: 1px solid #333;
            padding-bottom: 15px;
            margin-bottom: 40px;
            color: #ffffff;
            font-weight: 600;
        }
        .card {
            background-color: #1a1a1a;
            border: 1px solid #2a2a2a;
            border-radius: 12px;
            padding: 35px;
            margin-bottom: 30px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.5);
            transition: transform 0.3s ease, border-color 0.3s ease;
        }
        .card:hover {
            transform: translateY(-5px);
            border-color: #444;
        }
        .card h3 {
            margin-top: 0;
            color: #ffffff;
            font-size: 1.4rem;
            margin-bottom: 15px;
        }
        .tags {
            display: flex;
            gap: 8px;
            margin-bottom: 25px;
            flex-wrap: wrap;
        }
        .tag {
            background-color: #2a2a2a;
            color: #b0b0b0;
            padding: 6px 14px;
            border-radius: 20px;
            font-size: 0.8rem;
            font-weight: 500;
        }
        ul {
            padding-left: 20px;
            color: #cccccc;
        }
        li {
            margin-bottom: 12px;
        }
        strong {
            color: #eeeeee;
            font-weight: 600;
        }
        footer {
            text-align: center;
            padding: 40px 20px;
            border-top: 1px solid #222;
            color: #666;
            font-size: 0.9rem;
            margin-top: 50px;
        }
    </style>
</head>
<body>

    <header>
        <img src="image_8fcfa5.jpg" alt="프로필 이미지" class="profile-img">
        <h1>데이터로 논리를 증명하는<br>수학과 예비 분석가</h1>
        <p class="subtitle">수식 속에서 길러낸 논리적 사고력과 문제 해결 능력</p>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <div class="card">
            <p><strong>수학과 3학년</strong>에 재학 중이며, 복잡한 증명 과정에서 기른 논리적 전개 방식을 데이터 분석에 접목하고 있습니다.</p>
            <p>숫자 이면에 숨겨진 의미를 찾아내고, 이를 누구나 이해하기 쉽게 시각화하여 타인을 설득하는 과정에 매력을 느낍니다. 꾸준함과 성실함을 바탕으로 조직에 기여하는 데이터 분석가로 성장하고자 합니다.</p>
        </div>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="card">
            <h3>🏀 NBA 데이터 분석 및 시각화 보고서</h3>
            <div class="tags">
                <span class="tag">Data Analysis</span>
                <span class="tag">Data Visualization</span>
                <span class="tag">Report</span>
            </div>
            <ul>
                <li><strong>배경 및 목표:</strong> NBA 선수들의 기록과 팀 승률 간의 상관관계를 파악하여 핵심 승리 요인 도출</li>
                <li><strong>수행 과정:</strong> 데이터 수집 및 결측치 전처리, 통계적 기법을 활용한 탐색적 데이터 분석(EDA) 진행</li>
                <li><strong>주요 결과:</strong> 방대한 스포츠 데이터를 분석하여 유의미한 인사이트를 도출하고, 이를 시각화 보고서로 작성하여 데이터 리터러시 역량 입증</li>
            </ul>
        </div>
    </section>

    <section id="experience">
        <h2>Experience</h2>
        <div class="card">
            <h3>📚 대학교 도서관 근로 장학생</h3>
            <div class="tags">
                <span class="tag">Problem Solving</span>
                <span class="tag">Responsibility</span>
                <span class="tag">Communication</span>
            </div>
            <ul>
                <li><strong>기간:</strong> 2026.03.02 ~ 현재</li>
                <li><strong>주요 업무:</strong> 장서 관리, 대출/반납 시스템 운영 지원 및 교내 이용자 응대</li>
                <li><strong>핵심 역량:</strong> 성실하고 책임감 있는 태도로 이용자 불편을 최소화. 반복되는 업무 속에서도 프로세스를 정확하게 준수하며 꼼꼼한 업무 처리 능력 함양</li>
            </ul>
        </div>
    </section>

    <footer>
        <p>© 2026 Portfolio. All rights reserved.</p>
    </footer>

</body>
</html>
