**[Dataset daily infected, deaths and recovered](#_jczym64vm6q6) 1**

**[Mobility dataset](#_9mqaofimoeg3) 2**

[Feriados Argentina](#_wlimf5uzxc2) 2

[Google mobility](#_43k5655kmq9a) 2

[Apple mobility](#_1gb0rjbcdemj) 2

**[Tests Argentinas y ocupación de camas](#_2p2wssrdlku3) 3**

[Camas por país](#_1einwn84dnxq) 4

[Test per day dataset](#_ayes3grdjc4i) 4

[Why is data on testing important?](#_2ajsw9mbo5o9) 4

[Daily COVID-19 tests per thousand people](#_2ko8puyubqgl) 5

[Tests per case: how many tests to find one COVID-19 case?](#_kku18rlc2wca) 6

[What can we learn from these measures about the pandemic?](#_4yjho32mvl2j) 7

**[Kaggle Predictions](#_w7kn2quwuvcx) 7**

**[Other](#_9gkzvfxartxt) 7**

# Dataset daily infected, deaths and recovered

[Casos COVID-19](http://datos.salud.gob.ar/dataset/covid-19-casos-registrados-en-la-republica-argentina/archivo/fd657d02-a33a-498b-a91b-2ef1a68b8d16) detallados por ciudad, sexo edad, etc de la Republica Argentina

| Título de la columna | Tipo de dato | Descripción |
| --- | --- | --- |
| id\_evento\_caso | Número entero (integer) | Numero de caso |
| sexo | Texto (string) | Sexo |
| edad | Número entero (integer) | Edad |
| edad\_años\_meses | Texto (string) | Edad indicada en meses o años |
| residencia\_pais\_nombre | Texto (string) | País de residencia |
| residencia\_provincia\_nombre | Texto (string) | Provincia de residencia |
| residencia\_departamento\_nombre | Texto (string) | Departamento de residencia |
| carga\_provincia\_nombre | Texto (string) | Provincia de establecimiento de carga |
| fecha\_inicio\_sintomas | Fecha ISO-8601 (date) | Fecha de inicio de síntomas |
| fecha\_apertura | Fecha ISO-8601 (date) | Fecha de apertura del caso |
| sepi\_apertura | Número entero (integer) | Semana Epidemiológica de fecha de apertura |
| fecha\_internacion | Fecha ISO-8601 (date) | Fecha de internación |
| cuidado\_intensivo | Texto (string) | Indicación si estuvo en cuidado intensivo |
| fecha\_cui\_intensivo | Fecha ISO-8601 (date) | Fecha de ingreso a cuidado intensivo en el caso de corresponder |
| fallecido | Texto (string) | Indicación de fallecido |
| fecha\_fallecimiento | Tiempo ISO-8601 (time) | Fecha de fallecimiento en el caso de corresponder |
| asistencia\_respiratoria\_mecanica | Texto (string) | Indicación si requirió asistencia respiratoria mecánica |
| carga\_provincia\_id | Número entero (integer) | Código de Provincia de carga |
| origen\_financiamiento | Texto (string) | Origen de financiamiento |
| clasificacion | Texto (string) | Clasificación manual del registro |
| clasificacion\_resumen | Texto (string) | Clasificación del caso |
| residencia\_provincia\_id | Número entero (integer) | Código de Provincia de residencia |
| fecha\_diagnostico | Tiempo ISO-8601 (time) | Fecha de diagnóstico |
| residencia\_departamento\_id | Número entero (integer) | Código de Departamento de residencia |
| ultima\_actualizacion | Fecha ISO-8601 (date) | Última actualización |

[https://github.com/SistemasMapache/Covid19arData](https://github.com/SistemasMapache/Covid19arData)

[https://github.com/CSSEGISandData/COVID-19/tree/master/csse\_covid\_19\_data/csse\_covid\_19\_time\_series](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series)

[https://data.humdata.org/hxlproxy/api/data-preview.csv?url=https%3A%2F%2Fraw.githubusercontent.com%2FCSSEGISandData%2FCOVID-19%2Fmaster%2Fcsse\_covid\_19\_data%2Fcsse\_covid\_19\_time\_series%2Ftime\_series\_covid19\_confirmed\_global.csv&amp;filename=time\_series\_covid19\_confirmed\_global.csv](https://data.humdata.org/hxlproxy/api/data-preview.csv?url=https%3A%2F%2Fraw.githubusercontent.com%2FCSSEGISandData%2FCOVID-19%2Fmaster%2Fcsse_covid_19_data%2Fcsse_covid_19_time_series%2Ftime_series_covid19_confirmed_global.csv&amp;filename=time_series_covid19_confirmed_global.csv)

[https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse\_covid\_19\_data/csse\_covid\_19\_time\_series/time\_series\_covid19\_confirmed\_global.csv](https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv)

Same but JSON → [https://pomber.github.io/covid19/timeseries.json](https://pomber.github.io/covid19/timeseries.json)

[http://sep.tucuman.gob.ar/dataset/informe-diario-min-de-salud-de-la-nacion](http://sep.tucuman.gob.ar/dataset/informe-diario-min-de-salud-de-la-nacion)

[https://en.wikipedia.org/wiki/COVID-19\_pandemic\_in\_Argentina](https://en.wikipedia.org/wiki/COVID-19_pandemic_in_Argentina)

Estaria bueno ver de agregar el origen de los casos

1. Autóctonos
2. Importados
3. etc

![](RackMultipart20200817-4-1njbqa1_html_f918d87864f35ac1.jpg)

[COVID-19. Casos registrados en la República Argentina](http://datos.salud.gob.ar/dataset/covid-19-casos-registrados-en-la-republica-argentina)

[https://qlik3.ms.gba.gov.ar/sense/app/0a29a121-edef-4cd9-9ffd-fb5e298b5afd/sheet/c812ce2b-d071-4e1c-a7a2-3a63cf710b68/state/analysis](https://qlik3.ms.gba.gov.ar/sense/app/0a29a121-edef-4cd9-9ffd-fb5e298b5afd/sheet/c812ce2b-d071-4e1c-a7a2-3a63cf710b68/state/analysis)

# Mobility dataset

[https://about.fb.com/news/2020/04/data-for-good/?utm\_source=email&amp;utm\_medium=fb4d-newsletter-april20&amp;utm\_campaign=organic&amp;utm\_offering=developer-news&amp;utm\_product=news&amp;utm\_content=body-content-coronavirustools&amp;utm\_location=3](https://about.fb.com/news/2020/04/data-for-good/?utm_source=email&amp;utm_medium=fb4d-newsletter-april20&amp;utm_campaign=organic&amp;utm_offering=developer-news&amp;utm_product=news&amp;utm_content=body-content-coronavirustools&amp;utm_location=3)

## Feriados Argentina

[Feriados 2020](https://www.argentina.gob.ar/interior/feriados-nacionales-2020)

## Google mobility

[Mobility Report CSV Documentation](https://www.google.com/covid19/mobility/data_documentation.html)

- region empy es el % del pais
- el resto por region es el % que subio y bajo
- todo se mueve entre +100 % y - 100%

Quiza parques y recreaciones conviene mostrarlo solo los fines de semana / feriados

Análisis en Excel → [Google Mobility.xlsx](https://1drv.ms/x/s!AkSFtNKJBDmNh6BQw8jPjwqwRcDutQ?e=nPlJWa)

## Apple mobility

[COVID‑19 - Mobility Trends Reports](https://www.apple.com/covid19/mobility)

- También está expresado en %
- Arranca en 100 en vez de 0, se podría hacer Dato - 100 para expresarlo al igual que el dataset de Google o continuar en 100 lo cual siempre nos daría números de movilidad positivo (lo cual es una puede ser una buena idea para luego procesador los datos en algún algoritmo)

Análisis en Excel → [Apple Mobility.xlsx](https://1drv.ms/x/s!AkSFtNKJBDmNh6B3FwNKf2sfF91YTw?e=bOhBeX)

# Tests Argentinas y ocupación de camas

[https://www.youtube.com/watch?v=wJdkK0wHpjc](https://www.youtube.com/watch?v=wJdkK0wHpjc)

## Camas Argentina cada 100K

- 09/04/2020 - [Control. Cómo funciona el sistema para administrar las camas de los hospitales](https://www.lanacion.com.ar/economia/covid-19-como-funciona-tablero-clave-centralizacion-del-nid2352561) → Según relevó recientemente el Ministerio de Salud de la Nación, **en la Argentina hay 8444 camas de terapia intensiva para adultos.** De ese total, 2516 son del sector público y 5928, del privado.
- 17/06/2020 - [Coronavirus en Argentina: falta información y preocupa la ocupación de camas de terapia intensiva](https://www.infobae.com/sociedad/2020/06/17/coronavirus-en-argentina-falta-informacion-y-preocupa-la-ocupacion-de-camas-de-terapia-intensiva/) → La **disponibilidad total de camas a nivel nacional del sector público y privado - 146.811-, y la cantidad de las que son de terapia intensiva -11.517-**

De acuerdo al último artículo → camas terapia intensiva (ICU beds - intensive care unit beds) cada 100K = 25.29 (11.517 \* 100.000 / 45.536.070)

[https://www.lanacion.com.ar/sociedad/coronavirus-escenario-mas-temido-colapsaran-unidades-terapia-nid2382059](https://www.lanacion.com.ar/sociedad/coronavirus-escenario-mas-temido-colapsaran-unidades-terapia-nid2382059)

Más datos:

[https://ourworldindata.org/grapher/hospital-beds-per-1000-people](https://ourworldindata.org/grapher/hospital-beds-per-1000-people)

[https://www.indexmundi.com/g/r.aspx?v=2227&amp;l=es](https://www.indexmundi.com/g/r.aspx?v=2227&amp;l=es)

[owid/covid-19-data · GitHub](https://github.com/owid/covid-19-data/tree/master/public/data/) (este dataset posee **hospital\_beds\_per\_100k)**

## Testeos

[Infectólogos argentinos advierten que para tener una tasa eficaz de letalidad del COVID-19 hay que incrementar los testeos](https://www.infobae.com/america/tendencias-america/2020/04/22/infectologos-argentinos-advierten-que-para-tener-una-tasa-eficaz-de-letalidad-del-covid-19-hay-que-incrementar-los-testeos/)

En este contexto, la **secretaria de Acceso a la Salud, Carla Vizzotti,** viene sosteniendo en su reporte matutino que el dispositivo de salud público y privado no está tensionado ya que hay unos 120 pacientes en unidades de terapia intensiva mientras que la mitad del total de las camas críticas en el país (unas 8.500) están disponibles.

**A la vez, hasta el momento son 840 las personas dadas de alta, lo que representa 27% del total de casos confirmados, mientras que la tasa de letalidad, es decir la cantidad de fallecimientos (151) sobre el total de confirmados (3144) por 100, asciende a 4,80% y la tasa de mortalidad (se divide el número de fallecidos por la enfermedad por la cifra de población total del país y se multiplica por 1 millón) que es de 3,3 casos sobre millón de habitantes, según datos del Ministerio de Salud.**

**Corea del Sur es otro ejemplo** de cómo un país puede controlar las infecciones. Además del aislamiento social, aplicó una estrategia de test masivos a la población (ya realizó más de medio millón). Así, la cantidad de test realizados de Corea **para detectar el coronavirus es de 11.100 por millón de habitantes, una de las más altas del mundo.** En **Alemania** se realizaron más de 1,7 millones, a razón de **20.600 por millón de habitantes. Muy alto para los 810 de Argentina.**

Hasta hoy, Chile ha realizado 122.300 tests, es decir 6400 por millón de habitantes. Ecuador, donde la pandemia está causando estragos, ha realizado 33.389 pruebas, a razón de 1892 por millón de personas. Uruguay, testeó a casi 14.000 personas, es decir 4000 test por millón. Perú, examinó a 155.724 habitantes, a razón de 4723 por millón. Brasil hizo pruebas a 291.000 personas, lo que significa 1373 por millón de habitantes. Colombia, con una población similar a la nuestra, hizo 65.200 test, es decir 1281 por millón de personas.

La proporción de tests de coronavirus por millón de habitantes de Argentina (810) se asemeja a la de países como Granada (818), Trinidad y Tobago (995), Guinea (762) o Paraguay (824).

### Test per day dataset

[To understand the global pandemic, we need global testing – the Our World in Data COVID-19 Testing dataset](https://ourworldindata.org/covid-testing)

### Why is data on testing important?

No country knows the total number of people infected with COVID-19. All we know is the infection status of those who have been _tested_. All those who have a lab-confirmed infection are counted as _confirmed cases_.

This means that the counts of confirmed cases depend on how much a country actually tests. **Without testing there is no data.**

Testing is our window onto the pandemic and how it is spreading. Without data on who is infected by the virus we have no way of understanding the pandemic. Without this data we can not know which countries are doing well, and which are just underreporting cases and deaths.

To interpret any data on confirmed cases we need to know how much testing for COVID-19 the country actually does.

- Dataset → [owid/covid-19-data · GitHub](https://github.com/owid/covid-19-data/tree/master/public/data/) (este dataset posee **hospital\_beds\_per\_100k)**
- Análisis en Excel (bajado del link de arriba y comentarios acerca de su cálculo) → [owid-covid-data.xlsx](https://docs.google.com/spreadsheets/d/1if8IaveKHGbrkGye3TGwa0MG8u-PPsyn/edit#gid=943723175)
- CSV → [https://covid.ourworldindata.org/data/owid-covid-data.csv](https://covid.ourworldindata.org/data/owid-covid-data.csv)

**total\_tests = acumulado de test realizados a la fecha**

**new\_tests = nuevos test hechos en esa fecha**

_**new\_tests\_smoothed = (**__total\_test / population) \* 1000 hab_

_**total\_tests\_per\_thousand = (new\_tests**_ _/ population) \* 1000 hab_

\*me parece que estan al reves estos 2 labels ya que de acuerdo a [owid-covid-data.xlsx](https://docs.google.com/spreadsheets/d/1if8IaveKHGbrkGye3TGwa0MG8u-PPsyn/edit#gid=943723175) → **total\_tests\_per\_thousand = (total\_tests** / population) \* 1000 hab

_ **new\_tests\_per\_thousand = ??** _

_**new\_tests\_smoothed\_per\_thousand = (new\_tests\_per\_thousand**_ _/ population) \* 1000 hab_ _(esto seria daily-tests-per-thousand-people-smoothed)_

_population = total\_test / total\_test\_per\_thousand \* 1000 → population (45536070 aprox ARG)_

Incluye además:

- total\_cases\_per\_million
- total\_deaths\_per\_million
- hospital\_beds\_per\_100k

En [owid-covid-data 2020-05-20](https://docs.google.com/spreadsheets/d/1r6LVzt8s2BB3H5BPCRd2iB3QmioVd5nucbfSCAiwLjU/edit?usp=sharing) se puede ver un gráfico de evolución de testeo (new\_test) por fecha

![](RackMultipart20200817-4-1njbqa1_html_c417ee97d279ad3f.png)

### Daily COVID-19 tests per thousand people

[https://ourworldindata.org/coronavirus-testing#argentina](https://ourworldindata.org/coronavirus-testing#argentina)

![](RackMultipart20200817-4-1njbqa1_html_734eba4e23c3c183.png)

[https://ourworldindata.org/grapher/daily-tests-per-thousand-people-smoothed-7-day?time=2020-04-15..&amp;country=~ARG](https://ourworldindata.org/grapher/daily-tests-per-thousand-people-smoothed-7-day?time=2020-04-15..&amp;country=~ARG)

### **Tests per case** : how many tests to find one COVID-19 case?

[https://ourworldindata.org/coronavirus-testing#tests-per-case-how-many-tests-to-find-one-covid-19-case](https://ourworldindata.org/coronavirus-testing#tests-per-case-how-many-tests-to-find-one-covid-19-case)

test per case = **average(new\_tests today - 7 days) / average(new\_cases today - 7 days)**

![](RackMultipart20200817-4-1njbqa1_html_829c3b9a9176a27a.png)

![](RackMultipart20200817-4-1njbqa1_html_6e987757d872f316.png)

![](RackMultipart20200817-4-1njbqa1_html_49748212bd97cffb.png)

Ver [owid-covid-data 2020-05-20](https://docs.google.com/spreadsheets/d/1r6LVzt8s2BB3H5BPCRd2iB3QmioVd5nucbfSCAiwLjU/edit?usp=sharing), libro &quot;Tests per case&quot;

### What can we learn from these measures about the pandemic?

[https://ourworldindata.org/coronavirus-testing#what-can-we-learn-from-these-measures-about-the-pandemic](https://ourworldindata.org/coronavirus-testing#what-can-we-learn-from-these-measures-about-the-pandemic)

# Infectious Disease Modelling: Understanding the models that are used to model Coronavirus

Los parámetros necesarios para calcular esto los debería poder obtener a partir del dataset mio de contagios con mobilidad

[https://www.lewuathe.com/covid-19-dynamics-with-sir-model.html](https://www.lewuathe.com/covid-19-dynamics-with-sir-model.html)

1. [Infectious Disease Modelling, Part I: Understanding SIR](https://towardsdatascience.com/infectious-disease-modelling-part-i-understanding-sir-28d60e29fdfc)
2. [Modelling Coronavirus: Beyond the SIR Model](https://towardsdatascience.com/infectious-disease-modelling-beyond-the-basic-sir-model-216369c584c4)
3. [Modelling Coronaviurs: Fit your model to real-world data](https://towardsdatascience.com/infectious-disease-modelling-fit-your-model-to-coronavirus-data-2568e672dbc7)
4. [Building an interactive dashboard to simulate Coronavirus scenarios in Python](https://towardsdatascience.com/building-an-interactive-dashboard-to-simulate-coronavirus-scenarios-in-python-ed23100e0046)
  1. [https://github.com/vackup/infectious\_disease\_modelling](https://github.com/vackup/infectious_disease_modelling)
  2. [https://cosim.herokuapp.com/](https://cosim.herokuapp.com/)

# Kaggle Predictions

- [https://www.kaggle.com/c/covid19-global-forecasting-week-3/notebooks?sortBy=hotness&amp;group=everyone&amp;pageSize=20&amp;competitionId=19853](https://www.kaggle.com/c/covid19-global-forecasting-week-3/notebooks?sortBy=hotness&amp;group=everyone&amp;pageSize=20&amp;competitionId=19853)
- [https://www.kaggle.com/c/covid19-global-forecasting-week-5](https://www.kaggle.com/c/covid19-global-forecasting-week-5) (muchos graficos interesantes y para usar de ejemplo)
  - [https://www.kaggle.com/dkjung/covid-19-eda-s-korea-forecasting-global](https://www.kaggle.com/dkjung/covid-19-eda-s-korea-forecasting-global)
  - [https://www.kaggle.com/eswarchandt/geospatial-analysis-on-covid-19-day-to-day-track](https://www.kaggle.com/eswarchandt/geospatial-analysis-on-covid-19-day-to-day-track)

# Other

[The end of exponential growth: The decline in the spread of coronavirus](https://www.timesofisrael.com/the-end-of-exponential-growth-the-decline-in-the-spread-of-coronavirus/)

[FastStats - Deaths and Mortality](https://www.cdc.gov/nchs/fastats/deaths.htm) → Influenza and Pneumonia: 55,672

[https://www.opengovpartnership.org/collecting-open-government-approaches-to-covid-19/](https://www.opengovpartnership.org/collecting-open-government-approaches-to-covid-19/)

[https://www.paho.org/arg/index.php?option=com\_content&amp;view=article&amp;id=10430:coronavirus&amp;Itemid=226](https://www.paho.org/arg/index.php?option=com_content&amp;view=article&amp;id=10430:coronavirus&amp;Itemid=226)

[https://www.google.com/search?rlz=1C1GCEA\_enAR875AR875&amp;sxsrf=ALeKk03KYJXNWzi6SMgI8HeEaZlppXk9oA%3A1587139864952&amp;ei=GNWZXuXNOby-5OUP8o28kAI&amp;q=buenos+aires+uso+de+subtes+dataset&amp;oq=buenos+aires+uso+de+subtes+dataset&amp;gs\_lcp=CgZwc3ktYWIQAzIECAAQRzIECAAQRzIECAAQRzIECAAQRzIECAAQRzIECAAQRzIECAAQRzIECAAQR1C6B1jVDWDgDmgAcAJ4AIABAIgBAJIBAJgBAKABAaoBB2d3cy13aXo&amp;sclient=psy-ab&amp;ved=0ahUKEwjlue\_e7O\_oAhU8H7kGHfIGDyIQ4dUDCAw&amp;uact=5](https://www.google.com/search?rlz=1C1GCEA_enAR875AR875&amp;sxsrf=ALeKk03KYJXNWzi6SMgI8HeEaZlppXk9oA%3A1587139864952&amp;ei=GNWZXuXNOby-5OUP8o28kAI&amp;q=buenos+aires+uso+de+subtes+dataset&amp;oq=buenos+aires+uso+de+subtes+dataset&amp;gs_lcp=CgZwc3ktYWIQAzIECAAQRzIECAAQRzIECAAQRzIECAAQRzIECAAQRzIECAAQRzIECAAQRzIECAAQR1C6B1jVDWDgDmgAcAJ4AIABAIgBAJIBAJgBAKABAaoBB2d3cy13aXo&amp;sclient=psy-ab&amp;ved=0ahUKEwjlue_e7O_oAhU8H7kGHfIGDyIQ4dUDCAw&amp;uact=5)

[http://lppargentina.org.ar/subtedata/mira-como-se-movio-el-subte-en-2016/](http://lppargentina.org.ar/subtedata/mira-como-se-movio-el-subte-en-2016/)

[http://lppargentina.org.ar/subtedata/](http://lppargentina.org.ar/subtedata/)

[https://data.buenosaires.gob.ar/dataset?groups=movilidad](https://data.buenosaires.gob.ar/dataset?groups=movilidad)

[https://data.buenosaires.gob.ar/dataset/subte-viajes-molinetes/archivo/a43d8d7e-0e5e-4706-853b-303f567d82d0](https://data.buenosaires.gob.ar/dataset/subte-viajes-molinetes/archivo/a43d8d7e-0e5e-4706-853b-303f567d82d0)

[https://data.buenosaires.gob.ar/dataset/flujo-vehicular-por-radares-ausa/archivo/66bbccae-d6e0-43f4-b874-dbdece04dfd1](https://data.buenosaires.gob.ar/dataset/flujo-vehicular-por-radares-ausa/archivo/66bbccae-d6e0-43f4-b874-dbdece04dfd1)

[https://cuchu.github.io/covid-19/](https://cuchu.github.io/covid-19/)

[https://www.infobae.com/salud/2020/08/07/coronavirus-en-argentina-por-que-en-140-dias-de-cuarentena-obligatoria-no-bajo-nunca-la-curva-de-casos/](https://www.infobae.com/salud/2020/08/07/coronavirus-en-argentina-por-que-en-140-dias-de-cuarentena-obligatoria-no-bajo-nunca-la-curva-de-casos/)
