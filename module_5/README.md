# Задача
Построить скоринг модель для клиентов банка, которая бы предсказывала вероятность дефолта клиента:
  1. провести EDA;
  2. добавить признаки улучшающие модель;
  3. создать модель бинарной классификации;
  4. подбор гиперпараметров;
  5. тестирование модели. 

# Цель
добиться лучшего показателя метрики ROC AUC.

# Результат
Тестирование модели на kaggle дало результат ROC AUC = 0.73416. 

# Описание датасета
В данных предоставлена информация из анкетных данных заемщиков и факт наличия дефолта.

client_id - идентификатор клиента  
education - уровень образования  
sex - пол заемщика  
age - возраст заемщика  
car - флаг наличия автомобиля  
car_type - флаг автомобиля иномарки  
decline_app_cnt - количество отказанных прошлых заявок  
good_work - флаг наличия “хорошей” работы  
bki_request_cnt - количество запросов в БКИ  
home_address - категоризатор домашнего адреса  
work_address - категоризатор рабочего адреса  
income - доход заемщика  
foreign_passport - наличие загранпаспорта  
sna - связь заемщика с клиентами банка  
first_time - давность наличия информации о заемщике  
score_bki - скоринговый балл по данным из БКИ  
region_rating - рейтинг региона  
app_date - дата подачи заявки  
default - флаг дефолта по кредиту  
