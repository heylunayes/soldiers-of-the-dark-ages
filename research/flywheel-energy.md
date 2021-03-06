## Энергоёмкость маховиков

Формула плотности энергии:  
```
E/m=K*(a/p)
```
Где:  
E — энергия (джоули)  
m — масса (килограммы)  
K — коэффициент, зависящий от формы диска  
a — прочность материала (паскали)  
p — плотность материала (кг/м³)  

Коэффицинет плотности энергии:  
Диск равной прочности: K = 0.6-1 (в зависимости от формы и толщины обода).  
Диск без отверстия (равной толщины) — 0.6  
Тонкий обод (колесо со спицами) — 0.5  
Диск с центральным отверстием (гончарный круг) — 0.3  

Диапазон пределов прочности для стали — 500-3000 МПа  
Предел прочности арамидной ткани (кевлара) — 3650 МПа  
Предел прочности кремнезёма (высокотехнологичного волокна) — 5900 МПа  
Предел прочности углеродных нанотрубок — 120 000 МПа  

Плотность углепластика — 1800 кг/м³  

Вычисление:  
```
0.6*(30000000000/1800)=10*10^6 джоулей (10 МДж)
```
На 10 МДж/кг плотности энергии требуется 30 ГПа прочности диска при K=0.6, или 20 ГПа при К=0.9  

Формула энергии маховика:  
```
E=1/2*I*w²
```
Где:  
I — момент инерции  
w — угловая скорость вращения  

Момент инерции (формула для сплошного цилиндра):  
```
I=1/2*m*r^2
```
m — масса  
r — радиус  

Угловая скорость вращения:  
```
w=2*Pi*f
```
Pi — 3.14159265  
f — частота вращения  

Выведенная формула:  
```
E=m*(Pi*f)^2*(r^2)
```
E — энергия в джоулях  
m — масса в килограммах  
Pi — 3.14159265  
f — частота вращения  
r — радиус в метрах  

## Танковый маховик

Ширина корпуса танка у нас 2 метра, значит диаметр диска не больше 1.8 метра:  
```
(3.14159265*0.9^2*0.18)/2*1800=412 кг
```
Диаметр диска — 180 метров, толщина диска — 18 сантиметров. Масса — 412 килограмм (а нужно 4 тонны).
Хотя, можно обойтись и 2.4 тоннами, если танк весит всего 40 тонн. Значит три маховика один на другом плюс ещё три.  

Площадь кожуха:  
Площадь цилиндра: `S=2*Pi*r*(h+r)`  
```
2*3.14159265*0.9*(0.18+0.9)=6.1 м²
```
Маховик должен стоять в корпусе хотя бы 5-мм углепластика:  
```
6.1*0.005*1800=55 килограмм
```
 
Каждый маховик занимает полметра внутреннего объёма танка. Многовато.  

Энергия танкового маховика:
Подстановка (танковый маховик):  
m — 481 килограмм  
r — 0.9 метра  
f — 1120 оборотов в секунду  
Вычисление:  
```
481*(3.14159265*1120)^2*(0.9^2)/10^6=4823 МДж/маховик
```

Энергия маховика — 4.8 ГДж при частоте вращения в 1120 оборотов/секунду (67 800 оборотов/минуту).  
Для сравнения: Скорость вращения ротора пылесоса может достигать 30 000 оборотов в минуту, хотя диаметр ротора не больше пяти сантиметров. Вольфрамовые гироскопы баллистических ракет вращаются со скоростями до 180 000 оборотов/минуту, разумеется в вакууме и на магнитном подвесе.  

Вычисляем линейную скорость:  
Периметр круга: `P=2*Pi*r`  
Периметр диска маховика:  
```
2*3.14159265*0.9=5.7 метра
```
Линейная скорость:  
```
5.65*1120=6328 м/с  
```
