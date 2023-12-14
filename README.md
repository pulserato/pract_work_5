<h1 align="center">Описание<a href="https://daniilshat.ru/" target="_blank"></a> 
<img src="https://github.com/blackcater/blackcater/raw/main/images/Hi.gif" height="32"/></h1>
<h3 align="center">Здесь вы можете прочитать о реализации кода, который решает проблему гипотезы Коллатца </h3>

#### Краткое описание [**задачи**](https://ru.wikipedia.org/wiki/%D0%93%D0%B8%D0%BF%D0%BE%D1%82%D0%B5%D0%B7%D0%B0_%D0%9A%D0%BE%D0%BB%D0%BB%D0%B0%D1%82%D1%86%D0%B0), которую выполняет программа:
 *Эта программа генерирует последовательность Сиракуз для заданного числа и предоставляет возможность найти максимальное число в последовательности.*


### **Для запуска программы выполните следующие шаги:**


### 1. Установка Python:
* [ ] Проверьте, установлен ли Python на вашей системе, открыв командную строку или терминал и введя команду python --version.
* [ ] Если Python не установлен, перейдите на официальный веб-сайт Python (https://www.python.org) и загрузите и установите последнюю версию Python, совместимую с вашей операционной системой.

### 2.Клонирование репозитория:
* [ ] Перейдите на страницу репозитория с программой на GitHub.
* [ ] Нажмите на кнопку "Code" или "Код" и скопируйте URL репозитория.
* [ ] Откройте командную строку или терминал, перейдите в каталог (папку), в которую вы хотите клонировать репозиторий, и выполните команду git clone URL, заменив URL скопированным URL репозитория.

### 3.Запуск программы:
* [ ] Откройте терминал и перейдите в папку проекта, в которую вы только что клонировали репозиторий.
* [ ] Введите следующую команду: python syracuse.py (если вы используете Windows, возможно, вам нужно будет использовать команду python3 syracuse.py).

### 4.Использование программы:
После запуска программы вы увидите меню с вариантами.
Чтобы сгенерировать последовательность Сиракуз, выберите опцию "Сгенерировать последовательность Сиракуз" и введите положительное целое число. Последовательность будет выведена на экран.
Чтобы найти максимальное число в последовательности Сиракуз, выберите опцию "Найти максимальное число в последовательности Сиракуз" и введите положительное целое число. Максимальное число будет отображено.

## Программа отобразит меню с следующими вариантами:

* Сгенерировать последовательность Сиракуз: Введите положительное целое число, чтобы сгенерировать последовательность Сиракуз, начиная с этого числа. Последовательность будет выведена на экран.
* Найти максимальное число в последовательности Сиракуз: Введите положительное целое число, чтобы найти максимальное число в последовательности Сиракуз, начиная с этого числа. Максимальное число будет отображено.
* Выйти: Выберите этот вариант, чтобы выйти из программы.

## Примеры использования программы:

* Пример: получив на вход число 3, функция syracuse_sequence вернёт список [3, 10, 5, 16, 8, 4, 2, 1], а функция syracuse_max – 16

## Формула реализованная в программе:
if n is even number: 
$`n = {n \over 2}`$


else:
$`n = {3*n + 1}`$


## Графическое представление гипотезы Коллатца 
![График](https://www.google.com/url?sa=i&url=https%3A%2F%2Fforallxyz.net%2Fa-54&psig=AOvVaw3xEOEQw7l6IOeBpwtucH66&ust=1702634365704000&source=images&cd=vfe&opi=89978449&ved=0CBEQjRxqFwoTCMDcz7nVjoMDFQAAAAAdAAAAABAD)
