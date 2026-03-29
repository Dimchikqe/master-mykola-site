<!DOCTYPE html>
<html lang="uk">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Майстерня побутової техніки | Хмельницький</title>
<style>
  body { font-family: 'Segoe UI', Tahoma, sans-serif; margin:0; padding:0; background:#f5f5f5; color:#333; }
  header { background:#007ACC; color:white; padding:25px 20px; text-align:center; }
  header h1 { margin:0; font-size:2rem; }
  nav { margin-top:10px; }
  nav a { color:white; text-decoration:none; margin:0 15px; font-weight:bold; }
  nav a:hover { text-decoration:underline; }
  section { padding:60px 20px; max-width:1200px; margin:auto; }
  h2 { color:#007ACC; text-align:center; margin-bottom:40px; }
  .intro { text-align:center; max-width:800px; margin:auto; }
  .intro button { padding:12px 25px; font-size:16px; background:#ff6600; color:white; border:none; border-radius:5px; cursor:pointer; transition:0.3s; }
  .intro button:hover { background:#e55b00; }
  .services { display:flex; flex-wrap:wrap; gap:20px; justify-content:center; }
  .service { background:white; padding:30px 20px; border-radius:10px; flex:1 1 220px; max-width:280px; text-align:center; box-shadow:0 4px 10px rgba(0,0,0,0.1); transition:transform 0.3s; }
  .service:hover { transform: translateY(-8px); }
  .service h3 { margin-top:15px; color:#007ACC; }
  .prices ul { list-style:none; padding:0; max-width:400px; margin:auto; }
  .prices li { background:white; margin-bottom:10px; padding:15px; border-radius:8px; box-shadow:0 2px 5px rgba(0,0,0,0.1); }
  form { display:flex; flex-direction:column; gap:15px; max-width:400px; margin:auto; }
  input, textarea, button { padding:12px; font-size:16px; border-radius:5px; border:1px solid #ccc; width:100%; }
  button { background:#007ACC; color:white; border:none; cursor:pointer; transition:0.3s; }
  button:hover { background:#005fa3; }
  footer { background:#333; color:white; text-align:center; padding:25px; margin-top:50px; }
  @media(max-width:768px){ .services { flex-direction:column; align-items:center; } }
</style>
</head>
<body>

<header>
  <h1>Майстерня побутової техніки</h1>
  <nav>
    <a href="#services">Послуги</a>
    <a href="#prices">Ціни</a>
    <a href="#contact">Контакти</a>
  </nav>
</header>

<section id="intro" class="intro">
  <h2>Ремонт та обслуговування техніки у Хмельницькому та районі</h2>
  <p>Ми ремонтуємо пральні та посудомийні машини, холодильники, кондиціонери з виїздом до клієнта. Швидко, надійно та з гарантією!</p>
  <button onclick="document.getElementById('contact').scrollIntoView({behavior:'smooth'});">Замовити майстра</button>
</section>

<section id="services">
  <h2>Наші послуги</h2>
  <div class="services">
    <div class="service">
      <img src="https://img.icons8.com/ios-filled/64/007ACC/washing-machine.png" alt="Пральні машини">
      <h3>Пральні машини</h3>
      <p>Ремонт будь-яких поломок, заміна насосів, підшипників та електроніки.</p>
    </div>
    <div class="service">
      <img src="https://img.icons8.com/ios-filled/64/007ACC/dishwasher.png" alt="Посудомийні машини">
      <h3>Посудомийні машини</h3>
      <p>Чищення, ремонт двигуна, заміна запчастин та налаштування програм.</p>
    </div>
    <div class="service">
      <img src="https://img.icons8.com/ios-filled/64/007ACC/refrigerator.png" alt="Холодильники">
      <h3>Холодильники</h3>
      <p>Заправка фреоном, ремонт компресора, усунення витоків та шуму.</p>
    </div>
    <div class="service">
      <img src="https://img.icons8.com/ios-filled/64/007ACC/air-conditioner.png" alt="Кондиціонери">
      <h3>Кондиціонери</h3>
      <p>Чищення, діагностика, заправка фреоном та профілактичне обслуговування.</p>
    </div>
  </div>
</section>

<section id="prices" class="prices">
  <h2>Ціни на послуги</h2>
  <ul>
    <li>Ремонт пральної машини – від 500 грн</li>
    <li>Ремонт посудомийної машини – від 600 грн</li>
    <li>Ремонт холодильника – від 800 грн</li>
    <li>Обслуговування кондиціонера – від 400 грн</li>
    <li>Виїзд до клієнта по Хмельницькому та району – безкоштовно</li>
  </ul>
</section>

<section id="contact">
  <h2>Контакти</h2>
  <form>
    <input type="text" placeholder="Ваше ім'я" required>
    <input type="tel" placeholder="Телефон" value="+380633727566" required>
    <textarea placeholder="Ваше повідомлення" required></textarea>
    <button type="submit">Надіслати</button>
  </form>
  <p style="text-align:center; margin-top:20px;">
    Телефон: <strong>063 372 7566</strong><br>
    Адреса: м. Хмельницький та Хмельницький район, виїзд до клієнта
  </p>
</section>

<footer>
  <p>© 2026 Майстерня побутової техніки. Всі права захищені.</p>
</footer>

</body>
</html>
