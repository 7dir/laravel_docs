# Laravel Документация

Перевод документации Laravel 6.x [https://7dir.github.io/laravel_docs/](https://7dir.github.io/laravel_docs/)

[https://laravel.com/docs](https://laravel.com/docs)

## Состав

<ul>
    <li class="">
        <h2>Пролог</h2>
        <ul>
            <li><a href="releases">Заметки выпуска</a></li>
            <li><a href="upgrade">Обновление до 6.x</a></li>
            <li><a href="contributions">Гид содействия</a></li>
            <li><a href="api/6.x">API документация</a></li>
        </ul>
    </li>
    <li>
        <h2>Первый запуск</h2>
        <ul>
            <li><a href="installation">Установка</a></li>
            <li><a href="configuration">Конифгурация</a></li>
            <li><a href="structure">Структура каталогов</a></li>
            <li><a href="homestead">Homestead - Vagrant box</a></li>
            <li><a href="valet">Valet - development environment for Mac</a></li>
            <li><a href="deployment">Развертывание</a></li>
        </ul>
    </li>
    <li>
        <h2>Концепт архитектуры</h2>
        <ul>
            <li><a href="lifecycle">Request Lifecycle - Жизненный цикл запроса</a></li>
            <li><a href="container">Service Container - Контейнер</a></li>
            <li><a href="providers">Service Providers - Провайдер</a></li>
            <li><a href="facades">Facades - Фасады</a></li>
            <li><a href="contracts">Contracts - Контракты</a></li>
        </ul>
    </li>
    <li>
        <h2>Основы</h2>
        <ul>
            <li><a href="routing">Routing - Маршрутизация</a></li>
            <li><a href="middleware">Middleware - промежуточное программное обеспечение</a></li>
            <li><a href="csrf">CSRF Protection - Защита cross-site request forgery межсайтовая подделка запроса</a></li>
            <li><a href="controllers">Controllers - Контролеры</a></li>
            <li><a href="requests">Requests - Запросы</a></li>
            <li><a href="responses">Responses - Ответы</a></li>
            <li><a href="views">Views - Виды</a></li>
            <li><a href="urls">URL Generation - генерация URL</a></li>
            <li><a href="session">Session - Сессии</a></li>
            <li><a href="validation">Validation - Валидация</a></li>
            <li><a href="errors">Error Handling - Обработка ошибок</a></li>
            <li><a href="logging">Logging - Логирование</a></li>
        </ul>
    </li>
    <li>
        <h2>Frontend</h2>
        <ul>
            <li><a href="blade">Blade Templates - Блейд шаблоны</a></li>
            <li><a href="localization">Localization - Локализация</a></li>
            <li><a href="frontend">Frontend Scaffolding - Геннерация Frontend-а</a></li>
            <li><a href="mix">Compiling Assets - Компиляция Активов</a></li>
        </ul>
    </li>
    <li>
        <h2>Безопасность</h2>
        <ul>
            <li><a href="authentication">Authentication</a></li>
            <li><a href="api-authentication">API Authentication</a></li>
            <li><a href="authorization">Authorization</a></li>
            <li><a href="verification">Email Verification</a></li>
            <li><a href="encryption">Encryption</a></li>
            <li><a href="hashing">Hashing</a></li>
            <li><a href="passwords">Password Reset</a></li>
        </ul>
    </li>
    <li>
        <h2>Копнём поглубже</h2>
        <ul>
            <li><a href="artisan">Artisan Console - Консоль</a></li>
            <li><a href="broadcasting">Broadcasting - Широковещание</a></li>
            <li><a href="cache">Cache - Кеш</a></li>
            <li><a href="collections">Collections - Коллекции</a></li>
            <li><a href="events">Events - События</a></li>
            <li><a href="filesystem">File Storage - Файловое хранилище</a></li>
            <li><a href="helpers">Helpers - Помощники</a></li>
            <li><a href="mail">Mail - Почта</a></li>
            <li><a href="notifications">Notifications - Уведомления</a></li>
            <li><a href="packages">Package Development - Разработка пакета</a></li>
            <li><a href="queues">Queues - Очереди</a></li>
            <li><a href="scheduling">Task Scheduling - Расписание задач</a></li>
        </ul>
    </li>
    <li>
        <h2>Базы данных</h2>
        <ul>
            <li><a href="database">С чего начать</a></li>
            <li><a href="queries">Query Builder - Генератор запросов</a></li>
            <li><a href="pagination">Pagination - Пагинация</a></li>
            <li><a href="migrations">Migrations - Миграции</a></li>
            <li><a href="seeding">Seeding - Первые данные</a></li>
            <li><a href="redis">Redis</a></li>
        </ul>
    </li>
    <li>
        <h2>Eloquent ORM</h2>
        <ul>
            <li><a href="eloquent">С чего начать</a></li>
            <li><a href="eloquent-relationships">Relationships - Отношения</a></li>
            <li><a href="eloquent-collections">Collections - Коллекции</a></li>
            <li><a href="eloquent-mutators">Mutators - Мутаторы</a></li>
            <li><a href="eloquent-resources">API Resources - API Ресурсы</a></li>
            <li><a href="eloquent-serialization">Serialization - Сериализация</a></li>
        </ul>
    </li>
    <li>
        <h2>Тестирование</h2>
        <ul>
            <li><a href="testing">С чего начать</a></li>
            <li><a href="http-tests">HTTP Tests - HTTP тесты</a></li>
            <li><a href="console-tests">Console Tests - Консольные тесты</a></li>
            <li><a href="dusk">Browser Tests - Тесты браузерные</a></li>
            <li><a href="database-testing">Database - Тесты Баз данных</a></li>
            <li><a href="mocking">Mocking - Объект-имитация</a></li>
        </ul>
    </li>
    <li>
        <h2>Официальные пакеты</h2>
        <ul>
            <li><a href="billing">Cashier</a></li>
            <li><a href="dusk">Dusk</a></li>
            <li><a href="envoy">Envoy</a></li>
            <li><a href="horizon">Horizon</a></li>
            <li><a href="passport">Passport</a></li>
            <li><a href="scout">Scout</a></li>
            <li><a href="socialite">Socialite</a></li>
            <li><a href="telescope">Telescope</a></li>
        </ul>
    </li>
</ul>

## Полезные дополнения

 - https://github.com/ElForastero/Transliterate
 - https://github.com/staudenmeir/eloquent-has-many-deep