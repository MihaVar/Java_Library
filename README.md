# Лабораторна робота 1 - Бібліотека

## Опис програми

Програма, написана мовою **Java**. Користувач має змогу керувати бібліотекою, а саме **додавати книжки, шукати книжки за назвою та видаляти книжки**, які мають наступні властивості:

- Назва;
- Автор;
- Номер ISBN;
- Рік видання.

## Опис роботи

1. Створити клас [Book], об'єкти в якому зберігатимуться у класі [Library];
2. Створити клас [Library], що буде керувати об'єктами з класу [Book];
3. Створити метод `toString()` для зручного виведення книг;
4. Покрити програму модульними тестами у класі [LibraryTest]:
- Тест на додавання книжок до бібліотеки;
- Тест на додавання дублікату книги;
- Тест на видалення книги;
- Тест на пошук книги за ISBN.
5. Продемонструвати вивід програми у класі [Main].

## Висновки

Під час виконання цієї лабораторної роботи я здобув навички розробки програм мовою Java.

[Book]: src/main/java/org/example/Book.java
[Library]: src/main/java/org/example/Library.java
[LibraryTest]: src/test/java/org/example/LibraryTest.java
[Main]: src/main/java/org/example/Main.java
