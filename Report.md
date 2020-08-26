# Отчет о тестировании Credit Card Number Validator.

Начало установки IntelliJ IDEA: 26.08.2020, время 21.17 вечера.
Окончание установки IntelliJ IDEA: 26.08.2020, время 20.48 вечера.

Затраченное время на тестирование: 31 минута.

## По итогам тестирования были выявлены следующие деффекты:
Ошибки в работе программы с валидными номерми карт платежных систем American Express и Diners Club.
https://github.com/DimaVakarchuk/Home-Work-Java-2/issues/1#issue-686540956
https://github.com/DimaVakarchuk/Home-Work-Java-2/issues/2#issue-686546700


*В процессе тестирования использовалось*:

1. Руководство по установке IntelliJ IDEA.
2. Установочный файл jetbrains-toolbox-1.17.7391
3. Онлайн генератор карт https://www.freeformatter.com

*В качестве тестовых данных использовалось*:

1. Руководство по установке IntelliJ IDEA.
2. Случайные номера кредитных карт сгенерированные с помощью online сервиса (номера не реальные):
   * VISA 4290902923368292
   * VISA 4359302878562007
   * MasterCard 5391651470632197 
   * MasterCard 5462705498507023 
   * American Express 344039837800021 
   * American Express 372641852149682 
   * Diners Club 36030623830580
   

 
*Тестирование производилось в следующем окружении*:

 - Openjdk version "11.0.8"
 - IntelliJ IDEA
 - Windows 10 Pro (x64)