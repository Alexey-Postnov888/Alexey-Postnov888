# Android Developer

ФИО: Постнов Алексей Дмитриевич

Город: Челябинск

Возраст: 21 год

Контактные данные:

- Telegram: [@Alexey_Postnov888](https://t.me/alexey_postnov888) - предпочитаемый способ связи
- Email: adpostnov@yandex.ru

## Обо мне

Android-разработчик на Kotlin с практическим опытом создания клиентских приложений: от проектирования архитектуры Android-приложений (Clean Architecture, MVVM, модульный подход) и реализации клиент-серверного взаимодействия до рефакторинга и развития существующих проектов. Имею опыт разработки приложений на Jetpack Compose и XML, работы с Coroutines/Flow, Retrofit, Room, Dependency Injection (Koin, Dagger) и др. Дополнительно имею опыт backend-разработки на Kotlin/Java и проектирования распределённых систем. Имею опыт командной работы по Agile (Scrum), понимаю полный цикл разработки продукта, участвовал в процессах планирования и реализации задач. Уровень английского: B1-B2

## Образование

Челябинский государственный университет (2023 - 2027)

Направление: программная инженерия

Курс: 3

## Сертификаты
| Название | Год получения | Ссылка |
|---|:---:|:---:|
| Стипендиат Астра-стипендии 2025/2026 | 2026 | [Посмотреть](https://disk.yandex.ru/i/1axQ_KxqVDGv8A) |
| Астра паспорт | 2025 | [Посмотреть](https://disk.yandex.ru/i/NF_IRWyi2Gl0bA) |
| Участник проектного практикума Т-Банка (Android-разработчик) | 2025 | [Посмотреть](https://disk.yandex.ru/i/hHOqn_kS-86Zpg) |

## Технические навыки

- Языки: Kotlin, Java
- Android: Jetpack Compose, XML, Android SDK, Coil, Voyager, Room, Material Design 3
- Архитектура и DI: Clean Architecture, MVVM, модульность, Dagger, Koin, Coroutines/Flow
- Сеть: Retrofit, Kotlin/GSON Serialization, REST API
- Backend: Ktor, Spring, RabbitMQ, JWT, Keycloak
- Базы данных: SQL, Room, PostgreSQL, pgvector, MySQL, ORM, SQLite
- Инфраструктура и DevOps: Docker, Docker Compose, Nginx, Proxmox VE, Grafana, Prometheus
- Инструменты: Git, Figma

## Практический опыт

### Опыт работы

#### The Red One (март - май 2026) | Kotlin Developer

Мой вклад:

- Выполнил рефакторинг Android-клиента: улучшил разделение слоёв Clean Architecture, отделил сетевой слой от Android Framework и подготовил его к дальнейшему использованию в Kotlin Multiplatform.
- Исправил UI/UX-проблемы приложения, улучшив отображение данных и работу с уведомлениями.
- Улучшил архитектуру backend-части: устранил зависимость Domain-слоя от фреймворка, улучшив разделение слоёв Clean Architecture.
- Оптимизировал работу backend: устранил потенциальные блокировки при вызовах Firebase, добавил индексы и ограничения целостности данных в базе данных.
- Повысил безопасность приложения: вынес секреты из исходного кода и усилил защиту вебхуков.


### Android

#### Courses ([Courses](https://github.com/Alexey-Postnov888/EffectiveMobileCourses))

Стек: Jetpack Compose, Clean Architecture (модульная), MVVM, Koin, Retrofit, Room, Voyager

Спроектировал и внедрил модульную архитектуру (core-, feature-модули), изолировав функциональные части приложения и повысив переиспользуемость компонентов. Реализовал Clean Architecture, кэширование сетевых данных через Room для поддержки оффлайн-режима.

#### ChordFlow ([ChordFlow](https://github.com/Alexey-Postnov888/ChordFlow))

> Android приложение для просмотра текста песен с аккордами.

Разработал приложение с использованием Clean Architecture и MVVM. Реализовал декларативный UI на Jetpack Compose, внедрение зависимостей с использованием Koin, сетевой слой на базе Retrofit и Gson, локальное кэширование данных через Room для поддержки оффлайн-режима. Организовал навигацию между экранами с использованием Voyager.

#### EventDesigner ([event_designer](https://github.com/Alexey-Postnov888/event_designer))

> Проект в рамках практикума Т-Банка. Я разрабатывал Android-клиент.

Реализовал Android-клиент с использованием Clean MVVM и XML. Настроил внедрение зависимостей с использованием Dagger, сетевое взаимодействие через Retrofit с Kotlin Serialization и кастомный Interceptor для авторизации запросов, хранение токенов через SharedPreferences. Реализовал навигацию с вложенными графами, загрузку изображений через Coil и интерактивную работу с изображениями через PhotoView. Для отображения временной шкалы использовал кастомные UI-компоненты TimelineView.

#### YandexLamp ([yandexLamp](https://github.com/Alexey-Postnov888/yandexLamp))

> Приложение для управления Яндекс лампой через API.

Реализовал архитектуру Clean MVVM, внедрение зависимостей с использованием Dagger, сетевой слой на базе Retrofit и UI-компоненты с использованием Material Design 3.

### Backend / DevOps опыт

- Спроектировал и разработал распределённую систему для работы с заметками (Ktor, Qdrant, Elasticsearch, WebSockets, Redis, Keycloak)
- Спроектировал и разработал микросервисную систему информирования для факультета (Ktor, API Gateway, RabbitMQ, Keycloack)
- Развернул серверную инфраструктуру на собственном сервере (Proxmox, Docker Compose, Nginx, мониторинг)

> Детальное описание Backend и DevOps проектов: [смотреть](https://github.com/Alexey-Postnov888/Alexey-Postnov888/blob/master/README.md)
