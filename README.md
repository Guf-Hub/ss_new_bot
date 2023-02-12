## Logistica бот

###Установка
`pip install --upgrade pip` - обновить pip
`pip install -r requirements.txt` - установить пакты в проект

Обновить все пакеты
* `pip freeze > requirements.txt` - создать файл requirements.txt
* открыть текстовый файл, заменить == на >=
* `pip install -r requirements.txt --upgrade`

###
…or create a new repository on the command line
* echo "# ss_new_bot" >> README.md
* git init
* git add README.md
* git commit -m "first commit"
* git branch -M main
* git remote add origin https://github.com/Guf-Hub/ss_new_bot.git
* git push -u origin main

…or push an existing repository from the command line
* git remote add origin https://github.com/Guf-Hub/ss_new_bot.git
* git branch -M main
* git push -u origin main