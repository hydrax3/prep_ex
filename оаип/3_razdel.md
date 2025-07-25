# РАЗДЕЛ 3. ОБЩИЕ СВЕДЕНИЯ О ПРОГРАММНОМ ОБЕСПЕЧЕНИИ

## Тема 7. СТАДИИ РАЗРАБОТКИ ПРОГРАММНОГО ОБЕСПЕЧЕНИЯ

**Разработка ПО** — многошаговый процесс создания программного продукта.

**Основные этапы разработки ПО:**
1. **Анализ требований** — определение функциональности программного продукта
   - Сбор и документирование требований заказчика
   - Выяснение ограничений и предпосылок
   - Создание спецификаций требований
   - Оценка рисков и стоимости разработки
   - Результат: документация с требованиями к ПО

2. **Проектирование** — разработка структуры программы и алгоритмов
   - Проектирование архитектуры системы
   - Определение модулей и их взаимодействия
   - Создание структур данных и алгоритмов
   - Разработка интерфейсов пользователя
   - Результат: проектная документация (диаграммы, схемы, описания)

3. **Кодирование** — написание программного кода
   - Реализация алгоритмов на языках программирования
   - Соблюдение стандартов кодирования
   - Документирование кода
   - Результат: исходный код программы

4. **Тестирование** — проверка работоспособности и соответствия требованиям
   - Модульное тестирование (Unit Testing)
   - Интеграционное тестирование
   - Системное тестирование
   - Приемочное тестирование
   - Результат: протоколы тестирования, список обнаруженных ошибок

5. **Отладка** — устранение ошибок
   - Локализация ошибок
   - Исправление ошибок
   - Верификация исправлений
   - Результат: исправленный код

6. **Сопровождение** — поддержка и модификация программы после внедрения
   - Исправление обнаруженных ошибок
   - Оптимизация производительности
   - Добавление новой функциональности
   - Адаптация к изменениям окружения
   - Результат: обновленные версии программы

**Модели жизненного цикла ПО:**
- **Каскадная (водопадная) модель**
  - Последовательное выполнение этапов
  - Переход к следующему этапу только после завершения предыдущего
  - Преимущества: простота управления, чёткое планирование
  - Недостатки: низкая гибкость, поздняя обратная связь

- **Итерационная модель**
  - Циклическое повторение этапов разработки
  - Постепенное улучшение и дополнение продукта
  - Преимущества: ранняя обратная связь, гибкость
  - Недостатки: сложность управления, возможное увеличение сроков

- **Спиральная модель**
  - Сочетает элементы каскадной и итерационной моделей
  - Основана на управлении рисками
  - Преимущества: учёт рисков, ранние прототипы
  - Недостатки: сложность, зависимость от анализа рисков

- **Гибкие (Agile) методологии**
  - Адаптивная разработка с короткими итерациями
  - Тесное взаимодействие с заказчиком
  - Преимущества: гибкость, быстрая адаптация к изменениям
  - Примеры: Scrum, Kanban, XP (экстремальное программирование)

**Цели и задачи стадий:**
- **Анализ**: выявление и документирование требований заказчика
  - Определение границ проекта
  - Выявление функциональных и нефункциональных требований
  - Создание моделей системы (UML, схемы, диаграммы)

- **Проектирование**: создание архитектуры, проектирование интерфейсов и структур данных
  - Разработка архитектуры приложения
  - Проектирование баз данных
  - Выбор алгоритмов и структур данных
  - Определение интерфейсов между модулями

- **Кодирование**: реализация алгоритмов и структур данных в программном коде
  - Выбор языков программирования и технологий
  - Написание чистого и эффективного кода
  - Соблюдение стандартов и соглашений кодирования
  - Использование систем контроля версий

- **Тестирование**: обнаружение ошибок и несоответствий требованиям
  - Планирование тестирования
  - Создание тестовых случаев и сценариев
  - Автоматизация тестирования
  - Проверка покрытия кода тестами

- **Отладка**: локализация и устранение ошибок
  - Использование отладчиков
  - Анализ логов и трассировок
  - Изоляция проблем
  - Проверка корректности исправлений

- **Сопровождение**: исправление ошибок, добавление новой функциональности
  - Корректирующее сопровождение (исправление ошибок)
  - Адаптивное сопровождение (адаптация к изменениям окружения)
  - Совершенствующее сопровождение (улучшение характеристик)
  - Предупреждающее сопровождение (предотвращение проблем)

## Тема 8. СИСТЕМЫ ПРОГРАММИРОВАНИЯ

**Система программирования** — комплекс программных средств для разработки, отладки и сопровождения программ.

**История развития систем программирования:**
- **1940-1950-е годы**: Машинный код → появление ассемблеров
- **1950-е годы**: Появление первых языков высокого уровня (Fortran, COBOL, ALGOL)
- **1960-1970-е годы**: Структурные языки программирования (Pascal, C)
- **1980-1990-е годы**: Объектно-ориентированные языки (C++, Smalltalk)
- **1990-2000-е годы**: Визуальные среды разработки (Delphi, Visual Basic, Visual C++)
- **2000-2010-е годы**: Веб-ориентированные языки и фреймворки (Java, .NET, Python, Ruby)
- **2010-е годы и далее**: Интегрированные облачные среды разработки, языки для машинного обучения

**Классификация систем программирования:**
- **По парадигмам**:
  - **Процедурные** — основаны на концепции процедур и функций (C, Pascal)
  - **Объектно-ориентированные** — на основе понятия объектов и классов (C++, Java, C#)
  - **Функциональные** — основаны на применении функций (Lisp, Haskell, F#)
  - **Логические** — основаны на логических утверждениях и правилах вывода (Prolog)
  - **Мультипарадигмальные** — поддерживают несколько парадигм (Python, Scala)

- **По способу реализации**:
  - **Компиляторы** — переводят весь исходный код в машинный код до выполнения
    - Преимущества: высокая скорость выполнения, оптимизация
    - Примеры: C, C++, Fortran
  - **Интерпретаторы** — выполняют программу строка за строкой без предварительной компиляции
    - Преимущества: интерактивность, удобство отладки
    - Примеры: Python, Ruby, JavaScript
  - **Смешанные системы** — комбинируют компиляцию и интерпретацию
    - Преимущества: баланс между скоростью разработки и выполнения
    - Примеры: Java (JVM), .NET (CLR)

- **По назначению**:
  - **Универсальные** — для решения широкого спектра задач
    - Примеры: C++, Java, Python
  - **Специализированные** — для решения задач определенного класса
    - Примеры: MATLAB (математические вычисления), SQL (работа с базами данных), R (статистика)

**Состав системы программирования:**
- **Транслятор (компилятор или интерпретатор)**
  - Преобразует исходный код в машинный код или промежуточное представление
  - Выполняет лексический, синтаксический и семантический анализ
  - Оптимизирует код для повышения производительности

- **Редактор исходного текста**
  - Текстовый редактор со специализированными функциями для программирования
  - Подсветка синтаксиса, автодополнение, проверка синтаксиса в реальном времени
  - Навигация по коду, рефакторинг

- **Отладчик**
  - Позволяет пошагово выполнять программу
  - Устанавливать точки останова
  - Просматривать и изменять значения переменных
  - Отслеживать стек вызовов

- **Библиотеки стандартных подпрограмм**
  - Готовые функции и классы для решения типовых задач
  - Интерфейсы для работы с операционной системой
  - Структуры данных и алгоритмы

- **Документация и справочная система**
  - Руководство пользователя
  - Справочник по языку и библиотекам
  - Примеры и учебные материалы

- **Вспомогательные утилиты**
  - Профилировщик — анализ производительности
  - Генератор документации — создание документации по коду
  - Система контроля версий — управление изменениями в коде
  - Средства автоматического тестирования — проверка работоспособности кода

**Интегрированные среды разработки (IDE):**
- Объединяют все компоненты системы программирования в единый интерфейс
- Примеры: Visual Studio, IntelliJ IDEA, Eclipse, PyCharm, XCode

**Классификация языков программирования:**
- **По уровню абстракции**:
  - **Низкого уровня** — близки к машинному коду
    - Ассемблер — символическое представление машинных команд
    - Машинный код — двоичные команды процессора
  - **Высокого уровня** — абстрагированы от деталей аппаратной реализации
    - C++, Java, Python, JavaScript — ориентированы на решение задач, а не на особенности процессора

- **По парадигме**:
  - **Императивные** — описывают последовательность действий для достижения результата
    - Процедурные: C, Pascal, Fortran
    - Объектно-ориентированные: Java, C++, C#
  - **Декларативные** — описывают желаемый результат, а не способ его достижения
    - Функциональные: Lisp, Haskell, F#
    - Логические: Prolog
  - **Мультипарадигмальные**: Python, Scala, JavaScript

- **По области применения**:
  - **Универсальные**: C++, Java, Python — решение широкого спектра задач
  - **Специализированные**:
    - Веб-разработка: JavaScript, PHP, Ruby
    - Научные вычисления: MATLAB, R
    - Базы данных: SQL
    - Системное программирование: C, Rust
    - Встраиваемые системы: C, Ada

**Поколения языков программирования:**
- **Первое поколение (1GL)** — машинные языки (двоичный код)
- **Второе поколение (2GL)** — ассемблеры (символьное представление машинных команд)
- **Третье поколение (3GL)** — высокоуровневые языки (C, Pascal, Fortran)
- **Четвертое поколение (4GL)** — проблемно-ориентированные языки (SQL, MATLAB)
- **Пятое поколение (5GL)** — языки искусственного интеллекта (Prolog, Mercury) 