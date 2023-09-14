# Курс "Системы Искусственного Интеллекта" Самарского Университета 

Курс основывается на работах учёных [Института Искусственного Интеллекта](https://ai.ssau.ru/) Самарского Университета: д.т.н., [Артем Владимирович Никоноров](https://ssau.ru/staff/66320001-nikonorov-artem-vladimirovich), [Виктория Витальевна Евдокимова](https://ssau.ru/staff/304968209-evdokimova-viktoriya-vitalevna/edu), [Никита Александрович Фирсов](https://ssau.ru/staff/441332557-firsov-nikita-aleksandrovich/edu). Видеозаписи лекций материнского курса можно найти на youtube канале [Никонорова А.В.](https://www.youtube.com/@artemnikonorov5601)
В свою очередь, большое количество материалов взято из более обзорных лекциях и туториалах по глубокому обучению и его приложениях, в частности, вот [небольшая обзорная лекция](https://youtu.be/Gpq1PFUee88) в Кавказском Математическом Центре. Также во многом этот курс является адаптацией известнейшего курса [http://cs231n.stanford.edu/](https://cs231n.github.io/)  

Материалы курса за 2020-21 годы расположены [здесь](https://github.com/Daikon46/AISys_SamU/tree/main/Presentations/2020-21) и 2022-2023 [здесь](https://github.com/Daikon46/AISys_SamU/tree/main/Presentations/2022-23).  

## График проведения курса 2023-2024
TBA  

## Лекционный план 2023-2024  

**Часть первая. Введение в глубокое обучение.**   
  
**Лекции 1,2. Классификация, основанная на данных**   

Введение в курс.  
Задача классификации изображений.  
Подходы основанные на данных.  
Основные идеи - От MLP до CNN.
  
**Часть вторая. Основы глубокого обучения.**   
  
**Лекция 3. Функции потерь и оптимизация.**  

Мультиклассовый SVM и его функция потерь.  
Софтмакс и мультимодальная логистическая регрессия.  
Оптимизация функции потерь.  
Стохастический градиентный спуск (SGD).  
Разбор задач к самостоятельной: функции потерь для SVM и софтмакса.

**Лекция 4. Нейронные сети и обратное распространение ошибки.**  
 
Классификация с точки зрения нейронной сети.  
Многослойный перцептрон.  
Представление сети в виде вычислительного графа.
Алгоритм обратного распространения ошибки на вычислительном графе.  
Разбор задач к самостоятельной: прямое и обратное распротранение по вычислительному графу.  

**Лекция 5. Сверточные сети (СНС).**  
История.  
Основные операции СНС.  
Применение СНС вне задач машинного зрения.  
Разбор задач к самостоятельной: расчет выхода сверточной сети.   
  
**Лекция 6. Инструментарий глубокого обучения.**  
CPU vs GPU vs TPU.  
Пакеты глубокого обучения, Tensorflow, Keras и другие.  
Вычислительные графы СНС.    

**Самостоятельня работа.**  
  
Три задачи из лекций 2-5.  
**Внимание:** участие в самостоятельной, как и сдача лабораторных, необходимое условие для допуска к экзамену.  

**Лекция 7. Обучение СНС, часть 1.**  

Активационные функции, обработка данных сетью.  
Пакетная нормализация и другие трюки.  
Transfer learning.

**Лекция 8. Обучение СНС, часть 2.**  

Политики обновления гиперпараметров.  
Тюнинг процесса обучения.
Аугментация данных.  

**Лекция 9. Архитектуры СНС**  

Базовые архитектуры - AlexNet, VGG, GoogleNet, ResNet, UNET и другие.  


## План лабораторных работ

Материалы лабораторных работ:
Часть 1 - [Введение в Python.](https://github.com/Daikon46/AISys_SamU/blob/main/Labs1-Python/README.md)
Часть 2 - [Разработка систем ИИ.](https://github.com/Daikon46/AISys_SamU/blob/main/Labs2-DL/README.md)

Списки групп и статус выполнения лабораторных работ можно будет найти в [гугл-таблице](https://docs.google.com/spreadsheets/d/1R77CN5dvBpbXgZ-iWPGxt1W7K12V8aHv/edit?usp=drive_link&ouid=107640243735509757400&rtpof=true&sd=true).


## Литература и дополнительные источники  

1. Отличная книга на русском по глубокому обучению -  
[С. И. Николенко, А. Кадурин, Е. В. Архангельская, Глубокое обучение. Погружение в мир нейронных сетей. 2018](https://www.ozon.ru/context/detail/id/154415719/)  

2. Отличная книга по техническим аспектам реализации на Python -  
[Шолле Франсуа, Глубокое обучение на Python](https://www.ozon.ru/context/detail/id/145615583/)  

3. Хорошая современная книга на английском: [Advanced Deep Learning with Python. By Ivan Vasilev](http://neuralnetworksanddeeplearning.com)

4. [Лекционный курс К.В. Воронцова по машинному обучению](http://www.machinelearning.ru/wiki/index.php?title=%D0%9C%D0%B0%D1%88%D0%B8%D0%BD%D0%BD%D0%BE%D0%B5_%D0%BE%D0%B1%D1%83%D1%87%D0%B5%D0%BD%D0%B8%D0%B5_%28%D0%BA%D1%83%D1%80%D1%81_%D0%BB%D0%B5%D0%BA%D1%86%D0%B8%D0%B9%2C_%D0%9A.%D0%92.%D0%92%D0%BE%D1%80%D0%BE%D0%BD%D1%86%D0%BE%D0%B2%29).  

5. [Видеолекция академика Ю.И. Журавлева](https://www.youtube.com/watch?v=R3CMqrrIWOk) об истоках машинного обучения в СССР и о сочетании эвристики и науки в распознавании образов.  

7. Видеолекции С.И. Николенко по GAN сетям [1](https://www.youtube.com/watch?v=SlJgPIOlpiI), [2](https://www.youtube.com/watch?v=w38m5mTrG_M&t=1147s).
Хорошая проверка ваших знаний, на выходе из настоящего курса вы должны полностью понимать то, что говорится в этих лекциях по GAN.  
  
8. Хорошая вводная книга по питону и базовым библиотекам, таким как numpy, pandas, jupyter.
[Python и анализ данных. Второе издание [2020] Уэс Маккинни](https://www.ozon.ru/product/python-i-analiz-dannyh-vtoroe-izdanie-makkini-ues-285933371)  
[Альтернативная ссылка](https://vk.com/wall-51126445_67509)  
Важное замечание: первое издание книги содержит в себе короткое введение в python, изъятое из второго издания. Первое издание с руководством по питону можно найти [например здесь](https://t.me/physics_lib).  

## Подборка книг по математике, базовых для машинного обучения  
По многочисленным просьбам привожу список книг по направлениям математики, которые составляют базу для машинного и глубокого обучения.  
Базу составляют - матанализ,  линейная алгебра, методы оптимизации, теория вероятностей и математическая статистика.  
Опционально, но полезно, знать цифровую обработку сигналов и теорию случайных процессов, численные методы, и конечно обработку изображений.  

1. Матанализ: Г. М. ФИХТЕНГОЛЬЦ. ОСНОВЫ. МАТЕМАТИЧЕСКОГО. АНАЛИЗА.
2. Линейная алгебра: Г.С. Швецов, Линейная алгебра. теория и прикладные аспекты.
3. Альтернативный, всегда актуальный вариант - Гантмахер, Теория матриц.
4. Методы оптимизации - Советская книга по методам оптимизации в технических задачах. Для тех кто не знает как рашифровывается BFGS))) -  
[Реклейтис Г., Рейвиндран А., Рэгсдел К. Оптимизация в технике. Том 1 М.: Мир, 1986. – 348 с.](https://www.studmed.ru/rekleytis-g-reyvindran-a-regsdel-k-optimizaciya-v-tehnike-tom-1_5d310297b68.html)  
5. Тервер и матстат: Гмурман В.Е., Теория вероятностей и математическая статистика.
6. Обработка изображений, здесь можно привести целый список, немного классических книг: Э. Прэтт, Цифровая обработка изображений; Гонсалес Р., Вудс Р. Цифровая обработка изображений;
7. Ну и важная тема, формирование и восприятие цвета: М. Домасев, С. Гнатюк, Цвет, управление цветом, цветовые расчеты и измерения  


[Хороший телеграмм канал с подборкой технических книг](https://t.me/physics_lib)  



