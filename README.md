# <center> Feature selection

## Оглавление  
[1. Описание проекта](https://github.com/mrfluffypaws/Feature-selection/blob/main/README.md#Описание-проекта)  
[2. Задачи](https://github.com/mrfluffypaws/Feature-selection/blob/main/README.md#Задачи)  
[3. Краткая информация о данных](https://github.com/mrfluffypaws/Feature-selection/blob/main/README.md#Краткая-информация-о-данных)  
[4. Этапы работы над проектом](https://github.com/mrfluffypaws/Feature-selection/blob/main/README.md#Этапы-работы-над-проектом)  
[5. Результат](https://github.com/mrfluffypaws/Feature-selection/blob/main/README.md#Результаты)    
[6. Выводы](https://github.com/mrfluffypaws/Feature-selection/blob/main/README.md#Выводы) 

### Описание проекта    
Научится использовать инструменты по отбору признаков, на основании которых будет обучаться модель. 

:arrow_up:[к оглавлению](https://github.com/mrfluffypaws/Feature-selection/blob/main/README.md#Оглавление)


### Задачи    
1. Обучить модель линейной регрессии на найденных двумя способами (метод рекурсивного исключения признаков, метод отбора признаков на основе фильтров) трёх важных признаках; 
2. Сравнить полученные результаты.
  

**Метрика качества**     
* Верное решение поставленных задач.


**Что практикуем**     
* Использование инструментов по отбору признаков, на основании которых будет обучаться модель. 

:arrow_up:[к оглавлению](https://github.com/mrfluffypaws/Feature-selection/blob/main/README.md#Оглавление)


### Краткая информация о данных
Для анализа была предоставлена таблица, содержащая следующую информацию:
* price (тип данных int64);
* year (тип данных int64);
* condition (тип данных int64);
* cylinders (тип данных int64); 
* odometer (тип данных int64);
* title_status (тип данных object);
* transmission (тип данных object);
* drive (тип данных object);
* size (тип данных object);
* lat (тип данных float64);
* long (тип данных float64);
* weather (тип данных float64).

  
:arrow_up:[к оглавлению](https://github.com/mrfluffypaws/Feature-selection/blob/main/README.md#Оглавление)


### Этапы работы над проектом  
1. Импорт необходимых библиотек;
2. Загрузка данных;
3. Поиск пропусков в данных;
4. Обработка пропусков;
5. Кодирование признаков;
6. Создание тренировочной и тестовой выборок для обучения модели;
7. Поиск вызных признаков для обучения модели методом рекурсивного исключения признаков;
8. Поиск вызных признаков для обучения модели методом отбора признаков на основе фильтров;
9. Обучение модели на признаках метода рекурсивного исключения признаков;
10. Обучение модели на признаках метода отбора признаков на основе фильтров;
11. Обучение модели на основе всех признкаов.


:arrow_up:[к оглавлению](https://github.com/mrfluffypaws/Feature-selection/blob/main/README.md#Оглавление)


### Результаты:  
В результате проделанной работы был получен практический опыт использования метода рекурсивного исключения признаков и метода отбора признаков на основе фильтроврашения.    

:arrow_up:[к оглавлению](https://github.com/mrfluffypaws/Feature-selection/blob/main/README.md#Оглавление)


### Выводы:  
Мотоды отбора признаков для целей дальнейшего обучения модели машинного обучения являются полезным инструментов в арсинале специалиста в области data science, поскольку способны выявить максимально подходяцие признаки на которых впоследствии будет обучена модель.      


:arrow_up:[к оглавлению](https://github.com/mrfluffypaws/Feature-selection/blob/main/README.md#Оглавление)


Если информация по этому проекту покажется вам интересной или полезной, то я буду очень вам благодарен, если отметите репозиторий и профиль ⭐️⭐️⭐️-дами

