# [Прогнозирование температуры звезды](https://nbviewer.jupyter.org/github/Nanobelka/stars_temperature/blob/main/stars_temperature.ipynb)
Project for [Yandex.Praktikum](https://github.com/Nanobelka/Yandex_Praktikum)

### **Входные данные**  
Характеристики изученных 240 звезд.

### **Цель**  
Разработать нейронную сеть для предсказания абсолютной температуры на поверхности звезды.

### **Задачи:**  
- провести исследовательский анализ данных;
- исправить ошибки в данных;
- оценить значимость признаков для модели;
- подготовить данные для обучения модели;
- создать простую нейронную сеть:
    - cоздать класс для задания архитектуры нейронной сети;
    - cоздать функцию для обучения нейронной сети;
    - обучить модель;
    - построить график (по оси X – условные номера звезд, по оси Y – температура в Кельвинах);
- внести улучшения в нейронную сеть:
    - создать решение с перебором параметров нейросети;
    - обучить модель;
    - добиться метрики RMSE ниже 4500;
    - вывести таблицу с результатами эксперимента;
    - вывести график качества прогноза;
- подвести итог исследования.


### Примеры визуализаций

EDA

![star_color](https://github.com/Nanobelka/stars_temperature/blob/main/images/example_1_star_color.png)

![log_Luminosity_log_Temperature](https://github.com/Nanobelka/stars_temperature/blob/main/images/example_2a_log_Luminosity_log_Temperature.png)

![log_Radius_log_Temperature](https://github.com/Nanobelka/stars_temperature/blob/main/images/example_2b_log_Radius_log_Temperature.png)

![correlatins](https://github.com/Nanobelka/stars_temperature/blob/main/images/example_3_correlatins.png)

Mutual info

![correlatins](https://github.com/Nanobelka/stars_temperature/blob/main/images/example_4_mutual_info.png)

Анализ результата

![temperature_target_and_prediction](https://github.com/Nanobelka/stars_temperature/blob/main/images/example_5a_temperature_target_and_prediction.png)

![log_temperature_target_and_prediction](https://github.com/Nanobelka/stars_temperature/blob/main/images/example_5b_log_temperature_target_and_prediction.png)
