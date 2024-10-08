## Наиболее часто используемые типы данных в C++:
- int - целое число, занимает 4 байта
- char - символ в системе ASCII, занимает 1 байт
- bool - истина / ложь, 1 байт
- string - массив символов ( только с std::string )
- double - числа с плавающей точкой, прошлый float, занимает 8 байт
- void - undefined, обозначает пустой вывод
- wchar_t - wide char, символ, на который нужно больше места, 4 байта
- char16_t - символ Unicode
## Префиксы / постфиксы
- long - расширенный вариант другого типа данных
- unsigned - убирается бит, отвечающий за знак у числовых значений ( плюсовые )
### Примеры:
- unsigned long int

```cpp
ПЕРЕНЕСТИ В ТИПЫ
char a1 {'A'} // одно и то же (номер ASCII - 65)
char a2 { 65 }

wchar_t s {L's'} // символы больше 1 байта
```

```cpp
#include <string>
#include <iostream>

std::string number_to_string(int num) {
	return std::to_string(num);
};
```

**Связанное**
- [[Variables]]