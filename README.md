<!DOCTYPE html>
<html lang="kk">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Era_stroi</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 20px; line-height: 1.6; }
    header, section, footer { margin-bottom: 30px; }
    h1, h2 { color: #2c3e50; }
    nav a { margin-right: 10px; cursor: pointer; text-decoration: underline; }
    .lang-btn { float: right; margin-left: 10px; cursor: pointer; }
    .hidden { display: none; }
    .section { margin-bottom: 40px; }
    .contact { background-color: #f0f0f0; padding: 15px; border-radius: 8px; }
  </style>
</head>
<body>

  <div>
    <span class="lang-btn" onclick="switchLang('ru')">Русский</span>
    <span class="lang-btn" onclick="switchLang('kk')">Қазақша</span>
  </div>

  <!-- Қазақша бөлімдер -->
  <div id="kk-content">
    <header>
      <h1>Era_stroi</h1>
      <p>Сапалы құрылыс – сенімді серіктестік!</p>
    </header>

    <section class="section">
      <h2>Қызметтер</h2>
      <ul>
        <li>Үйге сызба сызу</li>
        <li>Жобалау</li>
        <li>Құрылыс бюджеті мен уақытының есебі</li>
        <li>Құрылыс жоспарын жасау</li>
      </ul>
      <p>Салынатын нысандар: үй, гараж, сұлулық салоны, SPA, дүкен, 3 жұлдызды қонақ үй.</p>
    </section>

    <section class="section">
      <h2>Біз туралы</h2>
      <p>"Era_stroi" – құрылыс пен жобалау саласында кәсіби қызмет көрсететін сенімді компания.</p>
    </section>

    <section class="section">
      <h2>Жобалар</h2>
      <p>Біз әртүрлі тұрғын үй және коммерциялық нысандарды салып, тапсырыс берушілеріміздің сеніміне ие болдық.</p>
    </section>

    <section class="section">
      <h2>Есептер</h2>
      <p>Есептеріміз сурет және жазбаша сипаттама түрінде ұсынылады.</p>
    </section>

    <footer class="contact">
      <h2>Байланыс</h2>
      <p>Телефон: +7 708 813 7753</p>
    </footer>
  </div>

  <!-- Русский разделы -->
  <div id="ru-content" class="hidden">
    <header>
      <h1>Era_stroi</h1>
      <p>Качественное строительство – надёжное партнёрство!</p>
    </header>

    <section class="section">
      <h2>Услуги</h2>
      <ul>
        <li>Чертежи для дома</li>
        <li>Проектирование</li>
        <li>Расчёт бюджета и сроков строительства</li>
        <li>Составление строительного плана</li>
      </ul>
      <p>Мы строим: дома, гаражи, салоны красоты, SPA, магазины, 3-звёздочные отели.</p>
    </section>

    <section class="section">
      <h2>О нас</h2>
      <p>"Era_stroi" – надёжная компания, профессионально оказывающая услуги в сфере проектирования и строительства.</p>
    </section>

    <section class="section">
      <h2>Проекты</h2>
      <p>Мы успешно реализовали множество жилых и коммерческих объектов, заслужив доверие клиентов.</p>
    </section>

    <section class="section">
      <h2>Отчёты</h2>
      <p>Отчёты предоставляются в виде изображений и текстовых описаний.</p>
    </section>

    <footer class="contact">
      <h2>Контакты</h2>
      <p>Телефон: +7 708 813 7753</p>
    </footer>
  </div>

  <script>
    function switchLang(lang) {
      document.getElementById('kk-content').classList.toggle('hidden', lang !== 'kk');
      document.getElementById('ru-content').classList.toggle('hidden', lang !== 'ru');
    }
  </script>

</body>
</html># Era_stroii
