<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Redirecting...</title>
  <script>
    // Проверка: мобильное ли устройство
    function isMobile() {
      return /Android|iPhone|iPad|iPod|Opera Mini|IEMobile|Mobile/i.test(navigator.userAgent);
    }

    window.onload = function () {
      const offers = [
        "https://grzvkg.amurllove.com/?utm_source=da57dc555e50572d&ban=inst&j1=1&s1=212364&s2=2166099", // оффер 1
        "https://somana.top/click?o=2&a=6549&sub_id1=insta", // оффер 2
        "https://tone.affomelody.com/aJ9mcJ", // оффер 3
        ""  // оффер 4
      ];

      const desktopRedirect = "https://t.me/+r3kPlvWsjdcxZWUy"; // для десктопа

      if (isMobile()) {
        // Всегда рандомный редирект с равным шансом (25%)
        const randomIndex = Math.floor(Math.random() * offers.length);
        window.location.href = offers[randomIndex];
      } else {
        window.location.href = desktopRedirect;
      }
    };
  </script>
</head>
<body>
  <p>Переход на оффер...</p>
</body>
</html>
