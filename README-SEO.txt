КАК НАСТРОИТЬ ПОИСК ДЛЯ САЙТА НА GITHUB PAGES

1. Откройте репозиторий GitHub -> Settings -> Pages.
2. Найдите точный адрес опубликованного сайта. Он будет похож на:
   https://USERNAME.github.io/REPOSITORY/
   или https://USERNAME.github.io/
3. Во всех трех файлах index.html, robots.txt и sitemap.xml замените SITE_URL на этот адрес.
   Важно: адрес должен заканчиваться символом /.
4. Загрузите index.html, robots.txt и sitemap.xml в корень репозитория.
5. Проверьте, что в браузере открываются:
   SITE_URL
   SITE_URLrobots.txt
   SITE_URLsitemap.xml
6. Добавьте сайт в Google Search Console: https://search.google.com/search-console/
   После подтверждения отправьте sitemap.xml и запросите индексацию главной страницы.
7. Добавьте сайт в Яндекс Вебмастер: https://webmaster.yandex.ru/
   После подтверждения добавьте sitemap.xml и отправьте главную страницу на переобход.

В index.html уже добавлены title, description, robots, canonical, Open Graph и Schema.org-разметка.
Также добавлены естественные поисковые формулировки для Динской, Краснодара, риичи и риити-маджонга.
