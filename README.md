# Здесь будет инструкция для пользователя
Лабораторные работы по машинному обучению магистратуры ПИ
## Этап 1. Скачать проект
Чтобы скачать проект целиком необходимо перейти в репозиторий по [данной](https://github.com/sirrorist/machine_learning_module_1) ссылке.

Затем нажать кнопку **<> Code**

<p align="left">
    <img src="https://github.com/sirrorist/machine_learning_module_1/blob/main/img/screen1.png?raw=true" alt="screen1.png" width="100%" height="100%" />
</p>

Далее нажать на кнопку **Download zip**, после чего начнётся загрузка проекта

<p align="left">
    <img src="https://github.com/sirrorist/machine_learning_module_1/blob/main/img/screen2.png?raw=true" alt="screen2.png" width="100%" height="100%" />
</p>

После того, как архив скачается, необходимо перейти в папку куда вы его скачали и извлечь содержимое (на скриншоте файлы извлекаются с помощью программы **WinRar**)

<p align="left">
    <img src="https://github.com/sirrorist/machine_learning_module_1/blob/main/img/screen3.png?raw=true" alt="screen3.png" width="100%" height="100%" />
</p>

В папке с извлеченным из архива проектом содержится: папка со скриншотами, файлы лабораторных работ с расширением .ipynb, используемые при работе с лабораторными таблицы с данными с расширением .csv

<p align="left">
    <img src="https://github.com/sirrorist/machine_learning_module_1/blob/main/img/screen4.png?raw=true" alt="screen4.png" width="100%" height="100%" />
</p>

## Этап 2. Загрузка проекта в Google Colab
*(Этап можно пропустить, если вы умеете открывать файлы с расширением .ipynb .)*

Для того чтобы начать работать с извлеченным проектом, необходимо определиться со средой разработки. В данном шаге будет рассмотрен [сайт](https://colab.research.google.com) **Google Colab**. Для начала перейдите по ссылке, приложенной сверху и в открывшемся окне нажмите кнопку **Войти**

<p align="left">
    <img src="https://github.com/sirrorist/machine_learning_module_1/blob/main/img/screen5.png?raw=true" alt="screen5.png" width="100%" height="100%" />
</p>

Далее, если у вас есть учетная запись Google, авторизируйтесь, или зарегистрируйтесь, если учетной записи у вас нет

<p align="left">
    <img src="https://github.com/sirrorist/machine_learning_module_1/blob/main/img/screen6.png?raw=true" alt="screen6.png" width="100%" height="100%" />
</p>

После входа в учетную запись, на [главной](https://colab.research.google.com/) странице Google Colab нажмите на кнопку **Файл**

<p align="left">
    <img src="https://github.com/sirrorist/machine_learning_module_1/blob/main/img/screen7.png?raw=true" alt="screen7.png" width="100%" height="100%" />
</p>

Затем в открывшемся меню нажмите **Загрузить блокнот**

<p align="left">
    <img src="https://github.com/sirrorist/machine_learning_module_1/blob/main/img/screen8.png?raw=true" alt="screen8.png" width="100%" height="100%" />
</p>

После чего в появывшемся окне нажмите кнопку **Загрузить** и после перехода на нужное окно нажмите на кнопку **Выберите файл**

<p align="left">
    <img src="https://github.com/sirrorist/machine_learning_module_1/blob/main/img/screen9.png?raw=true" alt="screen9.png" width="100%" height="100%" />
</p>

После чего найдите папку с извлеченным проектом и загрузите файлы с названиями

**1_1_Основы_работы_с_данными**

**1_2_Исследовательский_Анализ_Данных** 

**1.3_Линейная Регрессия** 

**1.4_Логистическая Регрессия** 

**1.5_Метод главных компонент и кластеризация к-средних**

Вы окажитесь на странице с загруженным проектом. Выберите тот проект, с которым вы хотите работать в данный момент. Если это первая лабораторная работа, то после перехода на его страницу можно добавить остальные файлы, для этого необходимо в левом боковом меню нажать на конпку **Папки**

<p align="left">
    <img src="https://github.com/sirrorist/machine_learning_module_1/blob/main/img/screen10.png?raw=true" alt="screen10.png" width="100%" height="100%" />
</p>

После чего в развернувшемся меню нажмите на иконку с изображением **файлы**

<p align="left">
    <img src="https://github.com/sirrorist/machine_learning_module_1/blob/main/img/screen11.png?raw=true" alt="screen11.png" width="100%" height="100%" />
</p>

Опять же, перейдите в папку с извлеченным проектом и выберите файл **cars_moldova.csv** и загрузите его

<p align="left">
    <img src="https://github.com/sirrorist/machine_learning_module_1/blob/main/img/screen13.png?raw=true" alt="screen13.png" width="100%" height="100%" />
</p>

## Этап 3. Работа с проектом

После того как вы настроили своё рабочее пространство, можно приступить к настройке проекта. Для работы с файлами необходимо размещать файлы, с которыми приходится работать, в одной папке, например, если вы работаете с первой лабораторной работой - переместите туда же базу данных с названием **cars_moldova.csv**, которую можно найти в папке с извлеченным проектом. Далее приступайте к работе с проектом. Чтобы инициировать работу конкретного участка кода, необходимо нажать на кнопку запуска:

<p align="left">
    <img src="https://github.com/sirrorist/machine_learning_module_1/blob/main/img/screen14.png?raw=true" alt="screen14.png" width="100%" height="100%" />
</p>

Если вам попадаются такие блоки

<p align="left">
    <img src="https://github.com/sirrorist/machine_learning_module_1/blob/main/img/screen15.png?raw=true" alt="screen15.png" width="100%" height="100%" />
</p>

Нажмите на пустые квадратные скобочки и интересующий вас код отобразится