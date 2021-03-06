
# Приоритизация гипотез и анализ результатов А/В теста.

Отделом маркетинга подготовлен список гипотез для увеличения выручки. Необходимо провести приоритизацию данных гипотез, а также проанализировать результаты A/B теста. 

**Задачи: **
        
        Приоритизировать гипотезы с применением фреймворков ICE и ICE, 
        Построить графики кумулятивных показателей
        Посчитать значимые перцентили
        Посчитать статистическую значимость различий по разным параметрам
        Принять решение по результатам теста

**Используемые библиотеки**

        Pandas
        Numpy
        Math
        Scipy
        Matplotlib 
        Seaborn

**Описание данных**

Таблица hypothesis

    Hypothesis — краткое описание гипотезы;
    Reach — охват пользователей по 10-балльной шкале;
    Impact — влияние на пользователей по 10-балльной шкале;
    Confidence — уверенность в гипотезе по 10-балльной шкале;
    Efforts — затраты ресурсов на проверку гипотезы по 10-балльной шкале. Чем больше значение Efforts, тем дороже проверка гипотезы.


 Таблица orders

    transactionId — идентификатор заказа;
    visitorId — идентификатор пользователя, совершившего заказ;
    date — дата, когда был совершён заказ;
    revenue — выручка заказа;
    group — группа A/B-теста, в которую попал заказ.

Таблица visitors

    date — дата;
    group — группа A/B-теста;
    visitors — количество пользователей в указанную дату в указанной группе A/B-теста

