# LR_0_ML
### Задача 
Сказать будет ли завтра дождь или нет.   
#### Описание датасета
Этот набор данных содержит около 10 лет ежедневных наблюдений за погодой с многочисленных австралийских метеостанций.

RainTomorrow - это целевая переменная для прогнозирования. Это значит - шел ли дождь на следующий день, да или нет?
Эта колонка имеет значение "Да", если количество осадков за этот день составило 1 мм или более.
#### Ссылка на датасет:    
Rain in Australia https://www.kaggle.com/jsphyg/weather-dataset-rattle-package

Описание столбцов:

| Название      | Описание      | 
| ------------- |:-------------:| 
| Date	        | Дата наблюдения |
| Location      | Общепринятое название местоположения метеостанции | 
| MinTemp	    | Минимальная температура в градусах Цельсия | 
| MaxTemp       | Максимальная температура в градусах Цельсия |
| Rainfall	    | Количество осадков, зафиксированных за день в мм |
| Evaporation	| Так называемое испарение на сковороде класса А (мм) за 24 часа до 9 утра. |
| Sunshine	    | Количество часов солнечного света в день |
| WindGustDir	| Направление сильнейшего порыва ветра за 24 часа до полуночи |
| WindGustSpeed	| Скорость (км / ч) самого сильного порыва ветра за 24 часа до полуночи. |
| WindDir9am	| Направление ветра в 9 утра |
| WindDir3pm    | Направление ветра в 15:00 |
| WindSpeed9am  | Средняя скорость ветра (км / ч) за 10 минут до 9 часов утра |
| WindSpeed3pm  | Скорость ветра (км / ч), усредненная за 10 минут до 15:00 |
| Humidity9am	| Влажность (в процентах) в 9 утра  |
| Humidity3pm	| Влажность (в процентах) в 15:00 |
| Pressure9am	| Атмосферное давление (гПа) снижено до среднего уровня моря в 9 утра |
| Pressure3pm	| Атмосферное давление (гПа) снижено до среднего уровня моря в 15:00 |
| Cloud9am	    | Часть неба, закрытая облаками в 9 утра. Он измеряется в октах, которые составляют восьмые доли. Он записывает, сколько |
| Cloud3pm	    | Часть неба, закрытая облаками (в «октах»: восьмые) в 15:00. См. Описание значений в Cload9am |
| Temp9am	    | Температура (градусы С) в 9 утра |
| Temp3pm	    | Температура (градусы C) в 15:00 |
| RainToday	    | 1, если количество осадков (мм) за 24 часа до 9 утра превышает 1 мм, в противном случае - 0 |
| RainTomorrow  | 1, если количество осадков (мм) за 24 часа до 9 утра превышает 1 мм, в противном случае - 0  |

В лабораторной работе проанализировали зависимость вероятности выпадения осадков завтра от различных параметров. Выяснили от каких параметров целевое заначение зависит меньше всего и удалили их. 
