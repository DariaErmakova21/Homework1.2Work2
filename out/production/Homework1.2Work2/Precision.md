# Отчет о тестировании "Precision".

## Краткое описание

08.08.2021 - 08.08.2021 было проведено функциональное тестирование приложения Precision.

На тестирование потрачено время - 1 час.

В результате тестирования выявлены следующие дефекты:
* [Некорректная итоговая сумма регулярного и специального бонуса.](https://github.com/DariaErmakova21/Homework1.2Work2/issues/2)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Идея внедрения дополнительной бонусной системы 

В качестве тестовых данных использовались данные,предоставленные сотрудником компании:
* Регулярный бонус = 0.3, Специальный бонус 0.6
* Фрагмент кода,написанный разработчиком:

````
public class Main {
    public static void main(String[] args) {
        double regularBonus = 0.3;
        double specialBonus = 0.6;
        double totalBonus = regularBonus + specialBonus;
        System.out.println(totalBonus);
}
}
````
Тестирование производилось в следующем окружении:
* Windows 10 Pro, 64 - разрядная операционная система
* Java(TM) SE Development Kit 11.0.11 (64-bit)

