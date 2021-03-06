[![Build status](https://travis-ci.org/anton-bannykh/intro17.svg?branch=master)](https://travis-ci.org/anton-bannykh/intro17)

# Описание

Проект предназначен для ознакомления студентов первого курса с современными технологиями и инструментами разработки ПО.

# Инструкция

1. Настройка
  * Создайте issue с просьбой завести для вас ветку в основном проекте. Укажите транслитерацию вашего имени и фамилии.
  * Создайте `fork` этого проекта
  * Настройте окружение, научитесь запускать тесты
  * Добавьте файл `.gitignore`, скрывающий вспомогательный директории билд-системы [Gradle](https://gradle.org/)
  * Создайте pull request с этими изменениями в нужную ветку.
2. Первые шаги: простой метод и тесты к нему
  * Создай issue для получения алгоритма (например, сложение массива чисел).
  * Разработайте метод, реализующий этот алгоритм.
  * Разработайте тесты, проверяющий корректность работы полученного метода.
  * Создайте pull-request
3. Консольное приложение
  * Модифицируйте код `Main.java` таким образом, чтобы аргументы для алгоритма из задания 2 поступали командной строки, а выводились в стандартный вывод.
    Для примера из задания 2 запуск `java Main 1 2 3` должен вывести `6`.
  * В случае некорректного ввода программа должна выводить текст ошибки.
  * Разработайте тесты для кода, обрабатывающего некорректный ввод.
  * Создайте pull-request
4. Работа с Gradle
  * Выделите отдельно код алгоритма и код для обработки аргументов командной строки в отдельные пакеты (package).
  * Оформите эти пакеты как подпроекты Gradle (subproject).
  * Модифицируйте `build.gradle` таким образом, чтобы одним из артефактов являлся исполняемый `.jar` файл
  * Создайте pull-request.
5. Dependency injection
  * Создайте issue для получения варианта задания.
  * При помощи библиотеки [Guice] избавьтесь от зависимости кода, содержащего `main` на код алгоритма.
  * Выполните задание.
  * Разработайте тесты.
  * Создайте pull-request.

