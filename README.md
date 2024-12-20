# Architect Blog

Architect Blog — это двухстраничный блог, состоящий из двух частей:

- **Фронтенд** (React, Next.js) — клиентская часть, доступная по адресу [http://localhost:3000](http://localhost:3000).
- **Бэкенд** (Strapi) — серверная часть, доступная по адресу [http://localhost:1337](http://localhost:1337).

## Демо

Вы можете ознакомиться с демо-версией проекта, где используется только фронтенд (без Strapi):  
[Architect Blog Demo](https://rina2316.github.io/Architect/)

## Особенности

- **Главная страница** с отображением всех статей.
- При клике на статью раскрывается ее содержимое.
- Проект состоит из двух частей: фронтенд на **React** и **Next.js**, и сервер на **Strapi**.
- Для полноценной работы требуется настроить и запустить как фронтенд, так и бэкенд.

## Установка

Для начала работы с проектом, вам нужно будет установить как фронтенд, так и бэкенд.

### Клонирование репозитория

Клонируйте проект на ваш локальный компьютер:

```bash
git clone https://github.com/Ваше_имя/Architect-blog.git
cd Architect-blog
```

### Настройка и запуск Бэкенда (Strapi)

1. Перейдите в папку **backend**:

    ```bash
    cd backend
    ```

2. Установите зависимости:

    ```bash
    npm install
    ```

3. Запустите сервер:

    ```bash
    npm run develop
    ```

    Бэкенд будет доступен по адресу [http://localhost:1337](http://localhost:1337).

### Настройка и запуск Фронтенда

1. Перейдите в папку **frontend**:

    ```bash
    cd frontend
    ```

2. Установите зависимости:

    ```bash
    npm install
    ```

3. Запустите сервер:

    ```bash
    npm run dev
    ```

    Фронтенд будет доступен по адресу [http://localhost:3000](http://localhost:3000).

## Использование

1. Перейдите на главную страницу, чтобы просмотреть список всех статей.
2. Для чтения полной статьи нажмите на её название.
3. Демо-версия без Strapi доступна на [Architect Blog Demo](https://rina2316.github.io/Architect/), но для полноценного функционала необходимо запустить и настроить бэкенд.
