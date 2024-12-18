# Кейс 3. Автоматизация бизнес-процессов
_+ Открытая модель разработки_
<!-- 4 пары -->

<details> 
  <summary><h3>📚 Вводная информация</h3></summary>
  
  Перед началом выполнения кейса повторите следующий материал:

  * [Основы работы с Git и Github](https://disk.yandex.ru/d/D7r1TqNN3tzmHA)
  * [Работа со сторонними зависимостями](https://pyshkovni.github.io/python-base-course/part_2/site_package/)
  * [Настройка изолированной среды проекта](https://github.com/pyshkovni/programming-technologies-1/blob/main/python_ide/README.md#%D0%BD%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B9%D0%BA%D0%B0-%D1%81%D1%80%D0%B5%D0%B4%D1%8B-%D1%80%D0%B0%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B8-vs-code-git-%D0%B8-%D0%B8%D0%B7%D0%BE%D0%BB%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%BD%D0%B0%D1%8F-%D1%81%D1%80%D0%B5%D0%B4%D0%B0)

</details>

<details> 
  <summary><h3>📖 Условие кейса</h3></summary>
  
  В ряде случаев некоторые задачи являются рутинными. Например, менеджер маркетплейса должен перебирать картинки для карточек товаров вручную, что может занять очень много времени. Или юристу необходимо переоформить много документов, чтобы привести их к одному стилю. Гораздо проще воспользоваться готовым скриптом для решения подобной рутинной задачи. А такие задачи может помочь решить программист.

</details>

<details open> 
  <summary><h3>❗ Задание</h3></summary>

  **Часть 1**

  1. Сформируйте команды по 2 человека. Если у вас нет пары, то вы выполняете кейс с преподавателем.
  2. [Определите вариант проекта для группы](https://docs.google.com/spreadsheets/d/1NA14YElz6Jfmcqx8Wv3Jef1nThxuUeKgljbuVWBeqfk/edit?usp=sharing)
  3. Выберите файл согласно вашему варианту и скопируйте условие задачи.
      * [project_1.py](project_1.py)
      * [project_2.py](project_2.py)
      * [project_3.py](project_3.py)
      * [project_4.py](project_4.py)
      * [project_5.py](project_5.py)
      * [project_6.py](project_6.py)
  4. Организуйте работу в командах согласно следующим этапам:
      * Один их участников команды является _главным разработчиком_, другой является его _помощником_.
      * Главный разработчик создает репозиторий, в котором будет хранится исходный код решаемой задачи.
      * Помощник разработчика делает _форк_ репозитория главного разработчика, чтобы сделать часть своей работы в своем репозитории.
      * Главный разработчик и помощник должны реализовать _открытую модель разработки_, когда изменения в исходный код репозитория будут поступать с помощью _pull-request_ из сторонних репозиторием других разработчиков.
      * Внутри своих репозиториев главный разработчик и помощник выполняют задачу, оставляя коммиты в ветке `develop`, публикуя на ветку `main` рабочие изменения.

  **Требования к части 1**

  1. Репозиторий главного разработчика и реплицированный репозиторий помощника должны иметь минимум две ветки.
  2. Ветка `main` содержит рабочий релиз программы и должна быть всегда рабочей.
  3. Ветка `develop` может содержать недоработки, эксперименты и ошибки.
  4. Из ветки `develop` формируется релиз для ветки `main` с новыми изменениями.
  5. Каждый коммит обозначает выполненную задачу в работе.

  **Часть 2**

  Согласно выбранной задаче вам и вашему напарнику необходимо выполнить небольшой проект, который заключается в написании скрипта с использованием внешних модулей для автоматизации одного из рабочих процессов.

  **Требования к части 2**

  1. Проект должен быть опубликован на GitHub с описанием README.md.
  
  _Структура README.md_

  ```MarkDown
  # <Название проекта>

  ## Описание 
  
  что делает данный проект?

  ## Установка

  Как установить/начать работу?
  Какие пакеты скачать и как?

  ## Участники команды

  <Участник 1>
  <Участник 2>
  ```

  2. Скрипт проекта должен быть разбит минимум на два файла, одним из которых является `main.py`. 
  3. Второй файл (например `handlers.py`) содержит функции, которые выполняют поставленные действие (минимум, две функции).

[Ссылку на готовый проект необходимо прислать в форму](https://forms.yandex.ru/cloud/673d5dde3e9d087b85c4c8a3/)

  **Рекомендация**

  * В процессе выполнения задания обращайтесь к документации библиотеки, которой вам необходимо воспользоваться.
  
  Желаю удачи 🍀  
  За помощью обращайтесь к преподавателю!

</details>
