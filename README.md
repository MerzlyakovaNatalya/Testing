
### Основные задачи:

1. Разделение комнонентов на презентационные и компоненты-контейнеры.

2. Работа с redux middlewares.
   Подключение библиотеки для middlewares - redux-thunk.
   redux-thunk использован для асинхронных действий.

3. Создание пользовательского хука.

4. Работа с компонентами высшего порядка (hoc) и connect.

5. Тестирование приложения с помощью Jest и React Testing Library

##### Вся основа приложения содержится в компоненте MessageContainer.

Компонент MessageContainer является связующем звеном между логикой (компоненты hoc, connect и hook) и визуальными компонентами.
