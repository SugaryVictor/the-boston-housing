# Multilinear regression on the example of a dataset about housing in Boston

Using this data set as an example, I want to show how a multilinear regression is built.

**Dataset taken from this site**: https://www.cs.toronto.edu/~delve/data/boston/bostonDetail.html

There are 506 observations in the dataset itself (a few)

## Variables
There are 14 features in the dataset:  
**CRIM** - crime rate per capita by city.  
**ZN** - the share of land for residential development, zoned for plots over 25,000 sq.m.  
**INDUS** is the proportion of acres of non-trading business per city.  
**CHAS** is the Charles River dummy variable (1 if the site borders a river; 0 otherwise).  
**NOX** - concentration of nitrogen oxides (parts per 10 million).  
**RM** - average number of rooms in a dwelling.  
**AGE** - proportion of housing units built before 1940.  
**DIS** -are weighted distances to five Boston job centers.  
**RAD** - index of accessibility to radial highways  
**TAX** - The full rate of property tax for $10,000.  
**PTTRATIO** - the ratio of students and teachers by city.  
**B** - 1000 (Bk - 0.63)^2, where Bk is the proportion of blacks by city.  
**LSTAT** - % lower status of the population.  
**MEDV** - Average value of owner-occupied homes in $1,000.  

### Note
Variable #14 appears to be censored at 50.00 (corresponding to an average price of $50,000); Censorship is indicated by the fact that the highest median price of exactly $50,000 is listed in 16 cases, and in 15 cases prices are in the range of $40,000 to $50,000, with prices rounded to the nearest hundred. Harrison and Rubinfeld do not mention any censorship.

# Мультилинейная регрессия на примере датасета о жилье в Бостоне

На примере этого датасета я хочу показать, как строится мультилинейная регрессия.

**Датасет взят с этого сайта**: https://www.cs.toronto.edu/~delve/data/boston/bostonDetail.html

В самом наборе данных 506 наблюдений (очень мало)

## Переменные
В датасете есть 14 фичей:  
**CRIM** - уровень преступности на душу населения по городам.  
**ZN** - доля земель под жилую застройку, зонированных под участки свыше 25 000 кв.м.  
**INDUS** - доля акров неторгового бизнеса на город.  
**CHAS** - фиктивная переменная реки Чарльз (1, если участок граничит с рекой; 0 в противном случае)  
**NOX** - концентрация оксидов азота (частей на 10 млн).  
**RM** - среднее количество комнат в жилом помещении.  
**AGE** - доля жилых единиц, построенных до 1940г.  
**DIS** - взвешенные расстояния до пяти центров занятости Бостона.  
**RAD** - индекс доступности к радиальным магистралям.  
**TAX** - полная ставка налога на имущество за 10 000 долларов США.  
**PTTRATIO** - соотношение учеников и учителей по городам.  
**B** - 1000 (Bk - 0,63)^2, где Bk - доля чернокожих по городам.  
**LSTAT** - % более низкий статус населения.  
**MEDV** - Средняя стоимость домов, занимаемых владельцами, в 1000 долларов.  

### Примечание
Переменная № 14, по-видимому, подвергается цензуре на уровне 50,00 (что соответствует средней цене в 50 000 долларов США); На цензуру указывает тот факт, что самая высокая медианная цена, составляющая ровно 50 000 долларов, указана в 16 случаях, а в 15 случаях цены находятся в диапазоне от 40 000 до 50 000 долларов, причем цены округлены до ближайшей сотни. Харрисон и Рубинфельд не упоминают о какой-либо цензуре.
