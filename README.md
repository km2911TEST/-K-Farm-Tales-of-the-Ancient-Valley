<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>K-Farm: Tales of the Ancient Valley — Официальный сайт</title>
    <style>
        :root {
            --bg-color: #12161f;
            --card-bg: #1c2230;
            --accent-gold: #f1c40f;
            --accent-green: #2ecc71;
            --accent-blue: #3498db;
            --text-color: #ecf0f1;
            --text-muted: #bdc3c7;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-color);
            line-height: 1.6;
        }

        header {
            background: linear-gradient(180deg, rgba(0,0,0,0.8) 0%, rgba(18,22,31,1) 100%);
            padding: 20px 0;
            border-bottom: 2px solid var(--accent-gold);
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 0 20px;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 1.8rem;
            font-weight: bold;
            color: var(--accent-gold);
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .nav-links {
            display: flex;
            gap: 20px;
            list-style: none;
        }

        .nav-links a {
            color: var(--text-color);
            text-decoration: none;
            font-weight: 600;
            transition: color 0.3s;
        }

        .nav-links a:hover {
            color: var(--accent-gold);
        }

        /* Hero Section */
        .hero {
            text-align: center;
            padding: 80px 20px;
            background: radial-gradient(circle, rgba(46,204,113,0.15) 0%, rgba(18,22,31,1) 70%);
        }

        .hero h1 {
            font-size: 3.2rem;
            color: var(--accent-gold);
            margin-bottom: 10px;
            text-shadow: 0 0 15px rgba(241, 196, 15, 0.3);
        }

        .hero p {
            font-size: 1.3rem;
            color: var(--text-muted);
            max-width: 700px;
            margin: 0 auto 30px;
        }

        .btn-group {
            display: flex;
            justify-content: center;
            gap: 15px;
            flex-wrap: wrap;
        }

        .btn {
            display: inline-block;
            padding: 12px 30px;
            border-radius: 6px;
            font-weight: bold;
            text-decoration: none;
            font-size: 1.1rem;
            transition: transform 0.2s, box-shadow 0.2s;
        }

        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.4);
        }

        .btn-primary {
            background-color: var(--accent-green);
            color: #fff;
        }

        .btn-telegram {
            background-color: var(--accent-blue);
            color: #fff;
        }

        /* Features Section */
        .features {
            padding: 60px 0;
        }

        .section-title {
            text-align: center;
            font-size: 2.2rem;
            color: var(--accent-gold);
            margin-bottom: 40px;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
        }

        .card {
            background-color: var(--card-bg);
            padding: 25px;
            border-radius: 10px;
            border: 1px solid rgba(255, 255, 255, 0.05);
            box-shadow: 0 4px 10px rgba(0,0,0,0.3);
        }

        .card-icon {
            font-size: 2.5rem;
            margin-bottom: 15px;
        }

        .card h3 {
            font-size: 1.4rem;
            margin-bottom: 10px;
            color: var(--accent-gold);
        }

        .card p {
            color: var(--text-muted);
            font-size: 0.95rem;
        }

        /* Specs Section */
        .specs {
            background-color: var(--card-bg);
            padding: 50px 0;
            border-top: 1px solid rgba(255,255,255,0.05);
            border-bottom: 1px solid rgba(255,255,255,0.05);
        }

        .specs-list {
            list-style: none;
            max-width: 600px;
            margin: 0 auto;
        }

        .specs-list li {
            padding: 10px 0;
            border-bottom: 1px solid rgba(255,255,255,0.1);
            display: flex;
            justify-content: space-between;
        }

        .specs-list li:last-child {
            border-bottom: none;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 30px 0;
            color: var(--text-muted);
            font-size: 0.9rem;
        }

        footer a {
            color: var(--accent-gold);
            text-decoration: none;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <div class="container nav">
            <a href="#" class="logo">🌾 K-FARM</a>
            <ul class="nav-links">
                <li><a href="#about">Об игре</a></li>
                <li><a href="#features">Особенности</a></li>
                <li><a href="#specs">Требования</a></li>
                <li><a href="https://t.me/KiraKris02" target="_blank">Telegram</a></li>
            </ul>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="about">
        <div class="container">
            <h1>K-Farm: Tales of the Ancient Valley</h1>
            <p>Официальная версия уютного хардкорного 2D-симулятора фермы. Восстанови заброшенный хутор, приручи верных питомцев и разгадай секрет Древнего Кристалла!</p>
            <div class="btn-group">
                <a href="https://t.me/KiraKris02" class="btn btn-primary" target="_blank">🎮 Скачать / Играть</a>
                <a href="https://t.me/KiraKris02" class="btn btn-telegram" target="_blank">💬 Telegram Канал</a>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section class="features" id="features">
        <div class="container">
            <h2 class="section-title">Особенности Игры</h2>
            <div class="grid">
                <div class="card">
                    <div class="card-icon">🏬</div>
                    <h3>Торговля и Прилавок</h3>
                    <p>Собирай урожай, выкладывай его на собственный прилавок и продавай проходящим НПС-покупателям за K coins!</p>
                </div>
                <div class="card">
                    <div class="card-icon">🌤️</div>
                    <h3>Смена Дня, Ночи и Погоды</h3>
                    <p>Динамическая погода влияет на геймплей: в дождь не тратится энергия, в туман вырастают цены, а в ясную погоду сбор быстрее!</p>
                </div>
                <div class="card">
                    <div class="card-icon">🏆</div>
                    <h3>Доска Заданий и Золотой Урожай</h3>
                    <p>Выполняй более 100 обновляющихся квестов и получай Золотую Морковь и Золотые Яблоки для покупки уникальных улучшений!</p>
                </div>
                <div class="card">
                    <div class="card-icon">⚡</div>
                    <h3>Выживание и Энергия</h3>
                    <p>Следи за шкалой усталости. Восстанавливай силы сном в собственном доме и расширяй угодья с помощью Мотыги и Косы!</p>
                </div>
            </div>
        </div>
    </section>

    <!-- System Specs -->
    <section class="specs" id="specs">
        <div class="container">
            <h2 class="section-title">Системные требования</h2>
            <ul class="specs-list">
                <li><span>Операционная система:</span> <span>Windows 8 / 10 / 11</span></li>
                <li><span>Платформа:</span> <span>.NET Framework (C# Windows Forms)</span></li>
                <li><span>Оперативная память (RAM):</span> <span>512 МБ</span></li>
                <li><span>Место на диске:</span> <span>~10 МБ</span></li>
                <li><span>Управление:</span> <span>Клавиатура (WASD / Стрелки + E / Space)</span></li>
            </ul>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>© 2026 K-Games Studio. Все права защищены.</p>
            <p>Официальное сообщество: <a href="https://t.me/KiraKris02" target="_blank">t.me/KiraKris02</a></p>
        </div>
    </footer>

</body>
</html>
