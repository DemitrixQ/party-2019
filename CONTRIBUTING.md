# Правила участия в мероприятии

## Содержание

- [Code of Conduct](#code-of-conduct)
- [Зарегистрироваться как участник на Hacktoberfest](#0.-зарегистрироваться-как-участник-на-hacktoberfest)
- [Сделать форк репозитория](#1.-сделать-форк-репозитория)
- [Клонировать репозиторий на компьютер](#2.-клонировать-репозиторий-на-компьютер)
- [Добавить информацию о себе](#3.-добавить-информацию-о-себе)
    - [Добавить фото](#добавить-фото)
    - [Добавить описание](#добавить-описание)
- [Commit & Push](#4.-commit-&-push)
- [Pull Request](#5.-pull-request)
- [Ура](#6.-ура)


## Code of Conduct

Участвуя в мероприятии, вы подтверждаете, что согласны с условиями [Hacktoberfest Events Code of Conduct](https://do.co/hacktoberconduct).

Для того, чтобы присоединиться, необходимо выполнить следующие шаги:

## 0. Зарегистрироваться как участник на Hacktoberfest

Перейдите на страницу [Hacktoberfest](https://hacktoberfest.digitalocean.com/) и зарегистрируйтесь как участник, нажав "START HACKING". Войдите, используя свой аккаунт GitHub. Если его еще нет, зарегистрируйте его на сайте [GitHub](https://github.com/join).

## 1. Сделать форк репозитория

Зайдите на страницу https://github.com/Hacktoberfest-Voronezh/party-2019 и нажмите кнопку "Fork" в правом верхнем углу. [Подробнее о том, как это сделать](https://guides.github.com/activities/forking/).

## 2. Клонировать репозиторий на компьютер

На странице созданного форка нужно нажать зеленую кнопку "Clone or download" справа и скопировать ссылку вида `https://github.com/<github-username>/party-2019.git`, где вместо `<github-username>` будет имя вашего пользователя на Github.

Далее необходимо перейти на компьютере в директорию, где вы планируете держать файлы проекта (потом их можно удалить) и выполнить команду

```bash
git clone <path>
```

И вместо `<path>` подставить скопированную ссылку.

Git создаст директорию `party-2019` и скопирует в нее проект из форка.

## 3. Добавить информацию о себе

Для этого нужно сделать следующее:

### Добавить фото

Добавляем фото в папку 'images'. Назовите его `имя-фамилия.jpg` или `имя-фамилия.png`, где имя-фамилия - ваши имя и фамилия латиницей.

Например, `ilya-kaznacheev.jpg`.

Фото желательно небольшого размера, 300х300 вполне будет достаточно.

### Добавить описание

Дальше необходимо добавить информацию о себе. Для этого необходимо открыть на редактирование файл `README.md` из корневого каталога проекта и найти раздел "Участники". В разделе представлена таблица участников, в конец ее нужно добавить одну строку вида

```
| <Имя Фамилия> | ![](/images/имя-фамилия.jpg) | Краткая информация о себе | [github-username](https://github.com/github-username) |
```

Соответственно вместо `<Имя Фамилия>` должны быть ваши имя и фамилия.

В следующем столбце нужно добавить путь к изображению (то, что добавили на предыдущем шаге) относительно корня прокета.

Далее напишите информацию о себе - то, что вы считаете другим было бы интересно знать о вас, как об участнике open source сообщества Воронежа.

В последнем столбце нужно указать ссылку на свой профиль на GitHub - вместо `github-username` укажите свой настоящий username.

## 4. Commit & Push

Далее необходимо отправить изменения в форк проекта на гитхаб. Для этого делаем следующее:

```bash
git add --all
git commit -m "Add participant info"
git push
```

Данный набор команд добавит изменения в коммит и отправит его на сервер GitHub.

## 5. Pull Request

Чтобы отправить запрос на добавление ваших изменений в проект, необходимо создать Pull Request (PR). Зайдите на страницу вашего форка - после загрузки изменений там появится кнопка "Compare & pull request". Нажмите ее.

Вы попадете на страницу создания нового PR. В названии укажите свои имя и фамилию. Описание на ваше усмотрение. После необходимо нажать "Create pull request" - и ваш первый PR создан.

## 6. Ура

Вы на шаг ближе к победе. Посмотреть свой статус можно на странице [своего профиля](https://hacktoberfest.digitalocean.com/profile).