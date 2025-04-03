<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Одностраничный сайт</title>
    <link rel="stylesheet" href="styles.css"> <!-- Подключаем файл стилей -->
</head>
<body>

    <nav>
        <ul>
            <li><a href="#home" class="nav-link">Главная</a></li>
            <li><a href="#about" class="nav-link">Обо мне</a></li>
            <li><a href="#skills" class="nav-link">Навыки</a></li>
            <li><a href="#image" class="nav-link">Изображение</a></li>
            <li><a href="#audio" class="nav-link">Аудио</a></li>
            <li><a href="#video" class="nav-link">Видео</a></li>
            <li><a href="#map" class="nav-link">Карта</a></li>
            <li><a href="#animation" class="nav-link">Анимация</a></li>



        </ul>
    </nav>

    <div id="home" class="section active">
        <h2>Добро пожаловать!</h2>
        <p>Это главная страница нашего одностраничного сайта.</p>
    </div>
    
    <div id="about" class="section">
        <h2>Обо мне</h2>
        <p>Здесь вы можете узнать немного о моем профиле.</p>
    </div>
    
    <div id="skills" class="section">
        <h2>Навыки</h2>
        <p>Этот раздел посвящен моим навыкам и умениям.</p>
    </div>
    
    <div id="image" class="section">
        <h2>Изображение</h2>
        <p>Райан Гослинг.</p>
        <img src="image.jpg" alt="Пример изображения" class="site-image">
    </div>

    <div id="audio" class="section">
 <h2>Аудио</h2>
 <audio controls>
 <source src="audio.mp3">
 </audio>
</div>


<div id="video" class="section">
 <h2>Видео</h2>
 <iframe width="560" height="315" src="https://www.youtube.com/embed/dQw4w9WgXcQ?si=jGhv9UiGDh_cyxd-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>


<div id="map" class="section">
 <h2>Карта</h2>
 <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1728.1740704968956!2d76.94945637959164!3d43.24239311467928!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x38836fba0053548d%3A0x4ecb615d1a32dafb!2sinternational%20medical%20school%2Cuniversity%20of%20international%20business!5e0!3m2!1sru!2skz!4v1743676138122!5m2!1sru!2skz" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
</div>

<div id="animation" class="section">
 <h2>Анимация</h2>
 <p class="animate">Ратататата.</p>
</div>

    <script src="script.js"></script> <!-- Подключаем JavaScript -->
</body>
</html>
