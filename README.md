# Создание Интелектуальных Систем

### Идея курса:
- Расширение курса ``Моя первая научная статья’’.
- Важна работа в командах — 2-3 человека.
- Eженедельная презентация работы команды за неделю: презентация с продвижением за неделю по проекту (5минут презентация + 5 минут обсуждение с другими людьми).

### Чекпоинты:
1. Исследование предметной области — анализ проблемы, выбор темы для исследования. (4я неделя)
2. Получение первых теоретических результатов. (7я неделя)
3. Подготовка эксперимента. (10я неделя)
4. Подготовка статьи. (13я неделя) 
5. Проект на гитхабе. (15я неделя) 

### Критерий к проекту:
1. Весь проект должен быть на GitHub под OpenSource лицензией (MIT)
2. Проект должен содержать код и инструкция по его запуску.
    1. Базовый код в jupyter notebook для демонстрации концепции работы и построения графиков из статьи — должен запускаться с colab.
    2. Исходный код вычислительного эксперимента должен запускаться на Unix системе выполнением двух команд (возможно в специльном docker образе):
        1. python3 train.py — для обучения моделей.
        2. python3 test.py — для тестирования, получения результатов эксперимента.
    3. Документация к коду — sphinx.
3. Проект должен содержать рукопись статьи используя стилевик от arXiv — для унификации.
4. Если проект подразумевает не синтетические данные, то должна быть инструкция для получения этих данных, а также скрипт для их получения. Если данные специфичные, то их требуется выложить на одном из файловых хранилищ.

### План лекции:
1. Вводная лекция.
2. Обсуждения проектов.
3. Правильная структура проекта.
4. Первый чекпоинт репозиторием.
5. Структура статьи.
6. Как правильно построить jupyter notebook.
7. Второй чекпоинт репозиторием.
8. Правильный код - код не в jupyter notebook!
9. О хранении данных для эксперимента.
10. Третий чекпоинт репозиторием.
11. Документация кода при помощи sphinx.
12. Докеризация кода эксперимента.
13. Четвертый чекпоинт репозиторием.
14. Проверка проектов и зачет.
