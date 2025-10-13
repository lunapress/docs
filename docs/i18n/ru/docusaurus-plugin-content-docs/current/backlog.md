---
sidebar_position: 100
---

# Backlog {#baclog}

## Общее
- [x] Нейминг экосистеме
- [x] Монорепозиторий, как у Symfony, для разделения врапперов на отдельные пакеты
- [x] Реализовать поддержку `Service Package`
- [ ] Кастомный генератор файлов локализации с поддержкой `TS` и единым конфигом с доменом плагина
- [ ] Внедрение тестов с **[wp-browser](https://github.com/lucatume/wp-browser)**
- [ ] Современная замена Carbon Fields ( `Package` )
- [ ] CLI для генерации `boilerplate`, аналог `Artisan Console` ( `Composer` )
- [ ] Шаблонный вьювер логов плагина ( `Package` )
- [ ] Отвязка от метаданных WP и переход на **[wp-orm](https://github.com/dimitriBouteille/wp-orm)**, с миграциями через **[Phinx](https://phinx.org/)** ( `Package` )
- [ ] Watcher для автоперезагрузки при изменениях
- [ ] Сделать удобнее Prefixer Namespaces для `vendor`
- [ ] Notice Manager ( `Package` )
- [ ] Custom Updater ( `Package` )

## Plugin Template
- [ ] Продуманная и единая (рекомендуемая) структура плагинов, описанная в доке
- [ ] Разворачивание через Composer project template

## Components
- [ ] Создать пакет

## Frontend
- [ ] Создание папки с настроенным фронтендом при установке пакета / команда для создания
- [ ] Конфигурация фронтенда ( `JS` / `TS` / `React` )
- [ ] Тесты до 100% покрытия

## WooCommerce
- [ ] Создать пакет

## Core
- [x] Расширение конфига плагина (парсить инфу из главного файла)
- [x] Поддержка подключения и переопределения PHP шаблонов
- [ ] Мультиязычность
- [ ] Hook Remover
- [x] Кеширование DI
- [ ] Врапперы глобальных WP функций
- [ ] Поддержка тем
- [ ] Тесты до 100% покрытия

## Static Analysis
- [ ] Попробовать вынести конфиг Rector в `.config` + прокси-CLI
- [ ] Тесты до 100% покрытия

## Coding Standard
- [ ] Разрешать return при проверке `ABSPATH` вместо обязательного exit (для случаев, когда composer autoload загружает функции с неймспейсом и сразу делает exit)
- [ ] Тесты до 100% покрытия

## Psalm Plugin
- [ ] Создать пакет
- [ ] Автопоиск и автоимпорт (stubs)
- [ ] Статический анализ хуков под нашу реализацию, вместо **[psalm-plugin-wordpress](https://github.com/psalm/psalm-plugin-wordpress)**
- [ ] Тесты до 100% покрытия

## WordPress Stub Generator
- [ ] Шаблон для быстрого разворачивания и генерации stubs (Composer project template)
- [ ] Тесты до 100% покрытия
