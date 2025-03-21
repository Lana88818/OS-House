<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Горный дом в Архызе</title>
  <link href="https://fonts.googleapis.com/css2?family=Rubik:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Rubik', sans-serif;
      margin: 0;
      background: #fffaf5;
      color: #333;
    }
    header {
      background: url('https://images.unsplash.com/photo-1614691917991-5d18f4b6e7b2') center/cover no-repeat;
      height: 90vh;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-align: center;
    }
    header h1 {
      font-size: 2.5rem;
      background: rgba(0, 0, 0, 0.5);
      padding: 1rem;
      border-radius: 12px;
    }
    .btn {
      display: inline-block;
      margin-top: 1rem;
      padding: 0.8rem 1.6rem;
      background: #f4a261;
      color: white;
      text-decoration: none;
      border-radius: 8px;
      font-weight: bold;
    }
    section {
      padding: 2rem 1rem;
      max-width: 1000px;
      margin: 0 auto;
    }
    .features ul {
      list-style: none;
      padding: 0;
    }
    .features li {
      background: #ffe8d6;
      margin: 0.5rem 0;
      padding: 0.8rem;
      border-radius: 6px;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
    }
    .gallery img {
      width: 100%;
      border-radius: 8px;
    }
    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 1.5rem 1rem;
    }
    @media (max-width: 600px) {
      header h1 {
        font-size: 1.5rem;
        padding: 0.5rem;
      }
      .btn {
        padding: 0.6rem 1.2rem;
        font-size: 0.9rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <div>
      <h1>Горный дом в Архызе</h1>
      <a href="#contact" class="btn">Забронировать</a>
    </div>
  </header>

  <section>
    <h2>О доме</h2>
    <p>Гостевой дом расположен в окружении вековых сосен Архыза. Внутри — 2 спальни, гостиная, кухня с техникой, ванная комната, Wi-Fi и ТВ. Просторная терраса с видом на горы, зона для мангала и костра, собственная парковка.</p>
  </section>

  <section class="features">
    <h2>Преимущества</h2>
    <ul>
      <li>2 спальни и гостиная — до 6 гостей</li>
      <li>Полностью оборудованная кухня</li>
      <li>Терраса с видом на сосны</li>
      <li>Wi-Fi, телевизор, фен</li>
      <li>Мангал и костровая зона</li>
      <li>Собственная парковка</li>
      <li>5 км до горнолыжного курорта «Архыз»</li>
    </ul>
  </section>

  <section>
    <h2>Галерея</h2>
    <div class="gallery">
      <img src="https://images.unsplash.com/photo-1588196749597-9ff075ee6b5b" alt="Интерьер спальни">
      <img src="https://images.unsplash.com/photo-1570129477492-45c003edd2be" alt="Кухня и гостиная">
      <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb" alt="Вид с террасы">
      <img src="https://images.unsplash.com/photo-1501612780327-45045538702b" alt="Мангал и костёр">
    </div>
  </section>

  <section>
    <h2>Отзывы гостей</h2>
    <p><em>«Дом — как на фото, очень уютно! Терраса — топ. Обязательно вернёмся!»</em> — Дарья, Москва</p>
    <p><em>«Всё чисто, тихо, красиво. До трасс 5 минут. Идеальный отдых!»</em> — Артём и Оля</p>
  </section>

  <section id="contact">
    <h2>Контакты и бронь</h2>
    <p>📞 <a href="tel:+79998887766">Позвонить: +7 (999) 888-77-66</a><br>
    💬 <a href="https://wa.me/79998887766">Написать в WhatsApp</a><br>
    ✈️ <a href="https://t.me/arkhyz_dom">Telegram: @arkhyz_dom</a></p>
    <a href="https://wa.me/79998887766" class="btn">Забронировать сейчас</a>
  </section>

  <section>
    <h2>Как добраться</h2>
    <p>Дом находится в 5 км от горнолыжного курорта «Архыз», в 213 км от аэропорта Минеральные Воды и 179 км от вокзала Кисловодска.</p>
    <iframe src="https://yandex.ru/map-widget/v1/?ll=41.280237%2C43.453647&z=10" width="100%" height="300" frameborder="0"></iframe>
  </section>

  <footer>
    <p>&copy; 2025 Горный дом в Архызе. Все права защищены.</p>
  </footer>
</body>
</html>
