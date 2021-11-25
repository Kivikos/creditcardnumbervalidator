# Отчёт о тестировании приложения Credit Card Number Validator
## Программа применяется для валидации номера банковской карты. 
24.11.2021 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Дефект №1](https://github.com/Kivikos/creditcardnumbervalidator/issues/1#issue-1063161978)

## Описание процесса тестирования

### В процессе тестирования использовались следующие артефакты:
* Спецификация ПО Credit Card Number Validator

### В качестве тестовых данных использовались данные из [генератора номера банковских карт](https://www.freeformatter.com/credit-card-number-generator-validator.html):
* Visa: 4929045579355251
* MasterCard: 5567998188032634
* American Express (AMEX): 371560101229924
* Discover: 6011342034945600
* JCB: 3542954169668446
* Diners Club - North America: 5436203530894115
* Diners Club - Carte Blanche: 30362079784326
* Diners Club - International: 36667573063009
* Maestro: 5038315908720698
* Visa Electron: 4844632309598789
* InstaPayment: 6387593179548429

### Тестирование производилось в следующем окружении:
* ОС: Windows 11 x64 21H2 22000.318
* IDE: IntelliJ IDEA 2021.2.3 build 212.5457.46
* Версия Java: Java SE 11.0.12 LTS
* Ссылка на исходники проекта на GitHub: https://github.com/Kivikos/creditcardnumbervalidator.git