# Исследование причин сердечно-сосудистых заболеваний (ССЗ)

## Данные
Набор данных состоит из 70 000 записей данных о пациентах по 12 параметрам, таким как возраст, пол, систолическое артериальное давление, диастолическое артериальное давление и т.д. Целевой класс "кардио" равен 1, если у пациента есть сердечно-сосудистые заболевания, и 0, если пациент здоров.  

Возраст - age  
Пол - gender (1: женщины, 2: мужчины)  
Рост - height (cm)  
Вес - weight (kg)  
Систолическое кровяное давление (верхняя граница) - ap_hi  
Диастолическое кровяное давление (нижняя граница) - ap_lo  
Холестерол - cholesterol (1: норма, 2: сверх нормы, 3: сильно выше нормы)  
Глюкоза - gluc (1: норма, 2: сверх нормы, 3: сильно выше нормы)  
Курение - smoke (1: курящие, 0: нет)  
Употребление алкоголя - alco (1: да, 0: нет)  
Физ. активность (1: присутствует, 0: отсутсвует)  
Наличие сердечно-сосудистых заболеваний (ССЗ) - cardio (1: есть, 0: нет)  

## Задача
Найти закономерности по наличию или отсутствию сердечно-сосудистых заболеваний (ССЗ) по результатам обследований пациентов.  

Подзадачи:  
Проверить, есть ли зависимость между:  

возрастом и наличием ССЗ  
полом и наличием ССЗ  
давлением и наличием ССЗ  
уронем холестерина и наличием ССЗ  
курением и наличием ССЗ  
употреблением алкоголя и наличием ССЗ  
физ. активностью и наличием ССЗ.  
ИМТ и наличием ССЗ.  

## Вывод
- Средний возраст пациентов с наличием ССЗ (54 года) на 3 года выше, чем у здоровых пациентов (51).  
- Среди возрастных людей гораздо больше больных. Чем больше возраст, тем больше пациентов с ССЗ.  
- Мужчины и женщины с одинаковой частотой имеют ССЗ. Пол не влияет на средний возраст заболеваемостью ССЗ.  
- Для больных ССЗ в целом характерно более высокое давление.
- Пациентов с ССЗ больше в группе с высоким и повышенным уровнем холестерина.  Чем выше уровень холестерина, тем больше больных и меньше здоровых пациентов.  
- Повышенный и высокий уровень холестерина встречаются чаще с увеличением возраста.  
- Среди пациентов с повышенным и высоким уровнем глюкозы больше больных ССЗ. Чем старше пациент, тем больше вероятность повышенного или высокого уровня глюкозы.  
- Нет какой-либо выраженной зависимости между курением и заболеваемостью ССЗ. При этом курящие женщины c ССЗ , в отличие от мужчин, имеют повышенную массу тела.  
- Нет какой-либо выраженной зависимости между употреблением алкоголя и наличием ССЗ. Однако у людей, употребляющих алкоголь, выше ИМТ. При этом, женщины, употребляющие алкоголь, более склонны к увеличенному ИМТ, чем мужчины.   
- Физ. активность не влияет ни на наличие ССЗ, ни на ИМТ.
- Масса тела (а соответственно и ИМТ) определённо влияет на наличие ССЗ. Чем выше масса тела, тем больше пациентов с ССЗ.
- Мужчины с выраженным недостатком массы тела и ожирением 3 степени гораздо раньше заболевают ССЗ (так, 2 из 3 пациентов с ожирением 3 ст. больны ССЗ). Чем больше ИМТ, тем более высокое давление характерно для пациента.


**ГИПОТЕЗЫ:**
- гипотеза о равенстве среднего возраста в группах пациентов с ССЗ и без ССЗ отвергнута в пользу предположения о том, что средний возраст пациентов с ССЗ выше, чем у пациентов без ССЗ.  
- гипотеза о равенстве среднего ИМТ в группах пациентов с ССЗ и без ССЗ отвергнута в пользу предположения о том, что ИМТ пациентов с ССЗ выше, чем у пациентов без ССЗ.

## Используемые библиотеки
pandas, numpy, matplotlib, seaborn, scipy.stats, 
