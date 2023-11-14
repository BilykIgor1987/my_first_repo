Быстрая настройка — 
https://github.com/BilykIgor1987/*Название репозитория*.git

Начните с создания нового файла или загрузки существующего файла. Мы рекомендуем каждому репозиторию включать в себя README, ЛИЦЕНЗИЮ и .gitignore.

... или создайте новый репозиторий в командной строке

echo "# POSOW" >> README.md     *создаем файл README*
git init                        *инициализация репозитория на ПК*
git add README.md               *добавили в отслеживание файл README*
git commit -m "first commit"    *добавили первый коммит*
git branch -M main              *переименовали ветку в "main"*
git remote add origin https://github.com/BilykIgor1987/POSOW.git    *связали папку на ПК с папкой на GitHub*
git push -u origin main         *отправили ветку "main" в репозиторий на GitHub*

... или запустите существующий репозиторий из командной строки

git remote add origin https://github.com/BilykIgor1987/POSOW.git
git branch -M main
git push -u origin main