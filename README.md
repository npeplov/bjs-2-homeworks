# Домашние задания по курсу «Основы Javascript»

#### 0. [Основы отладки](./0.debugger/)

#### 1. [Основные понятия](./1.base-concepts/)

#### 2. [Функции](./2.functions/)

#### 3. [Массивы](./3.arrays/)

## Требования

- браузер (лучше всего подойдет Google Chrome или Яндекс.Браузер);
- редактор кода, например [Sublime][1] или [Visual Studio Code][2];
- аккаунт на [GitHub][0] ([инструкция по регистрации на GitHub][3]);
- система контроля версий [Git][4], установленная локально ([инструкция по установке Git][5]);

## Перед началом работы над проектом

1. Произведите [Fork][0] репозитория с задачами.

После перехода на страницу с домашним заданием из личного кабинета в правом верхнем углу экрана нажмите на кнопку `Fork`. На экране появится окно с выбором предпочтительного репозитория для клонирования проекта. Выбираете ваш аккаунт и после непродолжительного ожидания вы будете перенаправлены на страницу репозитория на вашем аккаунте.

URL адрес этой страницы будет являться URL адресом вашего репозитория. Пример URL адреса репозитория:
`https://github.com/%username%/bjs-homeworks`, где `%username%` - имя вашего профиля GitHub, `%bjs-homeworks%` - название репозитория.

2. Скопируйте URL текушей страницы.
3. Перейдите в папку (директорию) на вашем компьютере, где будет храниться проект.
4. С помощью терминала, командной строки вашей операционной системы или консоли Git (ПКМ -> `GitBash Here`) откройте выбранную вами директорию.
5. Склонируйте репозиторий с домашними заданиями с помощью команды `git clone https://github.com/%username%/bjs-homeworks` в открывшемся терминале или командной строке.
6. Перейдите в директорию склонированного репозитория `cd ./bjs-homeworks`.

## Работа над каждым домашним заданием состоит из нескольких этапов

1. Ознакомьтесь с правилами отладки. Данная [инструкция](./1.0-debugger/README.md) входит в проект.
2. Ознакомьтесь с папкой задания. В каждой папке находится несколько файлов:
   1. `README.md` - файл с описанием домашнего задания.
   2. `index.html` - файл с разметкой, где можно вводить данные и проверять работу кода.
   3. `main.js` - файл, который взаимодействует со страницей в файлом домашнего задания.
   4. `task.js` - файл, для реализации домашнего задания. **Домашние задания выполняются в этом файле.**
   5. `tests.js` - файл с тестами.
   6. `test-runner.html` - файл, запускающий тесты.
3. Ознакомьтесь и реализуйте задания.
4. Код из домашних заданий можно вызывать как из консоли, так и со страницы.
5. Проверьте работу ваших заданий, запустив тесты jasmine (открыв файл `test-runner.html`).
6. В случае успеха прохождения тестов можно сдавать задание.

**!ВНИМАНИЕ!** - Прохождение тестов не означает полностью правильную реализацию домашнего задания. Тесты проверяют правильность вычисления задания, но не чистоту кода и правильность требований домашнего задания.

## Решение задач

1. Перейдите в папку задания, например, для первого задания `cd ./base-concepts`.
2. Откройте файл `task.js` в вашем редакторе кода и выполните задание.
3. Откройте файл `index.html` в вашем браузере и с помощью консоли DevTools убедитесь в правильности выводимых результатов.
4. Добавьте файл `task.js` в индекс git с помощью команды `git add %file-path%`, где `%file-path%` - путь до целевого файла, например, для первого задания `git add task.js`.
5. Сделайте коммит, используя команду `git commit -m '%comment%'`, где `%comment%` - это произвольный комментарий к вашему коммиту, например, для первого задания `git commit -m 'first commit variables'`.
6. Опубликуйте код в репозиторий homeworks с помощью команды `git push -u origin master`.
7. Пришлите ссылку на репозиторий через личный кабинет на сайте [Нетологии][6].

[0]: https://ru.wikipedia.org/wiki/%D0%A4%D0%BE%D1%80%D0%BA
[1]: https://www.sublimetext.com/
[2]: https://code.visualstudio.com/
[3]: https://github.com/netology-code/guides/tree/master/github
[4]: https://git-scm.com/
[5]: https://github.com/netology-code/guides/blob/master/git/README.md
[6]: https://netology.ru/
.