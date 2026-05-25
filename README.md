# Проект. Аппроксимация модели движения ЛА с помощью ML
### Предварительный план исследования
1. Обзор литературы по направлениям тематики исследования.
2. Получение данных для аппроксимации движения ЛА (методика формирования, обработки телеметрии, предобработка данных и др.).
3. Математическое описание различных моделей аппроксиматоров.
4. Анализ результатов исследования (различные методы оценки аппроксимации, их недостатки и преимущества).
5. Выводы.

## Обзор литературы
В папке [review/](https://github.com/LadyAlena/Flight-model-approximation-with-ML/tree/main/review) находятся обзоры представленных в списке статей, книг и пр. У каждого источника есть своя папка с именем его названия, в которой содержатся файл с его описанием description.md, PDF-файл данного источника (или ссылка на него в description.md), опционально реализации описанных в нем алгоритмов, методов в виде исходных файлов кода на каком-либо языке программирования.

Предварительный список источников (в дальнейшем будет дополняться, уточняться по локальным тематикам, т.е. для каждой тематики свой список источников, например, список источников по индитификации динамики объекта частотными методам и т. д.):
1. [Всё о LSTM: зачем нужна нейронная сеть и как с ней работать](https://github.com/LadyAlena/Flight-model-approximation-with-ML/tree/main/review/All-about-LSTM-why-you-need-a-neural-network-and-how-to-work-with-it)
2. [Trajectory prediction of flying vehicles based on deep learning methods](https://github.com/LadyAlena/Flight-model-approximation-with-ML/tree/main/review/Trajectory-prediction-of-flying-vehicles-based-on-deep-learning-methods)
3. [Aircraft Trajectory Prediction using LSTM Neural Network with Embedded Convolutional Layer](https://github.com/LadyAlena/Flight-model-approximation-with-ML/tree/main/review/Aircraft-Trajectory-Prediction-using-LSTM-Neural-Network-with-Embedded-Convolutional-Layer)
4. [Обзор репозитория drone_mvmot_lstm_trajectory_predictor](https://github.com/LadyAlena/Flight-model-approximation-with-ML/tree/main/review/drone_mvmot_lstm_trajectory_predictor)
5. [Phased Flight Trajectory Prediction with Deep Learning](https://github.com/LadyAlena/Flight-model-approximation-with-ML/tree/main/review/Phased-Flight-Trajectory-Prediction-with-Deep-Learning)
6. [A Multi-task Learning Framework for Drone State Identification and Trajectory Prediction](https://github.com/LadyAlena/Flight-model-approximation-with-ML/tree/main/review/A-Multi-task-Learning-Framework-for-Drone-State)

Заметки: найти литературу, в которой представлены варианты формирования данных на основе летных экспериментов/моделирования движения ЛА для аппроксимации модели/обучения нейросети.

## Аннотация

## Введение



## Математическое описание различных моделей аппроксиматоров
В настоящее время существует большое количество аппроксиматоров под самые различные задачи. Если говорить об аппроксимации параметров движения ЛА, изменяющихся во времени,то необходимо использовать модели, которые учитывают порядок данных,т.е. контекст. В работах для решения такой задачи в основном используют:
1) модель в виде передаточной функции с идентификацией МНК;
2) линейная ARX-модель;
3) нелинейная NARX-модель;
4) рекурретная нейронная сеть (RNN);
5) сеть долгой краткосрочной памяти (LSTM).

Рассмотрим каждую из них в отдельности.

### Передаточная функция с идентификацией МНК

### Линейная ARX-модель

### Нелинейная NARX-модель

### Рекуррентная нейронная сеть

### Сеть долгой краткосрочной памяти (LSTM)

## Анализ телеметрии движения ЛА

## Подготовка данных для аппроксимации движения ЛА

## Анализ результатов исследования

## Выводы
