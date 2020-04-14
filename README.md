# HW08

1. Отреагируйте на фидбек, присланный вам в предыдущем задании.
   *  Исправьте баги.
   *  Если решите не вносить предложенные коллегами правки в синтаксис, напишите об этом.
2. Добавьте поддержку двумерного синтаксиса в сообщения об ошибках.
   * Для этого надо заменить `type Position = Int` на `type Position { line: Int, col: Int }` и правильным образом увеличивать координату в коде при переходе через разные символы.
   * Поддержите перенос строки `\n` и символ табуляции `\t`.
   * Напишите на это тесты для своего конкретного синтаксиса.
3. Добавьте определение функций и вызовы функций в конкретный синтаксис. Появились новые категории абстрактного синтаксиса `Program`, `Function`, конструкция возврата значения `Return` и `FucntionCall` в выражениях.
4. Реализуйте парсер для нового синтаксиса (`parseDef`, `parseProg`). Добавьте тесты на них.



# Замечания

* Написанные юнит-тесты должны проходить.
* Можно добавлять свои юнит-тесты.
* Можно изменять любой код, имеющийся в репозитории, при условии сохранения сигнатур имеющихся функций и юнит-тестов.
* Можно писать задание на любом другом языке, при условии максимального сохранения сигнатур функций, юнит-тестов и предоставление инструкций по сборке и запуску вашего проекта.

# Сборка и запуск

* `stack build` для сборки
* `stack test` для запуска тестов

# Мягкий дедлайн: 23:59 18.04

# Жесткий дедлайн: 23:59 20.04
