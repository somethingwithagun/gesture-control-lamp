# Gesture Control Lamp  
# Лампа с управлением жестами

**EN:** A small portfolio project about recognizing hand gestures and using them to control a smart lightbulb.  
**RU:** Небольшой проект для портфолио: распознавание жестов рукой и управление умной лампочкой на их основе.

---

## About the project  
## О проекте

**EN:**  
This repository is a practical experiment at the intersection of computer vision, machine learning, and smart home interaction.  
The goal was simple: take a camera input, recognize a hand gesture, and convert it into a lamp action.

**RU:**  
Этот репозиторий - практический эксперимент на стыке компьютерного зрения, машинного обучения и управления умным домом.  
Идея была простой: получить изображение с камеры, распознать жест рукой и превратить его в действие для лампы.

---

## Why I made it  
## Зачем я это сделал

**EN:**  
I wanted a project that would be useful to show in a portfolio, but also feel personal and hands-on.  
Instead of building something abstract, I chose a familiar everyday scenario - turning a lamp on and off with gestures.

**RU:**  
Мне хотелось сделать проект, который было бы приятно показывать в портфолио, но который при этом оставался бы живым и прикладным.  
Вместо абстрактной задачи я выбрал понятный бытовой сценарий - включение и выключение лампы жестами.

---

## How the project evolved  
## Как развивался проект

**EN:**  
The work started in notebooks, where i tested ideas and gradually built everything step by step:

1. **Trying to connect to the lamp separately** - I ran into some trouble during this step because my router doesn't support widespread UDP broadcasting. Instead of a basic Wi-Fi scan, I had to retrieve the device information through the Tuya IoT Development Platform.
2. **Experimenting with models** - testing approaches for gesture recognition and comparing results.  
3. **Integration idea** - mapping recognized gestures to lamp actions.

As a result, I ended up with two notebooks, each showcasing a different approach to the problem and the entire development journey.

**RU:**  
Работа начиналась в ноутбуках, где я тестировал идеи и постепенно, шаг за шагом, выстраивал весь процесс:
1. **Попытка подключиться к лампе отдельно** - на этом этапе я столкнулся с трудностями, так как мой роутер не поддерживает широковещательную рассылку UDP (UDP broadcasting). Вместо обычного сканирования Wi-Fi мне пришлось получать информацию об устройстве через платформу разработки Tuya IoT.
2. **Эксперименты с моделями** - тестирование подходов к распознаванию жестов и сравнение результатов.
3. **Идея интеграции** - привязка (маппинг) распознанных жестов к действиям лампы.

В итоге получилось два ноутбука, в каждом из которых свой метод решения поставленной задачи и весь проделанный путь.

---

## Technologies used  
## Использованные технологии

**EN:**  
- **Jupyter Notebook** - for research, experimentation, and documenting the development process  
- **Python** - the main language for data processing and model work  
- **OpenCV** - to work with gesture images and visual input  
- **MediaPipe** - for landmark detection  
- **Smart device control (TinyTuya)** - for connecting recognition results to lamp behavior

**RU:**  
- **Jupyter Notebook** - для исследований, экспериментов и фиксации хода разработки  
- **Python** - основной язык для обработки данных и работы с моделью  
- **OpenCV** - работа с изображениями жестов и визуальным вводом  
- **MediaPipe** - для расставления ключевых точек
- **Управление smart-устройством (TinyTuya)** - чтобы связать распознавание с поведением лампы

---

## What I focused on  
## На что я делал упор

**EN:**  
- keeping the code understandable  
- making the notebook flow readable  
- testing ideas before locking into one solution  
- keeping the project practical, not overly theoretical

**RU:**  
- сделать код понятным  
- сохранить читаемую структуру ноутбуков  
- сначала проверять идеи, а потом фиксировать финальное решение  
- держать проект практичным, без лишней теории ради теории

---

## Result  
## Результат

**EN:**  
The result is a compact but complete project that shows both the technical process and the product idea behind it.  
This was a short story about how I implemented gesture control for my lamp.

**RU:**  
В результате получился компактный, но цельный проект, который показывает и техническую часть, и саму продуктовую идею.  
Это была небольшая история о том, как я реализовал жестовое управление для своей лампы.

---

## Notes  
## Заметки

**EN:**  
This repository is notebook-based, so the development process is visible directly in the code and cells.  
That was intentional: I wanted the project to feel like a working notebook (like data storytelling).

**RU:**  
Этот репозиторий построен на ноутбуках, поэтому ход разработки видно прямо в коде и ячейках.  
Это было сделано специально: мне хотелось, чтобы проект ощущался как рабочий ноутбук, со своим сюжетом (как data storytelling) 

---

## Future improvements  
## Что можно улучшить дальше

**EN:**  
- make gesture recognition more robust in different lighting conditions  
- add a more polished interface for controlling the lamp  

**RU:**  
- сделать распознавание жестов устойчивее к разному освещению  
- добавить более аккуратный интерфейс управления лампой  

---