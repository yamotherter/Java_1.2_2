# # Отчёт о тестировании кода расчёта скидок

## Краткое описание

28.07.2021 - 28.07.2021 было проведено тестирование расчёта скидок в программе IntelliJ IDEA

На тестирование затрачено: 10 минут.

В результате тестирования дефектов не выявлено.

## Описание процесса тестирования

В качестве тестовых данных использовался кусок кода, написанный программистами:

public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}

Тестирование производилось в следующем окружении:

* MacOs Big Sur 11.04
* Openjdk version "11.0.11"
* IntelliJ IDEA
