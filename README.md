# ConvertNumToText

Тестовое задание для jazzTeam. Сделал Мальчихин Артем ***04.04.2019***

Основное Условие задания:<br> 

Перевод числа в цифровой записи в строковую. Например 134345 будет "сто тридцать четыре тысячи триста сорок пять".
* Учесть склонения - разница в окончаниях (к примеру, две и два).

* Алгоритм должен работать для сколько угодно большого числа, соответственно, значения степеней - миллион, тысяча, миллиад и т.д. - должны браться из справочника, к примеру, текстового файла.
* Обязательно создать Data Driven Test (я, как пользователь, должен иметь возможность ввести множество наборов 1.число 2.правильный эталонный результат, тест самостоятельно проверяет все наборы и говорит, что неверное), который доказывает, что Ваш алгоритм работает правильно. Использовать JUnit.
* По возможности, применить ООП.

# Описание папок:

* libFiles содержит файлы-библиотеки для работы

* DataForTest содержит файл для тестрования
* src/main/java/by/artem содержит java файл с основной логикой задания ConverterNumToText и java файл для запуска TryToWork
* src/test/java/by/artem содержит java файлы для Тестирования<br>
TestConverNumToText - проверяет работу основных значений на правильность,
TestConvertNumToTextFromTextFile - проверка перевода значений со значениями из файла.<br>
by.artem.TestDataProvider - класс с тестовыми данными.

# Исправленно 
***09.04.2019*** :
1. добавлен сборщик maven и некоторые библиотеки.
2. добален класс TestDataProvider.

3. исправленны ошибки согласно Java name convention
4. изменена структура папок. 

# Запуск
1. собрать проект через maven: mvn clean install
2. зайти в папку target через cmd и ввести java -jar TestForJazzTeam-1.0-SNAPSHOT.jar

3. или просто запустить через idea.