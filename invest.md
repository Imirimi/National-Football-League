<div id="lock-screen" align="center">
  <h2>🔐 ИНВЕСТИЦИОННЫЙ ПОРТАЛ</h2>
  <p>Введите код доступа для ознакомления с финансовым меморандумом:</p>
  <input type="password" id="passcode" style="padding: 10px; border-radius: 8px; border: 1px solid #ddd;">
  <button onclick="checkPass()" style="padding: 10px 20px; cursor: pointer; background: #0050b3; color: white; border: none; border-radius: 8px;">ОТКРЫТЬ</button>
</div>

<div id="invest-content" style="display:none;">
  <h1 align="center">💰 ИНВЕСТИЦИОННЫЙ МЕМОРАНДУМ</h1>
  <hr>
  <h3>Общий объем инвестиций: 130 000 000 ₽</h3>
  <table border="1" width="100%" style="border-collapse: collapse;">
    <tr bgcolor="#f8f9fa"><th>Направление</th><th>Сумма (₽)</th><th>Ценность</th></tr>
    <tr><td>Smart-Инфраструктура</td><td>58 млн</td><td>Брендирование 11 хабов.</td></tr>
    <tr><td>Технологическое ядро (R&D)</td><td>35 млн</td><td>Владение долей в ПО Cloud Studio.</td></tr>
    <tr><td>Фонд развития талантов</td><td>20 млн</td><td>ESG-повестка и Навигатор.</td></tr>
    <tr><td>Event & Media</td><td>7,9 млн</td><td>Шоу на стадионах.</td></tr>
    <tr><td>Оператор (НКО)</td><td>9,1 млн</td><td>Управление (7%).</td></tr>
  </table>
  <h3>Масштабирование:</h3>
  <p>РФ: Юг, Центр, Поволжье, Урал, Сибирь. БРИКС+: ОАЭ, Саудовская Аравия, Китай, Индия.</p>
  <p><b>Статус Генерального партнера: ВАКАНТНО</b></p>
</div>
<script>
function checkPass() {
  if(document.getElementById("passcode").value == "11") {
    document.getElementById("invest-content").style.display = "block";
    document.getElementById("lock-screen").style.display = "none";
  } else { alert("Неверный код"); }
}
</script>
