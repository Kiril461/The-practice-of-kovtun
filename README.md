# The-practice-of-kovtun
<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Сайт-візитівка бібліотеки">
    <title>Бібліотека - Головна</title>
    <link rel="stylesheet" href="styles/style.css">
</head>
<body>
    <header>
        <nav class="navbar">
            <img src="images/logo.png" alt="Логотип бібліотеки" class="logo">
            <ul class="menu">
                <li><a href="#about">Про нас</a></li>
                <li><a href="#catalog">Каталог</a></li>
                <li><a href="#news">Новини</a></li>
                <li><a href="#contacts">Контакти</a></li>
            </ul>
            <div class="hamburger-menu" onclick="toggleMenu()">☰</div>
        </nav>
    </header>

    <main>
        <section id="hero">
            <h1>Ласкаво просимо до нашої бібліотеки!</h1>
            <p>Відкрийте світ знань разом з нами.</p>
            <a href="#about" class="cta-button">Дізнатися більше</a>
        </section>

        <section id="about">
            <h2>Про нас</h2>
            <p>Наша бібліотека — це місце для натхнення, навчання та відпочинку. Ми пишаємося багатою історією та широким вибором літератури для читачів різного віку.</p>
        </section>

        <section id="catalog">
            <h2>Каталог</h2>
            <input type="text" placeholder="Пошук книг за автором, назвою чи жанром" class="search-bar">
            <div class="carousel">
                <img src="images/book-carousel-1.jpg" alt="Книга 1">
                <img src="images/book-carousel-2.jpg" alt="Книга 2">
                <img src="images/book-carousel-3.jpg" alt="Книга 3">
            </div>
        </section>

        <section id="news">
            <h2>Новини</h2>
            <ul class="news-list">
                <li>📅 <strong>10 січня 2025:</strong> Нова колекція сучасної української літератури.</li>
                <li>📅 <strong>15 лютого 2025:</strong> Майстер-клас із креативного письма.</li>
            </ul>
        </section>

        <section id="contacts">
            <h2>Контакти</h2>
            <p>📍 Адреса: вул. Шевченка, 12, Київ<br>📞 Телефон: +380 44 123 45 67<br>📧 Email: info@library.com</p>
            <form action="#" method="POST" class="contact-form">
                <input type="text" name="name" placeholder="Ваше ім'я" required>
                <input type="email" name="email" placeholder="Ваш email" required>
                <textarea name="message" placeholder="Ваше повідомлення" required></textarea>
                <button type="submit">Надіслати</button>
            </form>
        </section>
    </main>

    <footer>
        <p>© 2025 Бібліотека. Всі права захищені.</p>
    </footer>

    <script src="scripts/script.js"></script>
</body>
</html>
