# Webpack React

# Структура

```
/src
├── /components (только UI)
│ ├── /atoms # Минимальные, независимые компоненты (кнопки, иконки, инпуты)
│ ├── /molecules # Компоненты, состоящие из нескольких атомов (форма, карточка)
│ ├── /organisms # Более сложные части UI (хедер, модальное окно, список)
│ ├── /templates # Шаблоны страниц, включающие в себя organisms и layout
│ ├── /pages # Полные страницы, состоящие из шаблонов и логики роутинга
├── /routes # Настройки роутов
├── /store # Глобальное состояние
├── /services # Логика API-запросов
├── /hooks # Переиспользуемая логика
├── /utils # Утилитарные функции/хелперы
├── /styles # Глобальные стили и переменные
├── App.tsx # Корневой компонент приложения
├── index.tsx
```
