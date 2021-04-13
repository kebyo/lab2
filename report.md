# Отчет по лабораторной работе №2

### Первый студент заводит репозиторий, второй делает в нее Pull request.

1. Репозиторий: https://github.com/kebyo/lab2/tree/master
2. Pull Request: https://github.com/kebyo/lab2/pull/1

### Создание веток по модели GitFlow - https://danielkummer.github.io/git-flow-cheatsheet/index.ru_RU.html - Обязательное наличие веток фич, релиз, девелоп, хот фикс.

1. Установка:

   `brew install git-flow-avh`


2. Инициализация:
   
   `git flow init`


3. Ветки:
![img.png](assets/img_1.png)

### В репозитории обязательно оформлен README.md
![img_1.png](assets/img.png)
    
### Наличие тегов
Использовали команды:
* `git flow release start <version>`
* `git flow release finish <version>`
* `git flow release publish <version>`

![img.png](assets/img_2.png)


### Submodules

Использовали команду:

`git submodule add https://github.com/kebyo/ITMO-Software-development-tools`

![img_3.png](assets/img_3.png)

Появился конфиг `.gitmodules`:


```
[submodule "ITMO-Software-development-tools"]
	path = ITMO-Software-development-tools
	url = https://github.com/kebyo/ITMO-Software-development-tools
```

### LFS:
```
*.mp3 filter=lfs diff=lfs merge=lfs -text
```

### Авторы:
* Ойбек Муслимов М3202 ([@kebyo](https://github.com/kebyo))
* Илья Рогулин М3204 ([@ilushaR](https://github.com/ilushaR))
