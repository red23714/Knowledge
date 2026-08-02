---
Используется:
  - "[[Литералы]]"
---
Nullptr — это зарезервированное слово для обозначения null pointer литерала, то есть безопасная замена макроса NULL из C. Главная особенность в том, что он типо-безопасный, то есть не обрабатывается компилятором как int или long как было с макросом NULL.

Обычно позволяет узнать точно, ссылается ли указатель на какое-то значение.

**Пример:**
```cpp
int main()
{
	int* ptr = nullptr;
	int x = 123;
	
	pointer = &x;
	
	if(pointer == nullptr)
	{
		std::cout << "address was not assigned";
	}
	else
	{
		std::cout << "address was assigned";
	}

	return 0;
}
```