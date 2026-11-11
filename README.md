<div align="center">

<img src="assets/hero.jpg" alt="Norach Charon · Fullstack Developer" width="100%" />

<br/>

[![Profile views](https://komarev.com/ghpvc/?username=norachcharon&color=6e40c9&style=for-the-badge&label=VIEWS)](https://github.com/norachcharon)
[![Fullstack](https://img.shields.io/badge/роль-Fullstack-9F7AEA?style=for-the-badge)](https://github.com/norachcharon)
[![UnseenConnect](https://img.shields.io/badge/UnseenConnect-org-0ea5e9?style=for-the-badge&logo=github)](https://github.com/UnseenConnect)
[![PMMP](https://img.shields.io/badge/Bedrock-PMMP%205.x-f78166?style=for-the-badge)](https://github.com/norachcharon)

</div>

## О себе

**Norach Charon** — fullstack-разработчик. Собираю **сайты и веб-сервисы под ключ**: проектирую API и БД, пишу бэкенд, подключаю фронт и выкатываю на Linux.

Публичная часть на GitHub — организация **[UnseenConnect](https://github.com/UnseenConnect)**: клиенты VPN на **Xray** для **Android**, **Windows** и **Linux**. Всё остальное (панели, боты, агрегаторы, мониторинг, плагины Bedrock, игры) — в **private**-репозиториях; здесь описан стек и направления, без названий закрытых проектов.

## Fullstack · сайты

| Слой | Технологии | Что делаю |
| --- | --- | --- |
| **Backend** | **Symfony**, **PHP**, Doctrine, Messenger | REST/JSON API, авторизация, роли, админки, webhooks, очереди |
| **Frontend** | **Vue** или **React** + **TypeScript** | SPA, дашборды, формы, таблицы, клиентская валидация |
| **Данные** | **PostgreSQL**, **Redis** | Миграции, индексы, кэш, сессии, rate-limit |
| **Инфра** | **Nginx**, **Docker**, Linux | Reverse proxy, TLS, compose, деплой, логи |

Типовой цикл: Symfony отдаёт API → Vue/React (TS) рисует UI → Postgres хранит состояние → Redis ускоряет горячие пути → Nginx и Docker на проде.

## UnseenConnect · Xray

Клиентская экосистема вокруг ядра **Xray**. Публичные репозитории — релизы и issues по платформам.

| Возможности | |
| --- | --- |
| Подписки | Импорт по URL, обновление профилей, несколько серверов в одном профиле |
| Режимы | Системный прокси, **TUN**, автоподключение |
| Протоколы | **VLESS** (Reality), **VMess**, **Trojan** и сочетания из подписки |
| UX | Пинг до нод, проверка доступности, автообновление приложения |

### Публичные репозитории

[![Android](https://img.shields.io/badge/Android-unseenconnect--android-3DDC84?style=for-the-badge&logo=android)](https://github.com/UnseenConnect/unseenconnect-android)
[![Windows](https://img.shields.io/badge/Windows-unseenconnect--desktop-0078D4?style=for-the-badge&logo=windows)](https://github.com/UnseenConnect/unseenconnect-desktop)
[![Linux](https://img.shields.io/badge/Linux-unseenconnect--linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://github.com/UnseenConnect/unseenconnect-linux)

| Платформа | Репозиторий | Описание |
| --- | --- | --- |
| Android | [unseenconnect-android](https://github.com/UnseenConnect/unseenconnect-android) | UnseenConnect VPN client for Android (Xray) — releases and issues |
| Windows | [unseenconnect-desktop](https://github.com/UnseenConnect/unseenconnect-desktop) | UnseenConnect VPN client for Windows (Xray) — releases and issues |
| Linux | [unseenconnect-linux](https://github.com/UnseenConnect/unseenconnect-linux) | UnseenConnect VPN client for Linux (Xray) — releases and issues |

## Minecraft Bedrock · PMMP 5.x

Активно пишу под **PocketMine-MP 5** (PMMP5) для **Minecraft: Bedrock**.

| Направление | Детали |
| --- | --- |
| **Плагины** | Мини-игры, экономика, UI, кастомные механики, интеграция с веб/API |
| **Ядро** | Форки и патчи **PocketMine-MP**: протокол Bedrock, оптимизация, кастомные расширения |
| **Деплой** | Сборка `.phar`, выкладка на Linux-сервера, сопровождение игровых инстансов |

## Игры

| Стек | Проекты |
| --- | --- |
| **Unity** | 3D, low-poly, геймплей, UI, сборки под платформы |
| **Three.js** | WebGL в браузере, 3D-сцены, **idle** / **city-sim**, интерактив и прогрессия |

## VPN-инфра (private)

За пределами публичных клиентов — панели **3x-ui**, Telegram-боты, агрегаторы подписок, мониторинг нод и автоматизация (bash, Docker). Детали и репозитории не публикую; стек совпадает с блоком **Fullstack** и **Stack** ниже.

## Stack

<div align="center">

**Backend · клиенты**

<img src="https://skillicons.dev/icons?i=php,symfony,python,kotlin,androidstudio&perline=5" alt="Backend" />

<br/>

**Frontend · игры**

<img src="https://skillicons.dev/icons?i=vue,js,ts,react,unity,cs&perline=5" alt="Frontend" />

<br/>

**Серверы и DevOps**

<img src="https://skillicons.dev/icons?i=docker,linux,nginx,postgres,redis,bash,git,github&perline=8" alt="Ops" />

<br/>

<sub>Three.js — в стеке веб-3D; отдельной иконки на skillicons.dev нет</sub>

</div>

## Активность

<div align="center">

<img src="https://streak-stats.demolab.com/?user=norachcharon&theme=github-dark&hide_border=false&border_radius=12&background=0D1117&ring=9F7AEA&fire=58A6FF&currStreakLabel=9F7AEA" alt="Streak" />

<br/>

<img src="https://raw.githubusercontent.com/norachcharon/norachcharon/main/dist/github-contribution-grid-snake-dark.svg" alt="Snake" />

</div>
