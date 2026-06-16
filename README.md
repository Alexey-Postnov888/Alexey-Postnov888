# Android Developer

ФИО: Постнов Алексей Дмитриевич

Город: Челябинск

Возраст: 21 год

Контактные данные:

- Telegram: [@Alexey_Postnov888](https://t.me/alexey_postnov888) - предпочитаемый способ связи
- Email: adpostnov@yandex.ru

## Обо мне

Android-разработчик с практическим опытом создания клиентских Android приложений на Kotlin (Jetpack Compose, XML) и экспертизой в full-stack разработке: от проектирования микросервисной архитектуры на Kotlin, Java до развёртывания серверной инфраструктуры. Имею опыт командной работы по Agile (Scrum), понимаю полный цикл разработки продукта, что позволяет не только эффективно проектировать клиент-серверное взаимодействие, API, но и участвовать в процессах планирования и реализации задач. Стремлюсь в команду, где смогу применять, развивать и обретать новые навыки в интересных проектах. Уровень английского: B1-B2

## Образование

Челябинский государственный университет (2023 - 2027)

Направление: программная инженерия

Курс: 3

## Сертификаты
| тест | что-то |
|---|---|
| тест | тест |
| тест | тест |

## Технические навыки

- Языки: Kotlin, Java
- Android: Jetpack Compose, XML, Android SDK, Material Design 3
- Архитектура и DI: Clean Architecture, MVVM, модульность, Dagger, Koin, Coroutines/Flow
- Сеть: Retrofit, Kotlin/GSON Serialization, REST API
- Backend: Ktor, Spring, RabbitMQ, JWT, Keycloak
- Базы данных: SQL, Room, PostgreSQL, pgvector, MySQL, ORM, SQLite
- Инфраструктура и DevOps: Docker, Docker Compose, Nginx, Proxmox VE, Grafana, Prometheus
- Инструменты: Git, Figma

## Практический опыт

### Android

#### Courses ([Courses](https://github.com/Alexey-Postnov888/EffectiveMobileCourses))

Стек: Jetpack Compose, Clean Architecture (модульная), MVVM, Koin, Retrofit, Room, Voyager

Спроектировал и внедрил модульную архитектуру (cores, features), что позволило ускорить сборку за счёт изоляции модулей, повысить переиспользуемость кода, масштабируемость. Разделение на слои по Clean Architecture упрощает поддержку и тестирование приложения. Реализовал кэширование сетевых запросов для оффлайн-режима, улучшения пользовательского опыта

#### ChordFlow ([ChordFlow](https://github.com/Alexey-Postnov888/ChordFlow))

> Android приложение для просмотра текста песен с аккордами.

Реализовал проект на Clean Architecture c MVVM для presentation слоя (Clean MVVM), UI - декларативный подход с Jetpack Compose, DI реализован через Koin, для работы с сетью использовал Retrofit с фабрикой GSON, Room использовал для кэширования сетевых данных (оффлайн-режим), навигация организована при помощи Voyager

#### EventDesigner ([event_designer](https://github.com/Alexey-Postnov888/event_designer))

> Проект в рамках практикума Т-Банка. Я разрабатывал Android-клиент.

Реализовал клиент на Clean MVVM, для DI использовал Dagger, для работы с сетью - Retrofit с фабрикой Kotlin Serialization, UI - императивный подход с XML, авторизованные запросы реализованы при помощи кастомного интерсептера (и работа с SharedPreferences), навигация производилась через вложенные графы навигации, загрузка изображений через Coil, а интерактивная работа с ними - PhotoView (by chrisbanes), для таймлайна так же использовались кастомные декораторы TimelineView (by lriccardo)

#### YandexLamp ([yandexLamp](https://github.com/Alexey-Postnov888/yandexLamp))

> Приложение для управления Яндекс лампой через API.

Архитектура - Clean MVVM, для DI использовал Dagger, работа с сетью через Retrofit, поддержка Material Design 3

### Full-stack

- Спроектировал и разработал распределённую систему для работы с заметками (Ktor, Qdrant, Elasticsearch, WebSockets, Redis, Keycloak)
- Спроектировал и разработал микросервисную систему информирования для факультета (Ktor, API Gateway, RabbitMQ, Keycloack)
- Развернул серверную инфраструктуру на собственном сервере (Proxmox, Docker Compose, Nginx, мониторинг)

> Детальное описание Backend и DevOps проектов: [смотреть](https://github.com/Alexey-Postnov888/Alexey-Postnov888/blob/master/AddCV.md)






