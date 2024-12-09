# Story sphere

**Это платформа для публикации и распространения авторского контента, где пользователи могут загружать книги, статьи и журналы, выбирать жанры, управлять своими публикациями и предлагать их широкой аудитории, с возможностью монетизации и аналитики.**

Для реализации системы выбрана микросервисная архитектура, что позволяет гибко масштабировать и развивать каждый из компонентов системы отдельно.

## Ссылки на репозитории для каждого микросервиса

В разработке
- [S-1: Сервис загрузки публикаций](https://github.com/svyat-lag/publication-service): Сервис, отвечающий за загрузку публикаций в систему;
- [S-5: Сервис авторизации](): Единый сервер авторизации по спецификации OAuth2.0;

Планируется
- [S-2: Сервис публикаций](): Сервис, отвечающий за хранение публикаций пользователей;
- [S-3: Платежный сервис](): Сервис, отвечающий за совершение внутренних платежных операций таких, как оплата услуг, и хранение информации об этом;
- [S-4: Сервис профиля пользователей](): Сервис, отвечающий за управление пользовательским профилем и хранение личных данных пользователей;
- [S-6: Сервис отправки уведомлений](): Сервис, отвечающий за отправку пользователям уведомлений внутри системы;
- [S-7: Сервис отправки писем](): Сервис, отвечающий за отправку пользователям писем по электронной почте;
- [S-8: Сервис обработки услуг](): Сервис, отвечающий за обработку услуг по публикациям;
- [S-9: Сервис поддержки](): Сервис, отвечающий за страницу поддержки.
