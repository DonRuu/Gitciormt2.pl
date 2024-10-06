<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="popup-logo@2x.png" alt="Logo Serwera">
        </div>
        <nav>
            <ul>
                <li><a href="#home">Strona Główna</a></li>
                <li><a href="#about">O Serwerze</a></li>
                <li><a href="#forum">Forum</a></li>
                <li><a href="#rules">Zasady</a></li>
                <li><a href="#contact">Kontakt</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="home" class="banner">
            <img src="banner.jpg" alt="Banner Serwera">
            <h1>Witaj na naszym serwerze Metin2!</h1>
            <p>Dołącz do niesamowitych przygód!</p>
            <a href="#register" class="btn">Dołącz do nas!</a>
        </section>

        <section id="about">
            <h2>O Serwerze</h2>
            <p>Nasza przygoda z Metin2 zaczyna się tutaj! Przyjazna społeczność, unikalne eventy i regularne aktualizacje.</p>
        </section>

        <section id="features">
            <h2>Zalety Serwera</h2>
            <ul>
                <li>Stabilny i szybki serwer</li>
                <li>Regularne eventy i nagrody</li>
                <li>Przyjazna atmosfera</li>
            </ul>
        </section>

        <section id="news">
            <h2>Aktualności</h2>
            <p>Śledź nasze najnowsze wydarzenia i aktualizacje!</p>
        </section>

        <section id="contact">
            <h2>Kontakt</h2>
            <form action="submit.php" method="post">
                <input type="text" name="name" placeholder="Twoje imię" required>
                <input type="email" name="email" placeholder="Twój e-mail" required>
                <textarea name="message" placeholder="Twoja wiadomość" required></textarea>
                <button type="submit">Wyślij</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Serwer Metin2 - Wszystkie prawa zastrzeżone</p>
        <div class="socials">
            <a href="#">Facebook</a>
            <a href="#">Twitter</a>
        </div>
    </footer>
</body>
</html>
