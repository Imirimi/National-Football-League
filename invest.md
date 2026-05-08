<div id="lock-screen" align="center">
  <h2>🔐 Доступ к финансовому протоколу</h2>
  <p>Для ознакомления с инвестиционным меморандумом введите код:</p>
  <input type="password" id="passcode" style="padding: 10px; border-radius: 5px; border: 1px solid #ccc;">
  <button onclick="checkPass()" style="padding: 10px 20px; cursor: pointer; background: #0050b3; color: white; border: none; border-radius: 5px;">Войти</button>
</div>

<div id="invest-content" style="display:none;">
  <h1 align="center">💰 ИНВЕСТИЦИОННЫЙ МЕМОРАНДУМ: ЭТАП "ПИЛОТ"</h1>
  <hr>
  
  <h3>1. Финансовые показатели (Крымский кластер)</h3>
  <p><b>Общий объем необходимых инвестиций: 130 000 000 ₽</b></p>
  
  <table border="1" width="100%" style="border-collapse: collapse; text-align: left;">
    <tr bgcolor="#f2f2f2">
      <th style="padding: 10px;">Категория расходов</th>
      <th style="padding: 10px;">Сумма (₽)</th>
      <th style="padding: 10px;">Целевое назначение</th>
    </tr>
    <tr>
      <td style="padding: 10px;"><b>Капитальные затраты (CAPEX)</b></td>
      <td style="padding: 10px;">58 000 000</td>
      <td>Реновация и строительство 11 Smart-площадок, оснащение серверным оборудованием и 4К-оптикой.</td>
    </tr>
    <tr>
      <td style="padding: 10px;"><b>R&D и Технологическое ядро</b></td>
      <td style="padding: 10px;">35 000 000</td>
      <td>Разработка Cloud Studio, ИИ-алгоритмов скаутинга, авторский надзор и медиа-производство контента.</td>
    </tr>
    <tr>
      <td style="padding: 10px;"><b>Фонд мотивации и грантов</b></td>
      <td style="padding: 10px;">20 000 000</td>
      <td>Призовые выплаты, международная экспертиза Совета Мудрецов, интеграция с системой «Навигатор».</td>
    </tr>
    <tr>
      <td style="padding: 10px;"><b>Event-маркетинг</b></td>
      <td style="padding: 10px;">7 900 000</td>
      <td>Аренда профессиональных арен для межгородских этапов и организация Гранд-Финала (стадион «Авангард»).</td>
    </tr>
    <tr>
      <td style="padding: 10px;"><b>Операционное управление</b></td>
      <td style="padding: 10px;">9 100 000</td>
      <td>Администрирование проекта через НКО-оператора (7%), юридическое и налоговое сопровождение.</td>
    </tr>
  </table>

  <h3>2. Стратегия капитализации (Exit Strategy)</h3>
  <p>Инвестор получает приоритетное право на использование бренда в маркетинговых кампаниях и долю в доходах от масштабирования технологии.</p>
  
  <h4>Этапы расширения (Масштабирование в РФ):</h4>
  <ul>
    <li><b>Южный кластер:</b> Краснодарский край (Сочи, Краснодар, Новороссийск), Ростовская область, Ставрополье.</li>
    <li><b>Центральный кластер:</b> Москва и МО, Воронежская, Тульская, Ярославская области.</li>
    <li><b>Приволжский кластер:</b> Татарстан (Казань), Башкортостан, Самарская и Нижегородская области.</li>
    <li><b>Уральский и Сибирский кластеры:</b> Екатеринбург, Новосибирск, Красноярск, Тюмень.</li>
    <li><b>Северо-Запад:</b> Санкт-Петербург и Ленинградская область, Калининград.</li>
  </ul>

  <h4>Международная экспансия (БРИКС+):</h4>
  <p>Продажа мастер-франшизы на технологию Cloud Studio в страны-партнеры (ОАЭ, Саудовская Аравия, Бразилия, Китай, Индия). Оценочная стоимость франшизы для одного региона БРИКС+ — от $1,5 млн.</p>
</div>

<script>
function checkPass() {
  var p = document.getElementById("passcode").value;
  if(p == "11") {
    document.getElementById("invest-content").style.display = "block";
    document.getElementById("lock-screen").style.display = "none";
  } else {
    alert("Доступ отклонен: неверный код");
  }
}
</script>
