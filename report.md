# **Краткое описание**

15.03.2021 было проведено функциональное тестирование приложения BigBankTheory.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:

* [При проведении операции подсчета выдается некорректный результат с периодической дробью](https://github.com/tanyaandre/java222/issues/1)

# **Описание процесса тестирования**

В процессе тестирования использовались следующие артефакты:

1. [Домашнее задание к занятию «1.2. Программирование на Java: переменные, операторы, работа с отладчиком»](https://github.com/netology-code/javaqa-homeworks/tree/master/programming)

В качестве тестовых данных использовались данные [Домашнего задания к занятию 1.2.](https://github.com/netology-code/javaqa-homeworks/tree/master/programming):

public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}

Тестирование производилось в следующем окружении:

Windows 8.1 x64
Java 11
IntelliJ IDEA Community Edition