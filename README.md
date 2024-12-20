## Лабораторная работа 3

Выполнил работу студент Яковлев Даниил

Язык программирования: Kotlin

### Описание

В данной лабораторной работе было разработано Android-приложение на языке Kotlin, которое взаимодействует с базой данных SQLite. Приложение позволяет управлять записями о одногруппниках, включая добавление, отображение и обновление информации.

### Техническое задание

**Задание 1:**
1. Создание приложения с базой данных.
2. Первое активити содержит три кнопки:
   - Первая кнопка открывает новое активити, выводящее информацию из таблицы «Одногруппники».
   - Вторая кнопка добавляет запись о новом одногруппнике.
   - Третья кнопка обновляет ФИО в последней записи.
3. При запуске приложения:
   - Создать базу данных, если она не существует.
   - Создать таблицу «Одногруппники», содержащую поля: ID, ФИО и время добавления записи.
   - Удалить все записи из БД и внести 5 записей об одногруппниках.

**Задание 2:**
1. Создать новое приложение на основе предыдущего.
2. Переопределить функцию `onUpgrade`, чтобы при изменении версии БД удалялась таблица «Одногруппники» и создавалась новая таблица с полями: ID, Фамилия, Имя, Отчество и время добавления записи.

### Используемые технологии
- Android Studio
- Язык программирования: Kotlin
- База данных: SQLite

### Установка и запуск

1. Клонируйте репозиторий или скачайте проект.
2. Откройте проект в Android Studio.
3. Убедитесь, что у вас установлены все необходимые зависимости.
4. Запустите приложение на эмуляторе или реальном устройстве.

### Функциональность

- При запуске приложения создается база данных и таблица «Одногруппники», если они не существуют.
- Пользователь может:
  - Просмотреть список одногруппников.
  - Добавить нового одногруппника.
  - Обновить информацию о последнем одногруппнике.

### Примечания
- Для работы приложения требуется включение разрешений на доступ к базе данных.
- Код приложения включает в себя комментарии для пояснения функциональности.

---
