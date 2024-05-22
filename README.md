# Модуль фитнес-трекера

### Описание проекта и используемые технологии

Программный модуль написан на Python3.9.

Программа обрабатывает данные для трёх видов тренировок: бега, спортивной ходьбы и плавания.
Для проверки работоспособности фитнес-трекера используются заранее подготовленные тестовые данные (пакеты данных) в виде кортежа.

**Этот модуль выполняет следующие функции:**

* принимает от блока датчиков информацию о прошедшей тренировке,
* определяет вид тренировки,
* рассчитывает результаты тренировки,
* выводит информационное сообщение о результатах тренировки.

**Информационное сообщение включает такие данные:**

* тип тренировки (бег, ходьба или плавание);
* длительность тренировки;
* дистанция, которую преодолел пользователь, в километрах;
* среднюю скорость на дистанции, в км/ч;
* расход энергии, в килокалориях.

### Как запустить проект:
Клонировать репозиторий и перейти в него в командной строке:
```
git clone https://github.com/miscanth/hw_python_oop.git
```
```
cd hw_python_oop
```
Cоздать и активировать виртуальное окружение:
```
python3 -m venv venv
```
```
source venv/bin/activate
```
Установить зависимости из файла requirements.txt:
```
python3 -m pip install --upgrade pip
```
```
pip install -r requirements.txt
```
Запустить проект:
```
python3.9 homework.py
```

## Разработчик (исполнитель):
👩🏼‍💻 Юлия: https://github.com/miscanth
