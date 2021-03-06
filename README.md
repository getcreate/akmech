# StartKit for Stylus
## Особенности
- Cборка предназначена для автоматизации задач в повседневной front-end разработке
- Основой для данной сборки является [BEM](https://ru.bem.info "BEM") методология
- Поддержка [npm](https://www.npmjs.com "npm") и [yarn](https://yarnpkg.com/ru/ "yarn")
- Используется препроцессор [Stylus](http://stylus-lang.com "Stylus")
- Встроенная сетка для адаптивной вёрстки [Smart-Grid](https://github.com/dmitry-lavrik/smart-grid "Smart-Grid")

## Установка
* **Установка для NPM**
1. Скачайте и установите [Node.js](https://nodejs.org/en/ "Node.js") последней версии
2. Установите [Gulp](https://gulpjs.com "Gulp") глобально:
    ```
	npm i gulp-cli -g
	```

3. Установите [Bower](https://bower.io "Bower") глобально:
    ```
	npm i bower -g
	```
	
4. Установите все зависимости:
    ```
	npm i
	```
	
5. Запустите gulp:
	```
	gulp
	```

------------


* **Установка для Yarn**
1. Скачайте и установите [Yarn](https://yarnpkg.com/ru/ "Yarn") последней версии
2. Установите [Gulp](https://gulpjs.com "Gulp") глобально:
    ```
	yarn global add gulp-cli
	```

3. Установите [Bower](https://bower.io "Bower") глобально:
    ```
	yarn global add bower
	```
	
4. Установите все зависимости:
    ```
	yarn
	```
	
5. Запустите gulp:
	```
	gulp
	```
	
## Файловая структура
```
StartKit-Stylus
├── data
├── gulp
├── public
├── resources
├── source
│   ├── blocks
│   ├── fonts
│   ├── pages
│   ├── pictures
│   ├── scripts
│   └── styles
├── .bowerrc
├── .csscomb.json
├── .gitignore
├── bower.json
├── gulpfile.js
└── package.json
```# akmech
