
## Посетитель (Visitor)

Паттерн Visitor относится к поведенческим паттернам уровня объекта.

Паттерн Visitor позволяет обойти набор элементов (объектов) с разнородными интерфейсами, а также позволяет добавить новый метод в класс объекта, при этом, не изменяя сам класс этого объекта.

Требуется для реализации:

1. Абстрактный класс Visitor, описывающий интерфейс визитера;
2. Класс ConcreteVisitor, реализующий конкретного визитера. Реализует методы для обхода конкретного элемента;
3. Класс ObjectStructure, реализующий структуру(коллекцию), в которой хранятся элементы для обхода;
4. Абстрактный класс Element, реализующий интерфейс элементов структуры;
5. Класс ElementA, реализующий элемент структуры;
6. Класс ElementB, реализующий элемент структуры.

## -~- THE END -~-
