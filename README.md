# Module-B3_Project-work-3
Модуль B3. Системы контроля версий (Git, SVN, Mercurial). Проектная работа 3

1) Ссылка на репозиторий

`https://github.com/ddenia/Module-B3_Project-work-3`

2) Для того чтоб склонировать репозиторий

`git clone https://github.com/ddenia/Module-B3_Project-work-3.git`

3) В git config настроить имя и электронную почту пользователя

`git config user.name  "Name"`

`git config user.email name@example.com`

4) Создать dev ветку 

`git branch dev-barnch`

5) Переключиться на dev ветку
 
`git checkout dev-barnch`

6) Все изменения в коде должны вноситься только в  dev ветках не в master или main 

5) Dev ветки должны создаваться интуитивно понятные на основе задач

6) Все необходимые изменения в master или main могут вноситься только через merge request на team leader

`git checkout master/main`

`git merge dev-barnch`

7) Если ветска больше не нужна ее можно удалить

`git branch -d dev-barnch`
