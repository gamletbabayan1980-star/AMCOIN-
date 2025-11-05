<!--
  Файл: index.html
  Лендинг: "Инфографика для маркетплейсов"
  Номер: +7 962 213 20 10

  Как использовать:
  1) Скопируйте этот файл в папку проекта.
  2) Инициализируйте git: git init
  3) Создайте репозиторий на GitHub и запушьте:
     git add .
     git commit -m "Initial commit: landing"
     git branch -M main
     git remote add origin https://github.com/<your-username>/<repo-name>.git
     git push -u origin main
  4) Чтобы опубликовать на GitHub Pages: в Settings → Pages выберите ветку main и / (root) или используйте gh-pages.

  Примечание: Для простоты я использовал Tailwind через CDN (https://cdn.tailwindcss.com). Это удобно для прототипа и публикации на GitHub Pages.
--><!doctype html>

<html lang="ru">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Инфографика для маркетплейсов — Премиум-инфографика и карточки</title>
  <meta name="description" content="Премиум-инфографика и карточки для маркетплейсов — рост CTR и конверсии. Заказать: +7 962 213 20 10" />  <!-- Tailwind CDN для быстрого прототипа -->  <script src="https://cdn.tailwindcss.com"></script>  <style>
    /* Небольшие правки для внешнего вида */
    body { -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; }
  </style></head>
<body class="bg-gray-50 text-gray-900">
  <header class="bg-white shadow">
    <div class="max-w-6xl mx-auto px-6 py-5 flex items-center justify-between">
      <div class="flex items-center gap-4">
        <div class="w-12 h-12 rounded-lg bg-gradient-to-br from-indigo-600 to-pink-500 flex items-center justify-center text-white font-bold text-lg">iM</div>
        <div>
          <h1 class="text-lg font-semibold">Инфографика для маркетплейсов</h1>
          <p class="text-xs text-gray-500">Премиум-инфографика и карточки товаров — рост конверсии</p>
        </div>
      </div><div class="flex items-center gap-4">
    <a href="tel:+79622132010" class="hidden sm:inline-flex items-center gap-2 px-4 py-2 rounded-md border border-gray-200 hover:shadow">
      <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" viewBox="0 0 20 20" fill="currentColor"><path d="M2 3.5A1.5 1.5 0 013.5 2h2A1.5 1.5 0 017 3.5V5a1 1 0 01-1 1H6a1 1 0 00-.8.4l-.6.9a11.04 11.04 0 005.7 5.7l.9-.6A1 1 0 0114 11v-.1a1 1 0 011-1h1.5A1.5 1.5 0 0118 10.5v2A1.5 1.5 0 0116.5 14H15a3 3 0 01-3-3V9a2 2 0 00-2-2H8.5A1.5 1.5 0 017 5.5V4A1.5 1.5 0 015.5 2.5h-2A1.5 1.5 0 012 3.5z" /></svg>
      <span class="text-sm">+7 962 213 20 10</span>
    </a>

    <a href="https://wa.me/79622132010" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-2 px-4 py-2 rounded-md bg-green-500 text-white shadow hover:opacity-95">Написать в WhatsApp</a>
  </div>
</div>

  </header>  <main class="max-w-6xl mx-auto px-6 py-12">
    <!-- Hero -->
    <section class="grid grid-cols-1 lg:grid-cols-2 gap-8 items-center mb-12">
      <div>
        <h2 class="text-4xl font-extrabold leading-tight">Премиум-инфографика и карточки для маркетплейсов</h2>
        <p class="mt-4 text-lg text-gray-600">Мы создаём визуальные карточки и инфографику, которые объясняют ценность товара за 3 секунды и повышают CTR и конверсию. Готовы к запуску — от адаптации под правила маркетплейса до оптимизации под мобильные каталоги.</p><div class="mt-6 flex gap-4">
      <a href="tel:+79622132010" class="inline-flex items-center gap-3 px-5 py-3 rounded-lg bg-indigo-600 text-white font-medium shadow">Заказать звонок</a>
      <a href="#contact" class="inline-flex items-center gap-3 px-5 py-3 rounded-lg border border-gray-200">Оставить заявку</a>
    </div>

    <ul class="mt-8 grid grid-cols-1 sm:grid-cols-2 gap-3 text-sm text-gray-700">
      <li>✅ Карточки товаров (фото + дизайн)</li>
      <li>✅ Инфографика технических характеристик</li>
      <li>✅ Сравнительные блоки и иконки</li>
      <li>✅ Оптимизация под мобильные листинги</li>
    </ul>

    <div class="mt-8 flex items-center gap-6">
      <div>
        <p class="text-3xl font-semibold">+20%</p>
        <p class="text-xs text-gray-500">Средний рост конверсии у клиентов</p>
      </div>
      <div>
        <p class="text-3xl font-semibold">500+</p>
        <p class="text-xs text-gray-500">Карточек и инфографик разработано</p>
      </div>
    </div>
  </div>

  <div class="relative">
    <div class="rounded-2xl overflow-hidden shadow-xl">
      <img alt="Примеры работ" src="https://picsum.photos/seed/hero/1200/900" class="w-full h-96 object-cover" />
    </div>
    <div class="absolute -bottom-6 left-6 bg-white rounded-xl shadow p-4 w-64">
      <p class="text-xs text-gray-500">Быстрая демонстрация</p>
      <p class="font-medium">Карточки под любую категорию</p>
    </div>
  </div>
</section>

<!-- Process -->
<section class="mb-12">
  <h3 class="text-2xl font-semibold mb-6">Как мы работаем</h3>
  <div class="grid grid-cols-1 md:grid-cols-4 gap-6">
    <div class="bg-white p-6 rounded-lg shadow">
      <h4 class="font-semibold">1. Бриф</h4>
      <p class="text-sm text-gray-600 mt-2">Вы присылаете ТЗ или пример — мы анализируем товар и целевую аудиторию.</p>
    </div>
    <div class="bg-white p-6 rounded-lg shadow">
      <h4 class="font-semibold">2. Концепт</h4>
      <p class="text-sm text-gray-600 mt-2">Готовим 2-3 концепта инфографики/карточки для согласования.</p>
    </div>
    <div class="bg-white p-6 rounded-lg shadow">
      <h4 class="font-semibold">3. Доработка</h4>
      <p class="text-sm text-gray-600 mt-2">Вносим правки, подгоняем под требования маркетплейса.</p>
    </div>
    <div class="bg-white p-6 rounded-lg shadow">
      <h4 class="font-semibold">4. Готово</h4>
      <p class="text-sm text-gray-600 mt-2">Файлы в нужных размерах и форматах — PNG, JPG, SVG по запросу.</p>
    </div>
  </div>
</section>

<!-- Portfolio -->
<section class="mb-12">
  <div class="flex items-center justify-between">
    <h3 class="text-2xl font-semibold">Портфолио — примеры работ</h3>
    <a href="#portfolio" class="text-sm text-indigo-600">Смотреть все</a>
  </div>

  <div id="portfolio" class="mt-6 grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
    <div class="bg-white rounded-lg overflow-hidden shadow hover:scale-[1.01] transition-transform">
      <img src="https://picsum.photos/seed/1/800/600" alt="Карточка — Электроника" class="w-full h-48 object-cover" />
      <div class="p-4">
        <h4 class="font-medium">Карточка — Электроника</h4>
        <p class="text-sm text-gray-500 mt-2">Демонстрация оформления карточки и наглядного блока инфографики.</p>
        <div class="mt-3 flex gap-2">
          <a href="https://picsum.photos/seed/1/800/600" target="_blank" rel="noopener" class="text-sm px-3 py-2 border rounded">Открыть</a>
          <button onclick="orderSample('Карточка — Электроника')" class="text-sm px-3 py-2 bg-indigo-600 text-white rounded">Заказать похожее</button>
        </div>
      </div>
    </div>

    <div class="bg-white rounded-lg overflow-hidden shadow hover:scale-[1.01] transition-transform">
      <img src="https://picsum.photos/seed/2/800/600" alt="Инфографика — Характеристики" class="w-full h-48 object-cover" />
      <div class="p-4">
        <h4 class="font-medium">Инфографика — Характеристики</h4>
        <p class="text-sm text-gray-500 mt-2">Понятные блоки для мобильных и десктоп листингов.</p>
        <div class="mt-3 flex gap-2">
          <a href="https://picsum.photos/seed/2/800/600" target="_blank" rel="noopener" class="text-sm px-3 py-2 border rounded">Открыть</a>
          <button onclick="orderSample('Инфографика — Характеристики')" class="text-sm px-3 py-2 bg-indigo-600 text-white rounded">Заказать похожее</button>
        </div>
      </div>
    </div>

    <div class="bg-white rounded-lg overflow-hidden shadow hover:scale-[1.01] transition-transform">
      <img src="https://picsum.photos/seed/3/800/600" alt="Карточка — Дом и сад" class="w-full h-48 object-cover" />
      <div class="p-4">
        <h4 class="font-medium">Карточка — Дом и сад</h4>
        <p class="text-sm text-gray-500 mt-2">Адаптация под категорию и стилистику бренда.</p>
        <div class="mt-3 flex gap-2">
          <a href="https://picsum.photos/seed/3/800/600" target="_blank" rel="noopener" class="text-sm px-3 py-2 border rounded">Открыть</a>
          <button onclick="orderSample('Карточка — Дом и сад')" class="text-sm px-3 py-2 bg-indigo-600 text-white rounded">Заказать похожее</button>
        </div>
      </div>
    </div>

  </div>
</section>

<!-- Pricing -->
<section class="mb-12">
  <h3 class="text-2xl font-semibold mb-6">Пакеты услуг (ориентировочно)</h3>
  <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
    <div class="bg-white p-6 rounded-xl shadow">
      <h4 class="text-lg font-semibold">Старт</h4>
      <p class="text-sm text-gray-600 mt-2">1 инфографика или 1 карточка — базовое оформление, 1 итерация правок.</p>
      <p class="mt-4 font-bold">От 3 500 ₽</p>
      <a href="#contact" class="mt-4 inline-block text-sm px-4 py-2 border rounded">Заказать</a>
    </div>
    <div class="bg-white p-6 rounded-xl shadow border-2 border-indigo-600">
      <h4 class="text-lg font-semibold">Популярный</h4>
      <p class="text-sm text-gray-600 mt-2">3 карточки + 1 инфографика, адаптация под мобильные каталоги.</p>
      <p class="mt-4 font-bold">От 9 900 ₽</p>
      <a href="#contact" class="mt-4 inline-block text-sm px-4 py-2 bg-indigo-600 text-white rounded">Заказать</a>
    </div>
    <div class="bg-white p-6 rounded-xl shadow">
      <h4 class="text-lg font-semibold">Бренд</h4>
      <p class="text-sm text-gray-600 mt-2">Полный пакет для категорий с высоким трафиком — A/B блоки, иконки, SVG.</p>
      <p class="mt-4 font-bold">Индивидуально</p>
      <a href="#contact" class="mt-4 inline-block text-sm px-4 py-2 border rounded">Заказать</a>
    </div>
  </div>
</section>

<!-- Contact -->
<section id="contact" class="mb-12 bg-gradient-to-r from-white to-gray-50 p-8 rounded-2xl">
  <div class="grid grid-cols-1 lg:grid-cols-2 gap-8 items-start">
    <div>
      <h3 class="text-2xl font-semibold">Оставьте заявку</h3>
      <p class="text-gray-600 mt-3">Опишите задачу — мы подготовим коммерческое предложение и сроки. Для срочных задач звоните: <a href="tel:+79622132010" class="font-medium text-indigo-600">+7 962 213 20 10</a></p>

      <div class="mt-6 grid grid-cols-1 gap-3">
        <div class="bg-white p-4 rounded-lg shadow">
          <p class="text-sm text-gray-500">Готовы начать прямо сейчас?</p>
          <a href="https://wa.me/79622132010" target="_blank" rel="noopener noreferrer" class="mt-2 inline-block text-sm px-4 py-2 bg-green-500 text-white rounded">Написать в WhatsApp</a>
        </div>

        <div class="bg-white p-4 rounded-lg shadow">
          <p class="text-sm text-gray-500">Нужен срочный обзор карточек?</p>
          <a href="tel:+79622132010" class="mt-2 inline-block text-sm px-4 py-2 border rounded">Заказать звонок</a>
        </div>
      </div>
    </div>

    <form id="contactForm" class="bg-white p-6 rounded-lg shadow">
      <label class="block text-sm font-medium">Ваше имя</label>
      <input name="name" class="mt-2 block w-full rounded-md border-gray-200 p-2" placeholder="Иван" />

      <label class="block text-sm font-medium mt-4">Email</label>
      <input name="email" class="mt-2 block w-full rounded-md border-gray-200 p-2" placeholder="ivan@mail.ru" />

      <label class="block text-sm font-medium mt-4">Коротко о задаче</label>
      <textarea name="message" class="mt-2 block w-full rounded-md border-gray-200 p-2 h-28" placeholder="Например: 3 карточки для косметики, нужна инфографика по составу"></textarea>

      <div class="mt-4 flex items-center gap-3">
        <button type="submit" class="px-4 py-2 rounded bg-indigo-600 text-white font-medium">Отправить</button>
        <a href="https://wa.me/79622132010" target="_blank" rel="noopener noreferrer" class="px-4 py-2 rounded border">Написать в WhatsApp</a>
      </div>

      <p class="mt-4 text-xs text-gray-500">Номер для связи: <a href="tel:+79622132010" class="font-medium text-indigo-600">+7 962 213 20 10</a></p>
    </form>
  </div>
</section>

<footer class="py-10 text-center text-sm text-gray-500">
  © <span id="year"></span> Инфографика для маркетплейсов — все права защищены. Тел: <a href="tel:+79622132010" class="text-indigo-600">+7 962 213 20 10</a>
</footer>

  </main>  <script>
    // Подставляем текущий год
    document.getElementById('year').textContent = new Date().getFullYear();

    // Обработка формы: заглушка. Для реальной отправки подключите бэкенд или сервис (Formspree, Google Forms, Zapier и т.д.)
    document.getElementById('contactForm').addEventListener('submit', function(e){
      e.preventDefault();
      const form = e.target;
      const name = form.name.value || 'клиент';
      const email = form.email.value || '(не указан)';
      const message = form.message.value || '(без описания)';

      alert(`Спасибо, ${name}!\nМы получили вашу заявку:\n\n${message}\n\nС вами свяжутся по email: ${email} или по телефону +7 962 213 20 10`);
      form.reset();
    });

    function orderSample(title){
      const url = `https://wa.me/79622132010?text=${encodeURIComponent('Здравствуйте! Хочу заказать похожую работу: '+title)}`;
      window.open(url,'_blank');
    }
  </script></body>
</html>