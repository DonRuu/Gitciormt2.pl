<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Oficjalna strona serwera Metin2">
    <title>Serwer Metin2 - [Twoja nazwa serwera]</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Nagłówek -->
    <header>
        <div class="logo">
            <h1>[Twoja nazwa serwera]</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#home">Strona Główna</a></li>
                <li><a href="#about">O Serwerze</a></li>
                <li><a href="#download">Pobierz</a></li>
                <li><a href="#ranking">Ranking</a></li>
                <li><a href="#register">Rejestracja</a></li>
                <li><a href="#contact">Kontakt</a></li>
            </ul>
        </nav>
    </header>

    <!-- Strona główna -->
    <section id="home">
        <h2>Witaj na serwerze [Twoja nazwa serwera]</h2>
        <p>Dołącz do nas i przeżyj niesamowite przygody w świecie Metin2!</p>
        <a href="#download" class="button">Pobierz grę</a>
    </section>

    <!-- O serwerze -->
    <section id="about">
        <h2>O serwerze</h2>
        <p>[Tutaj umieść opis serwera, jego cechy, unikalne systemy, stawki expa, dropów, eventy itp.]</p>
    </section>

    <!-- Pobierz klienta -->
    <section id="download">
        <h2>Pobierz grę</h2>
        <p>Kliknij poniżej, aby pobrać klienta gry i zacząć swoją przygodę!</p>
        <a href="[link do klienta]" class="button">Pobierz klienta gry</a>
    </section>

    <!-- Ranking graczy -->
    <section id="ranking">
        <h2>Ranking Graczy</h2>
        <table>
            <thead>
                <tr>
                    <th>Miejsce</th>
                    <th>Nazwa Gracza</th>
                    <th>Poziom</th>
                    <th>Punkty</th>
                </tr>
            </thead>
            <tbody>
                <!-- Tutaj wstaw dane graczy -->
                <tr>
                    <td>1</td>
                    <td>Gracz1</td>
                    <td>99</td>
                    <td>5000</td>
                </tr>
                <tr>
                    <td>2</td>
                    <td>Gracz2</td>
                    <td>98</td>
                    <td>4800</td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- Rejestracja -->
    <section id="register">
        <h2>Rejestracja</h2>
        <form action="[url do skryptu rejestracji]" method="post">
            <label for="username">Nazwa użytkownika:</label>
            <input type="text" id="username" name="username" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="password">Hasło:</label>
            <input type="password" id="password" name="password" required>
            
            <input type="submit" value="Zarejestruj się">
        </form>
    </section>

    <!-- Kontakt -->
    <section id="contact">
        <h2>Kontakt</h2>
        <p>Masz pytania? Napisz do nas:</p>
        <form action="[url do skryptu kontaktowego]" method="post">
            <label for="name">Imię:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="message">Wiadomość:</label>
            <textarea id="message" name="message" required></textarea>
            
            <input type="submit" value="Wyślij">
        </form>
    </section>

    <!-- Stopka -->
    <footer>
        <p>&copy; 2024 [Twoja nazwa serwera]. Wszelkie prawa zastrzeżone.</p>
    </footer>
</body>
</html>
