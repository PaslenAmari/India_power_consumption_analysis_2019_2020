Анализ потребления электроэнергии в Индии (2019-2020гг)
датасет с kaggle

Посмотрели пропущенные значения по городам Индии из датасета.

Визаулизировали для перепроверки:
![image](https://github.com/PaslenAmari/India_power_consumption_analysis_2019_2020/assets/106679149/d9f3f804-1e16-46ce-b63d-cbc056ec7d82)

Посмотрели статистические данные по числовым признакам:
![image](https://github.com/PaslenAmari/India_power_consumption_analysis_2019_2020/assets/106679149/28ba82f0-2ab0-4ba1-bcb7-15f82567a0ae)

Определили категориальный признак и декомпозировали его на составляющие (год, месяц и т.д.)
![image](https://github.com/PaslenAmari/India_power_consumption_analysis_2019_2020/assets/106679149/4921553c-130b-43cb-a165-2cc11d921b9e)

Суммарно посмотрели энергпотребление в разрезе представленных в датасете годов:
![image](https://github.com/PaslenAmari/India_power_consumption_analysis_2019_2020/assets/106679149/8cf34680-c795-4510-858f-922daa15ac9f)

Посмотрели распределение по городам без группировки по годам:
![image](https://github.com/PaslenAmari/India_power_consumption_analysis_2019_2020/assets/106679149/2ed5eeff-11b0-41a0-ba91-dc7a430e67ef)
![image](https://github.com/PaslenAmari/India_power_consumption_analysis_2019_2020/assets/106679149/0b621218-5685-4ecb-af8c-a267c3f434f4)

Визуализировали расположение городов из датасета на карте Индии:
![image](https://github.com/PaslenAmari/India_power_consumption_analysis_2019_2020/assets/106679149/6acf505c-790e-4187-8ef9-d99b34e37520)

Посмотрим корреляцию через функцию corr() (через коэффициенты корреляции Пирсона):
![image](https://github.com/PaslenAmari/India_power_consumption_analysis_2019_2020/assets/106679149/042dbb99-c61a-4923-aa1e-a2ebcb2bee06)
![image](https://github.com/PaslenAmari/India_power_consumption_analysis_2019_2020/assets/106679149/b9c8284e-ce63-4446-9018-a038d02f06f0)

Посмотрели попарно наиболее корелируемые города по значениям энергопотребления:
![image](https://github.com/PaslenAmari/India_power_consumption_analysis_2019_2020/assets/106679149/201dac84-fa70-4430-a614-5b9e44b22431)
![image](https://github.com/PaslenAmari/India_power_consumption_analysis_2019_2020/assets/106679149/9a962710-234e-43c1-8629-d62870da362f)

Посмотрели по координатма топографию местности для определения перепада высот (для определения разницы в энергопотреблениидля городов, находхщихся в горной местности и на равнинах):
![image](https://github.com/PaslenAmari/India_power_consumption_analysis_2019_2020/assets/106679149/6e47b266-59a3-45cb-ac94-bff89ca67dd0)

Вывода:
Для городов, без значительных различий по альтитуде, можно сделать вывод, что их энергопотребление и при расстоянии между ними менее 300 км, не будет иметь существенных различий.
Для городов со значительными различиями по альтитуде (дельта больше 500м), можно сделать вывод, что энергопотребление у городов, находящихся в горной местности (альтитуда 1000м по средним значениям) и при расстоянии между ними более 500 км, будет сильно отличаться
