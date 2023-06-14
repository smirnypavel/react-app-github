# Проект на React.js с использованием RTK Query и Redux

Этот проект представляет собой пример приложения на React.js, которое использует API GitHub для поиска разработчиков и их репозиториев. Он также использует библиотеки RTK Query и Redux для управления состоянием приложения.

## Установка

Перед началом работы с проектом, убедитесь, что у вас установлен Node.js и npm (или yarn). Выполните следующие шаги:

1. Клонируйте репозиторий:

```bash
git clone https://github.com/smirnypavel/react-app.git

bash

2. Перейдите в папку проекта:

cd your-repo

3. Установите зависимости:

npm install
или
yarn install

```

Запуск

После установки зависимостей, вы можете запустить проект. Выполните следующую команду:

```bash
npm start
или
yarn start

Это запустит приложение в режиме разработки. Откройте http://localhost:3000 в вашем браузере, чтобы увидеть приложение.
```

прикольно

Функциональность

Приложение предоставляет следующую функциональность:

Поиск разработчиков по имени пользователя GitHub.
Отображение информации о найденных разработчиках, таких как имя, аватар и ссылка на их профиль GitHub.
Отображение списка репозиториев выбранного разработчика.
Возможность открыть репозиторий в новой вкладке.
Использование RTK Query и Redux

В этом проекте используется RTK Query для выполнения запросов к API GitHub и управления кэшированием данных. Redux используется для управления глобальным состоянием приложения.

Конфигурация RTK Query и Redux находится в файле src/app/store.js. Там вы найдете настройки сети, настройки RTK Query и создание Redux store.

Вклад и обратная связь

Если вы хотите внести вклад в проект или оставить отзыв, пожалуйста, создайте issue или pull request в репозитории. Мы всегда рады новым идеям и предложениям!

Лицензия

Этот проект лицензируется в соответствии с условиями лицензии MIT.

Примечание: Пожалуйста, замените `"https://github.com/your-username/your-repo.git"` на фактический URL вашего репозитория GitHub в строке клонирования репозитория.
