# Отчёт о тестировании приложения "KeyValidator"

## Краткое описание
 20.11.2020 было проведено функциональное тестирование приложения KeyValidator. 
 На тестирование было потрачено 1 час. 
 Было введено 5 валидных и 5 невалидных ключей для проверки корректной работы приложения.
 
 В результате тестирования выявлены следующие дефекты: 
 [Некорректная_валидация_ключей_при_вводе](https://github.com/AleksandraArt/hwjava/issues/1)

## Описание тестов
Было проведено позитивное и негативное функциональное тестирование приложения, а именно  функции проверки лицензионных ключей.
Тестирование осуществлялось на Java 11.

## Результаты
В ходе тестирования выведено 70% успешных и 30% не успешны тестов.

Ссылка на баг-репорт:
[Некорректная_валидация](https://github.com/AleksandraArt/hwjava/issues/1)

## Общие рекомендации
Следует произвести доработку функции приложения принятия валидных и искючения принятия невалидных ключей.