
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>MYXAMET SHOP</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background-color: #0d0d0d;
      color: #fff;
    }
    .neon-text {
      color: #ff1f1f;
      text-shadow: 0 0 5px #ff1f1f, 0 0 10px #ff1f1f;
    }
    .neon-box {
      border: 2px solid #ff1f1f;
      box-shadow: 0 0 10px #ff1f1f, 0 0 20px #ff1f1f;
    }
    .shop-btn {
      background-color: #ff1f1f;
      color: #000;
    }
    .shop-btn:hover {
      background-color: #ff4d4d;
    }
  </style>
</head>
<body class="min-h-screen flex flex-col justify-between">

  <header class="text-center py-6">
    <h1 class="text-4xl neon-text font-bold">MYXAMET SHOP</h1>
  </header>

  <div class="flex justify-center px-4">
    <img src="banner.png" alt="Shop Banner" style="max-width: 800px; width: 100%; border-radius: 12px;" />
  </div>

  <main class="max-w-6xl mx-auto p-6 grid grid-cols-1 md:grid-cols-3 gap-6 mt-10">
    <div class="bg-black neon-box rounded-xl p-6 text-center">
      <h2 class="text-2xl neon-text mb-2">Алмазы</h2>
      <p class="mb-4">Пополнение до 50,000 алмазов</p>
      <a href="https://t.me/muhichshopff_bot?start=buy_алмазы" target="_blank" class="shop-btn px-6 py-2 rounded inline-block">Купить</a>
    </div>
    <div class="bg-black neon-box rounded-xl p-6 text-center">
      <h2 class="text-2xl neon-text mb-2">Ваучеры</h2>
      <p class="mb-4">Элитный пропуск и скины</p>
      <a href="https://t.me/muhichshopff_bot?start=buy_ваучеры" target="_blank" class="shop-btn px-6 py-2 rounded inline-block">Купить</a>
    </div>
    <div class="bg-black neon-box rounded-xl p-6 text-center">
      <h2 class="text-2xl neon-text mb-2">Прокачка</h2>
      <p class="mb-4">Помощь с рангами</p>
      <a href="https://t.me/muhichshopff_bot?start=buy_прокачка" target="_blank" class="shop-btn px-6 py-2 rounded inline-block">Купить</a>
    </div>
  </main>

  <section class="max-w-3xl mx-auto mt-12 p-6 bg-black neon-box rounded-xl text-center">
    <h3 class="text-3xl neon-text mb-4">📞 Контакты</h3>
    <p class="text-lg mb-2">Telegram: <a href="https://t.me/tologonov_m" class="text-red-400">@tologonov_m</a></p>
    <p class="text-lg">Email: <a href="mailto:fasterff2021@gmail.com" class="text-red-400">fasterff2021@gmail.com</a></p>
  </section>

  <footer class="text-center mt-12 py-6 text-sm text-gray-500">
    &copy; 2025 MYXAMET SHOP. Все права защищены.
  </footer>

</body>
</html>
