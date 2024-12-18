# Интересные места в Алуште

Этот проект представляет собой веб-приложение, отображающее интересные места в Алуште. Реализована функция фильтрации мест по категориям и отображения подробной информации о каждом месте через модальное окно.

## Содержание

- [Начало работы](#начало-работы)
- [Файловая структура](#файловая-структура)
- [Использование](#использование)
- [Поддержка](#поддержка)

## Начало работы

Эти инструкции помогут вам запустить копию проекта на вашем локальном компьютере для разработки и тестирования.

### Установка

1. Клонируйте репозиторий:
    ```sh
    git clone https://github.com/ваш-логин/ваш-репозиторий.git
    ```
2. Перейдите в директорию проекта:
    ```sh
    cd ваш-репозиторий
    ```
3. Убедитесь, что все необходимые файлы находятся на своих местах.

## Файловая структура

- **index.html**: Основной HTML-файл, отображающий веб-страницу.
- **static/styles.css**: Файл стилей CSS для веб-страницы.
- **controller/placecontroller.go**: Файл, содержащий контроллер для обработки запросов и взаимодействия с HTML-шаблонами.
- **model/place.go**: Структура данных для описания мест.
- **model/placeservice.go**: Файл, отвечающий за загрузку данных о местах и фильтрацию по категориям.
- **main.go**: Главный файл для запуска веб-сервера.
- **places.json**: JSON-файл, содержащий данные о местах.

## Использование

После клонирования репозитория и размещения файлов на GitHub Pages, вы можете открыть веб-страницу в браузере и взаимодействовать с ней:

1. Кнопки навигации позволяют фильтровать места по категориям.
2. Щелкните на карточку места, чтобы открыть модальное окно с подробной информацией.
3. Закрыть модальное окно можно нажатием на "×".

## Поддержка

Если у вас возникли вопросы или вы нашли баги, пожалуйста, создайте issue в репозитории.



