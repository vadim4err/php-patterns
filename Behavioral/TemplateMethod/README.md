
## Шаблонный метод (Template Method)

Паттерн Template Method относится к поведенческим паттернам уровня класса.

Паттерн Template Method формирует структуру алгоритма и позволяет в производных классах реализовать, перекрыть или переопределить определенные шаги алгоритма, не изменяя структуру алгоритма в целом.

Проектировщик решает, какие шаги алгоритма являются неизменными, а какие изменяемыми. Абстрактный базовый класс реализует стандартные неизменяемые шаги алгоритма и может предоставлять реализацию по умолчанию для изменяемых шагов. Изменяемые шаги могут предоставляться клиентом компонента в конкретных производных классах.

Требуется для реализации:

1. Абстрактный класс AbstractClass, реализующий Template Method, который описывает порядок действий;
2. Класс ConcreteClass, реализующий изменяемые действия.

## -~- THE END -~-