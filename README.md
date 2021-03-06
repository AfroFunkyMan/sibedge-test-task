# SibedgeTestTask

# Task description 
#### Приложение должно работать следующим образом:
1. При запуске приложения должен отображаться индикатор загрузки (реализовать через svg и @keyframes).
2. Приложение должно загрузить данные по адресу: http://jsteam.sibedge.com/raw/task/users.json и вывести их на страницу в виде таблицы.
3. По-умолчанию в таблице должно отображаться 10 строк, но должна быть реализована возможность указать сколько строк выводить. Реализовать в виде выпадающего списка из параметров: 10, 20, 30 строк. При смене значения данные в таблице должны пересчитываться.
4. Под таблицей реализовать возможность переключения по страницам. Количество страниц должно рассчитываться исходя из указанного количества строк и общего количества строк в данных.
5. Над таблицей реализовать фильтр из следующих полей:
  * Фамилия, текстовое поле
  * Телефон, числовое поле
  * Город, тестовое поле
  * Дата рождения, два поля “от” и “до”, можно использовать сторонние компоненты, типа datepicker
6. При смене одного из полей в фильтре данные в таблице должны пересчитываться исходя из введённых данных.
7. В фильтре должна быть кнопка “Сбросить”, которая очистит форму и вернет данные в таблице в исходный вид.
#### Требования к реализации
* Запрещено использовать сторонние компоненты, кроме фильтра дат.
* Требований к дизайну как таковых нет. Однако при оценке задания реализация верстки так же будет оцениваться. Тут есть простор для творчества. Разрешается использование фреймворков Angular Material или PrimeNG.

Результат необходимо прислать в виде папки zip с исходными файлами или выложить код на общедоступных площадках (Github, Bitbucket). К выполненному заданию необходимо приложить инструкцию по сборке/запуску проекта (в файле Readme.md).

#### Комментарии от разработчика
1. ```загрузить данные``` - не настроен CORS. Если планируется это ТЗ для джуна, то у него могут быть проблемы.
2.  ```Запрещено использовать сторонние компоненты``` и ```использование фреймворков Angular Material``` не много протеворечит друг другу. Ведь в Angular Material есть компоненты и для таблиц. Если ТЗ писалось для версии ниже 6-ой, то обновите ТЗ.
3. ```виде папки zip``` - считаю, что нужно использовать любой git. Лучше 3 дня, что вы даете, использовать для изучения гита.


## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).
