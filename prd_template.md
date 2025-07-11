# vibepm_ru - Vibe Product Management

PRD Template Example:

```markdown
# Документ с требованиями к продукту (PRD): [Название проекта]

## 1. Обзор проекта

- Четкое и краткое описание цели проекта
- Целевая аудитория и её основные потребности
- Ключевые бизнес-цели и метрики успеха

### 1.1 Цель

[Один абзац, описывающий, что это за проект и почему он важен]

### 1.2 Целевая аудитория

- Основная: [Описание основной пользовательской персоны]
- Вспомогательная: [Описание дополнительных пользовательских персон]

### 1.3 Бизнес-цели

1. [Цель 1]
2. [Цель 2]
3. [Цель 3]

### 1.4 Метрики успеха

- [Метрика 1]: [Целевое значение]
- [Метрика 2]: [Целевое значение]

## 2. Функциональные требования

- Подробное описание функций, организованное по приоритетам
- Пользовательские истории в едином формате («Как [тип пользователя], я хочу [действие], чтобы [результат]»)
- Критерии приёмки для каждой функции

### 2.1 Основные функции

#### 2.1.1 [Название функции] — ПРИОРИТЕТ: ВЫСОКИЙ

**Описание**: [Четкое описание функциональности]

**Пользовательские истории**:
- Как [тип пользователя], я хочу [действие], чтобы [результат].
- Как [тип пользователя], я хочу [действие], чтобы [результат].

**Критерии приёмки**:

- [ ] [Критерий 1]
- [ ] [Критерий 2]
- [ ] [Критерий 3]

#### 2.1.2 [Название функции] — ПРИОРИТЕТ: СРЕДНИЙ

...

### 2.2 Второстепенные функции

...

## 3. Технические требования

- Предпочтения и ограничения по архитектуре
- Необходимые интеграции с API
- Требования к производительности
- Безопасность и соответствие стандартам

### 3.1 Архитектура

- [Описание архитектуры на высоком уровне]
- [Диаграмма или ссылка на архитектурный документ]

### 3.2 Интеграции с API

1. [Название API]
   - Необходимые эндпоинты: [список]
   - Метод аутентификации: [метод]
   - Ограничения по частоте: [если применимо]

### 3.3 Требования к производительности

- Время загрузки страниц: [цель]
- Время отклика API: [цель]
- Количество одновременных пользователей: [цель]

### 3.4 Безопасность и соответствие

- [Требование по безопасности 1]
- [Требование по безопасности 2]
- Соответствие стандартам: [список нормативов]

## 4. Требования к UI/UX

- Диаграммы пользовательских потоков
- Вайрфреймы или мокапы (ссылки на дизайн-файлы)
- Дизайн-система или стилистические рекомендации

### 4.1 Пользовательские потоки

[Описание или ссылка на диаграммы пользовательских потоков]

### 4.2 Вайрфреймы

[Ссылки на вайрфреймы или мокапы]

### 4.3 Дизайн-система

- Цветовая палитра: [цвета]
- Шрифты: [шрифты]
- Библиотека компонентов: [если применимо]

## 5. Требования к данным

- Модели данных и их взаимосвязи
- Требования к хранению данных
- Потоки обработки данных

### 5.1 Модели данных

```javascript
// Пример модели пользователя
{
  id: string,
  name: string,
  email: string,
  role: enum['admin', 'user', 'guest'],
  createdAt: timestamp
}

### 5.2 Требования к базе данных

* Тип: \[SQL/NoSQL и т.д.]
* Оценочный объём: \[начальный объём и прогноз роста]
* Резервное копирование: \[частота и срок хранения]

### 5.3 Потоки обработки данных

* \[Описание процессов ETL]
* \[Описание требований к аналитике данных]

## 6. Таймлайн и ключевые этапы

* Этапы разработки
* Зависимости между компонентами

### 6.1 Этапы разработки

1. **Фаза 1** (Недели 1–3)

   * \[Функция 1]
   * \[Функция 2]
2. **Фаза 2** (Недели 4–6)

   * \[Функция 3]
   * \[Функция 4]

### 6.2 Зависимости между компонентами

* \[Функция A] должна быть завершена до \[Функции B]
* \[Внешняя зависимость] требуется для \[Функции C]

---

## 7. Заметки по реализации с помощью ИИ-инструментов

### 7.1 Рекомендуемые технологии

* Frontend: \[фреймворки/библиотеки]
* Backend: \[фреймворки/библиотеки]
* Тестирование: \[фреймворки/подходы]

### 7.2 Организация кода

* \[Предпочитаемые шаблоны]
* \[Организация модулей]
* \[Соглашения по наименованию]

### 7.3 Стратегия тестирования

* Целевой охват unit-тестами: \[процент]
* Подход к интеграционному тестированию: \[описание]
* Требования к end-to-end тестам: \[описание]
```
