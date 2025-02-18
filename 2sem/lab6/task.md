# ЛАБОРАТОРНАЯ РАБОТА «ФАЙЛОВЫЙ МЕНЕДЖЕР»

## Цель работы

Основной целью работы является развитие умений и навыков в создании комплексных программных проектов, а также в
освоении программного взаимодействия с файловой системой на языке Python.

## Задания для выполнения

Студентам необходимо разработать базовую версию файлового менеджера. Этот программный проект должен позволять
пользователю взаимодействовать с файлами и папками в заданной рабочей директории.

### Список требуемых функций включает:
- Создание и удаление директорий.
- Навигация по файловой системе внутри рабочей директории.
- Создание, чтение, запись, удаление, копирование, перемещение и переименование файлов.
- Пользовательский интерфейс должен быть текстовым и работать по принципу командной строки.

### Указания к выполнению
**Настройка рабочей директории:**
- Укажите путь к рабочей папке в конфигурационном файле проекта. Этот файл должен быть отдельным от основного кода.

**Ограничение действий:**
- Файловый менеджер должен предотвращать выход пользователя за пределы рабочей директории, тем самым создавая
  изолированное пространство для работы.

**Структура проекта:**
- Код должен быть структурирован и разделен на модули или классы, каждый из которых отвечает за определенную функцию
  файлового менеджера.

**Кроссплатформенность:**
- Программа должна корректно работать как в Windows, так и в UNIX-подобных системах. Используйте стандартную
  библиотеку Python для обеспечения совместимости.

**Использование Git:**
- Разработка должна проходить с использованием системы контроля версий Git, а результаты должны быть опубликованы в
  репозитории на GitHub.

**Дизайн команд:**
- Перед началом разработки необходимо тщательно спланировать набор и структуру команд, которые будут доступны
  пользователю. Стремитесь к оригинальности и избегайте копирования интерфейса существующих оболочек.

### Дополнительные задания
**Разработка псевдографического интерфейса:**
- Создайте улучшенный пользовательский интерфейс, используя элементы псевдографики, аналогичные тем, что
  используются в программных менеджерах файлов Far или Midnight Commander.

**Многопользовательский доступ:**
- Добавьте функционал для работы нескольких пользователей с файловым менеджером: регистрацию и автоматическое
  создание персональной директории для каждого.

**Расширение функционала:**
- Включите дополнительные возможности для работы с файлами и папками, такие как архивация, разархивация и квотирование
  дискового пространства.

### Ожидаемый результат
- Полностью функциональный файловый менеджер с текстовым интерфейсом.
- Отчет о проделанной работе, включающий описание каждой функции и принципов организации кода.
- Код, организованный в соответствии с лучшими практиками программирования и опубликованный на GitHub.
