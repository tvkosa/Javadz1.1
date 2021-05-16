# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

15.05.2021 - 15.05.2021 было проведено дымовое тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1.5 часа

В результате тестирования выявлены следующие дефекты:
* [Не проходят валидацию номера карт Diners Club - Carte Blanche из 14-ти знаков](https://github.com/tvkosa/Javadz1.1/issues/1#issue-892633053)
* [Не проходят валидацию номера карт American Express (AMEX) из 15-ти знаков](https://github.com/tvkosa/Javadz1.1/issues/2#issue-892633896)
* [Не проходят валидацию номера карт VISA, Discover, JCB из 19-ти знаков](https://github.com/tvkosa/Javadz1.1/issues/3#issue-892634651)




## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)
* [Генератор валидных номеров карт на сайте freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html#validate)


В качестве тестовых данных использовались номера валидных карт сгенерированные на сайте freeformatter.com:
* 14-значные номера карт Diners Club - Carte Blanche:
  
  30491248827698
  
  30276209112606
  
  30564201366647


* 15-значные номера карт American Express (AMEX):
  
  341206866836845
  
  343788702652401
  
  344206603518976


* 19-значные номера карт:
  
  VISA - 4916058163987856689
  
  Discover - 6011479302070858918
  
  JCB - 3543428400585182589


Тестирование производилось в следующем окружении:
* Windows 10 Домашняя, 64-разрядная ОС
* Java 11.0.10
* IntelliJ IDEA 2021.1.1
