<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>어린이 성당</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Gamja+Flower&display=swap" rel="stylesheet">
</head>
<body>
    <header>
        <div class="container">
            <h1>어린이 성당</h1>
            <nav>
              <ul>
                <li><a href="#home">홈</a></li>
                <li><a href="#bible-stories">성경 이야기</a></li>
                <li><a href="#prayers">기도</a></li>
                <li><a href="활동사진.html" target="_blank">활동사진</a></li>
            </ul>
            </nav>
        </div>
    </header>

    <main>
        <section id="home" class="section">
            <div class="container">
                <h2>홈</h2>
                <h1>여기는 어린이들을 위한 성당 공간이에요!</h1>
                <img src="예수님과 아이들.PNG" alt="성당 이미지">
            </div>
        </section>

        <section id="bible-stories" class="section">
            <div class="container">
                <h2>성경 이야기</h2>
                <div class="story-grid">
                    <div class="story">
                        <h3>노아의 방주</h3>
                        <h3>하느님은 노아에게 큰 방주를 만들라고 명령하셨어요...</h3>
                        <button onclick="showStory('noah')">자세히 보기</button>
                    </div>
                    <div class="story">
                        <h3>다윗과 골리앗</h3>
                        <h3>작은 소년 다윗은 거대한 골리앗을 믿음으로 이겼어요...</h3>
                        <button onclick="showStory('david')">자세히 보기</button>
                    </div>
                    <div class="story">
                        <h3>요셉의 꿈</h3>
                        <h3>요셉은 꿈을 통해 하느님의 계획을 알게 되었어요...</h3>
                        <button onclick="showStory('joseph')">자세히 보기</button>
                    </div>
                    <div class="story">
                        <h3>모세와 홍해</h3>
                        <h3>모세는 하느님의 능력으로 홍해를 갈랐어요...</h3>
                        <button onclick="showStory('moses')">자세히 보기</button>
                    </div>
                </div>
            </div>
        </section>

        <section id="prayers" class="section">
            <div class="container">
                <h2>기도</h2>
                <h2>매일매일 기도를 통해 하느님과 가까워지세요.</h2>
                <ul>
                    <li><h2><strong> 하느님 오늘 하루도 감사드려요!</li></h2></strong>   
                </ul>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2024 어린이 성당 | 모든 권리 보유.</p>
            <p>문의: <a href="mailto:kidschurch@example.com">kidschurch@example.com</a></p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>