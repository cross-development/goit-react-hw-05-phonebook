# Homework 5 - Phonebook

## Структура проекта

### Папка src
Данная папка содержит: папку animation, папку components, файл index.js

### Папка animation
В папке animation хранятся файлы Vanilla CSS стилей монтирования/входа/выхода компонентов.

### Папка components
В папке components содержатся папки с компонентами, которые состоят из файла компонента и файла
css-модуля стиля. Имя компонента начинается с заглавной буквы в camelCase формате. 
Имя модуля начинается с заглавной буквы в camelCase формате с приставкой .module

### Содержание файла компонента
Основная структура файла компонента может включать:

- импорты Core (react, react-transition-group)
- импорты зависимых компонентов проекта (из папки components)
- импорты установленных утилит (uuid)
- импорты модулей стилей и стилей анимации
- объявление классового или функционального компонента

## Стили проекта 

### Стили анимаций
К анимациям монтирования/входа/выхода применяется подход Vanilla CSS. Все стили анимаций находятся в
папке animation с приставкой fade и именем компонента. Импортируется в компонент, где применяется
React Transition Group. В каждом файле анимации в комментариях описано в каком компоненте
используется стиль.

### Оформительные стили
К стилям оформления элементов компонента применяется подход CSS-модулей. Файл стиля находятся в
папке каждого компонента. Импортируется как объект стилей с именем styles без деструктуризации
свойств.
