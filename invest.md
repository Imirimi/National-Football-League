<div id="lock-screen" align="center">
  <h2>🔐 Доступ ограничен</h2>
  <p>Для просмотра инвестиционного пакета введите код доступа:</p>
  <input type="password" id="passcode" style="padding: 10px; border-radius: 5px; border: 1px solid #ccc;">
  <button onclick="checkPass()" style="padding: 10px 20px; cursor: pointer;">Войти</button>
</div>

<div id="invest-content" style="display:none;">
  <h1 align="center">💰 ИНВЕСТИЦИОННЫЙ ПАКЕТ: ЭТАП "КРЫМ"</h1>
  <hr>
  <p><b>Целевой объем финансирования: 130 000 000 ₽</b></p>
  
  <table border="1" width="100%">
    <tr bgcolor="#f2f2f2">
      <th>Направление</th>
      <th>Бюджет</th>
      <th>Результат</th>
    </tr>
    <tr>
      <td><b>Smart-Инфраструктура</b></td>
      <td>58 млн ₽</td>
      <td>11 брендированных площадок ВТБ с 4К-стримингом.</td>
    </tr>
    <tr>
      <td><b>Креатив и Авторское право</b></td>
      <td>35 млн ₽</td>
      <td>Продюсирование, Cloud Studio, гонорар автора проекта.</td>
    </tr>
    <tr>
      <td><b>Призовой фонд и Навигатор</b></td>
      <td>20 млн ₽</td>
      <td>Выплаты талантам, гранты, мотивация Мудрецов.</td>
    </tr>
    <tr>
      <td><b>События и Стадионы</b></td>
      <td>7,9 млн ₽</td>
      <td>Аренда арен и финал на «Авангарде».</td>
    </tr>
    <tr>
      <td><b>Оператор (НКО)</b></td>
      <td>9,1 млн ₽</td>
      <td>Управление, налоги, юридический блок (7%).</td>
    </tr>
  </table>
  <br>
  <h3>📈 Модель БРИКС+</h3>
  <p>Капитализация проекта строится на продаже технологической франшизы в другие регионы и страны. Ожидаемая стоимость лицензии для одной страны БРИКС+ — от $500k.</p>
</div>

<script>
function checkPass() {
  var p = document.getElementById("passcode").value;
  if(p == "11") {
    document.getElementById("invest-content").style.display = "block";
    document.getElementById("lock-screen").style.display = "none";
  } else {
    alert("Неверный код доступа");
  }
}
</script>
