# Отчет о тестировании бонусной системы #

## Краткое описание ##

12.03.2021 г. было проведено Функциональное тестирование счета VIP-клиента.

На тестирование затрачено: *1 час*

## В результате тестирования выявлены следующие дефекты: ##

#### Некорректное отражение итоговой суммы бонусов ####
[Некорректная сумма бонусов на счете клиента при зачислении](https://github.com/Alex-isk/HW-J-1.2-2/issues/1)


## Описание процесса тестирования ##

В процессе тестирования использовались следующие артефакты:
 
[Код](https://github.com/Alex-isk/HW-J-1.2-2/blob/main/src/Main.java)


1. ### Шаг ### 


Запустить код

* Ожидаемый результат (ОР):

Итоговая сумма (totalBonus) - 0,9

* Фактический результат:

Не соответствует ОР

[Некорректная сумма бонусов на счете клиента при зачислении](https://github.com/Alex-isk/HW-J-1.2-2/issues/1)

### Тестирование производилось в следующем окружении: ###

* macOS Catalina версия 10.15.7 
* IntelliJ IDEA 2020.3.2 (Community Edition)
Runtime version: 11.0.9.1+11-b1145.77 x86_64
VM: OpenJDK 64-Bit Server VM by JetBrains s.r.o.
