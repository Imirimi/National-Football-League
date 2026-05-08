<div id="lock-screen" align="center" style="padding: 50px; font-family: sans-serif;">
  <img src="https://imirimi.github.io/National-Football-League/1str.jpg" width="200" style="border-radius: 50%; margin-bottom: 20px;">
  <h2>🔐 Доступ к финансовым данным ограничен</h2>
  <p>Для просмотра инвестиционного пакета и сметы проекта введите код доступа:</p>
  <input type="password" id="passcode" placeholder="Введите код" style="padding: 12px; border-radius: 8px; border: 1px solid #ddd; width: 200px; font-size: 16px;">
  <br><br>
  <button onclick="checkPass()" style="padding: 12px 30px; background-color: #005eb8; color: white; border: none; border-radius: 8px; cursor: pointer; font-weight: bold;">Подтвердить</button>
  <p id="error-msg" style="color: red; display: none; margin-top: 15px;">Неверный код доступа. Попробуйте еще раз.</p>
</div>

<div id="invest-content" style="display:none; font-family: sans-serif; line-height: 1.6;">
  <h1 align="center">💰 ИНВЕСТИЦИОННЫЙ ПАКЕТ: ЭТАП "КРЫМ"</h1>
  <p align="center"><b>Статус: Пилотный регион (11 городов)</b></p>
  <hr>

  <h3>📊 Финансовое обоснование проекта</h3>
  <p>Общий объем необходимых инвестиций для запуска первой фазы проекта в Республике Крым составляет <b>130 000 000 рублей</b>. Данная сумма покрывает создание физической инфраструктуры, разработку ПО и проведение первого сезона медиа-лиги.</p>

  <table border="1" width="100%" style="border-collapse: collapse; margin-bottom: 20px;">
    <thead>
      <tr bgcolor="#f8f9fa">
        <th style="padding: 12px;">Направление</th>
        <th style="padding: 12px;">Сумма (₽)</th>
        <th style="padding: 12px;">Целевое назначение</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="padding: 10px;"><b>Smart-Инфраструктура</b></td>
        <td style="padding: 10px;">58 000 000</td>
        <td>Реновация 11 площадок в городах Крыма, установка 4К-камер, освещения и брендирование (ВТБ).</td>
      </tr>
      <tr>
        <td style="padding: 10px;"><b>Креатив и Авторское право</b></td>
        <td style="padding: 10px;">35 000 000</td>
        <td>Продюсирование медиа-контента, разработка Cloud Studio, вознаграждение за технологию и авторский надзор.</td>
      </tr>
      <tr>
        <td style="padding: 10px;"><b>Призовой фонд и Гранты</b></td>
        <td style="padding: 10px;">20 000 000</td>
        <td>Выплаты игрокам, поддержка детских команд через сертификаты "Навигатор", гонорары Мудрецам.</td>
      </tr>
      <tr>
        <td style="padding: 10px;"><b>События и Аренда</b></td>
        <td style="padding: 10px;">7 900 000</td>
        <td>Аренда профессиональных стадионов для межгородских матчей и организация финала в Ялте.</td>
      </tr>
      <tr>
        <td style="padding: 10px;"><b>Операторский фонд</b></td>
        <td style="padding: 10px;">9 100 000</td>
        <td>Административное сопровождение через НКО (7%), юридическая поддержка, налоги.</td>
      </tr>
    </tbody>
  </table>

  <h3>📈 Стратегия капитализации (Exit Strategy)</h3>
  <p>Инвестор получает эксклюзивные права на использование бренда "Народный футбол" в рамках банковских продуктов. Основной доход после запуска пилота строится на:</p>
  <ul>
    <li><b>Продажа франшизы:</b> Масштабирование в регионы РФ (Краснодарский край, Ростовская обл. и др.).</li>
    <li><b>Международные лицензии:</b> Продажа прав на трансляции и использование Cloud Studio в странах БРИКС+.</li>
    <li><b>Медиа-права:</b> Рекламные контракты внутри собственной стриминговой платформы.</li>
  </ul>

  <div align="center" style="margin-top: 30px;">
    <p><a href="https://imirimi.github.io/National-Football-League/" style="color: #005eb8; text-decoration: none; font-weight: bold;">🏠 Вернуться на главную</a></p>
  </div>
</div>

<script>
function checkPass() {
  var p = document.getElementById("passcode").value;
  var content = document.getElementById("invest-content");
  var lock = document.getElementById("lock-screen");
  var error = document.getElementById("error-msg");
  
  if(p === "11") {
    content.style.display = "block";
    lock.style.display = "none";
  } else {
    error.style.display = "block";
    document.getElementById("passcode").value = "";
  }
}

// Позволяет нажимать Enter для ввода
document.getElementById("passcode").addEventListener("keyup", function(event) {
  if (event.keyCode === 13) {
    checkPass();
  }
});
</script>
