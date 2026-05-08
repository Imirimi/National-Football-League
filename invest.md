<div id="lock-screen" align="center">
  <img src="https://imirimi.github.io/National-Football-League/1str.jpg" width="180" style="border-radius: 50%; margin-bottom: 20px;">
  <h2>🔐 ИНВЕСТИЦИОННЫЙ ПОРТАЛ</h2>
  <p>Доступ ограничен. Введите код доступа для ознакомления с финансовым меморандумом:</p>
  <div style="margin: 20px 0;">
    <input type="password" id="passcode" style="padding: 12px; border-radius: 8px; border: 1px solid #ddd; width: 150px; text-align: center; font-size: 1.2em;">
  </div>
  <button onclick="checkPass()" style="padding: 12px 30px; cursor: pointer; background: #0050b3; color: white; border: none; border-radius: 8px; font-weight: bold;">ОТКРЫТЬ</button>
</div>

<div id="invest-content" style="display:none; line-height: 1.6;">
  <h1 align="center">💰 ФИНАНСОВЫЙ МЕМОРАНДУМ: ЭТАП "КРЫМ"</h1>
  <hr>
  <h3>1. Инвестиционный план</h3>
  <p>Общий объем инвестиций: <b>130 000 000 ₽</b></p>
  <table border="1" width="100%" style="border-collapse: collapse; margin: 20px 0;">
    <tr bgcolor="#f8f9fa">
      <th style="padding: 10px;">Направление</th>
      <th style="padding: 10px;">Сумма (₽)</th>
      <th style="padding: 10px;">Ценность для Партнера</th>
    </tr>
    <tr><td>Smart-Инфраструктура</td><td>58 млн</td><td>Брендирование 11 технологичных хабов.</td></tr>
    <tr><td>R&D и Cloud Studio</td><td>35 млн</td><td>Доля в уникальном ПО и ИИ-алгоритмах.</td></tr>
    <tr><td>Фонд развития талантов</td><td>20 млн</td><td>Социальная ответственность (ESG) и Навигатор.</td></tr>
    <tr><td>Media Production</td><td>7,9 млн</td><td>Виральный контент и охваты.</td></tr>
    <tr><td>Оператор (НКО)</td><td>9,1 млн</td><td>Юридическое и админ. сопровождение.</td></tr>
  </table>

  <h3>2. Капитализация</h3>
  <p>Масштабирование через технологическую франшизу в регионы РФ и страны БРИКС+. Прогнозная стоимость мастер-франшизы за рубежом: <b>от $1,5 млн.</b></p>
  <p align="center" style="background: #e6f7ff; padding: 15px; border-radius: 8px;"><b>СТАТУС ГЕНЕРАЛЬНОГО ПАРТНЕРА: ВАКАНТНО</b></p>
</div>

<script>
function checkPass() {
  if(document.getElementById("passcode").value == "11") {
    document.getElementById("invest-content").style.display = "block";
    document.getElementById("lock-screen").style.display = "none";
  } else { alert("Доступ отклонен"); }
}
</script>
