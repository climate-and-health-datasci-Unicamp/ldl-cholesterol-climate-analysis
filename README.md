# Como ondas de frio influenciam os níveis de colesterol ldl?
# How cold waves influence ldl cholesterol levels?

# Descrição Resumida do Projeto

Descreva resumidamente o que fará o projeto. O resumo idealmente deve: apresentar o contexto; indicar o problema; 
apresentar a sua solução para o problema; indicar porque a sua solução é melhor do que os esforços atuais (não obrigatório);
concluir com os resultados alcançados.

# Abstract 

English version of the abstract.

# Equipe
* [Daniela Souza de Oliveira](https://github.com/Danielaso) - 155099
* [Júlia Perassolli De Lázari](https://github.com/juliaplazari) - 200298
* [Thiago Ribas Bella](https://www.linkedin.com/in/thiago-ribas-bella-016380149/) - 157414
* [Welington Corozolla](https://www.linkedin.com/in/welington-corozolla-7b820b92/) - 188894


# Project Video
[Project proposal video](https://drive.google.com/file/d/16P_fglul0e5NVvD1JWwW9koR-nYbb1sx/view)

# Introduction
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The reports of the Brazilian Panel on Climate Change (PBMC) and the Intergovernmental Panel on Climate Change (IPCC) were unanimous in revealing that South America and Brazil already have records of climate change predicted in climate models (1) and highlight that the changes associated with global warming can alter the frequency, intensity, duration and timing of extreme events, resulting in extreme environmental conditions, even never seen before (2). The World Health Organization (WHO) concluded that these climate changes should cause approximately 250,000 additional deaths per year between 2030 and 2050 (3). 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The World Health Organization (WHO) concluded that climate change is expected to cause approximately 250,000 additional deaths per year between 2030 and 2050 (3). Studies show that the impacts of climate change are disproportionately affecting the health of populations, and especially of the vulnerable population (4). 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Cardiovascular diseases (CVD) are drastically affected by environmental changes, and this makes it extremely important to understand how and what are the components of the environment that increase cardiovascular risk (5,6).

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Classified as the leading cause of death in the world, CVDs represent almost 32% of all causes of death in women and 27% in men (7). Low temperature-related mortality places a major burden on public health spending (8) and cardiovascular events, such as acute myocardial infarction (AMI) and stroke, present a seasonal pattern, with higher rates in winter than in other seasons (9,10). In the northern and southern hemispheres, cholesterol concentrations of low-density lipoprotein (LDL-C), also popularly known as “bad cholesterol” are slightly higher in winter when compared to other seasons (11,12) and plasma lipids and lipoproteins are essential components in the pathogenesis and progression of atherosclerosis (a chronic inflammatory disease that affects the wall of large and medium-sized arteries, characterized by a long asymptomatic phase (which can last for decades) resulting from the accumulation of lipids), especially those situations of increased LDL-C (13).

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The formation of atherosclerotic plaque begins with the aggression to the vascular endothelium by several risk factors, such as dyslipidemia (increased or reduced concentrations of lipids or lipoproteins), hypertension or smoking. As a consequence, endothelial dysfunction increases the permeability of the intima layer to plasma lipoproteins, favoring their retention in the subendothelial space. Retained, the LDL particles undergo oxidation, causing the exposure of several neoepitopes, making them immunogenic. The deposition of lipoproteins in the arterial wall, a key process at the beginning of atherogenesis, occurs in proportion to the concentration of these lipoproteins in the plasma (13).

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Even in patients at low risk for cardiovascular disease, studies suggest that LDL-C at concentrations above the reference value (≥160 mg/dL) is associated with a 50% increase in the relative risk of CVD mortality (14), large clinical trials indicate that the reduction of LDL-C by 1 mmol/L (± 39 mg/dL) would reduce the risk for some cardiovascular outcomes by 22% (15) and that the 20 °C variation in air temperature may result in a change of about 20% in plasma lipid levels (16).

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; In a scenario where the effects of climate change and the frequency of extreme events make it more evident and intense, there is an urgent need to investigate and develop analytical tools and predictive models that reveal their effects on human health, as well as being able to provide information accessible to health professionals and public health policymakers, which can be used as indicators to define strategies for the perception of the problem by society and for the implementation of actions to prevent and mitigate its pathological effects.	

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; In this context, this study aimed to analyse the impact of cold waves on LDL-C concentrations of patients who sought medical care at basic health units (UBS) in the city of Campinas-SP, from 2008 to 2018, comprising an 11-year time series. Additionally, we modelled historical weather data and used climate models to predict the occurrences of cold waves in the future.


# Research Question
**Question:** Does cold waves increase LDL-C levels?

**Null Hypothesis:** Cold waves do not increases LDL-C levels.

**Hypothesis:** Cold waves increases LDL-C levels.

# Objective
To assess the impact of cold waves on LDL-C concentrations in patients who sought medical attention in Campinas-SP, from 2008 to 2018.

# Resources

## Database

Database | Web Address | Description and Usage
----- | ----- | -----
Campinas Municipal Laboratory | https://bit.ly/CML-database | `<Descrição da Base 1 e para que ela foi usada no projeto.>`
Agronomic Institute of Campinas | https://bit.ly/cold_wave_IAC | `<Descrição da Base 2 e para que ela foi usada no projeto.>`
Agronomic Institute of Campinas | https://bit.ly/heat_wave_IAC | `<Descrição da Base 2 e para que ela foi usada no projeto.>`
Projections from ETA | https://bit.ly/ETA_TMIN | `<Descrição da Base 2 e para que ela foi usada no projeto.>`
Projections from ETA | https://bit.ly/ETA_TMAX | `<Descrição da Base 2 e para que ela foi usada no projeto.>`

## Tools

Tool | Web Address | Description and Usage
----- | ----- | -----
Google Colab | https://colab.research.google.com | `<Descrição da Ferramenta 1 e para que ela foi usada no projeto.>`


# Material and Methods
## 2.1 - Database
### 2.1.1 - Biological data 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; LDL-C concentrations data from the Campinas Municipal Laboratory of Clinical Pathology (LMC-Campinas) between the years 2008 to 2018, where laboratory tests are performed on individuals seen at 63 basic health units in Campinas.

### 2.1.2 - Weather data

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The database used in this work consisted of daily minimum (Tmin) and maximum temperatures (Tmax) from the weather station of the Agronomic Institute of Campinas (located at latitude 22°52’ S and longitude 47°4’ W) from 1989 to 2018. First, to estimate the impact of cold waves on LDL-C concentrations, data from the period of 2000 - 2018 was used. Further, the whole period was used to forecast the temperature time series.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Daily Tmax and Tmin projections for the period of 2018 - 2050 (Latitude: 22°51' S, Longitude: 47°3' W) were obtained from the regionalized ETA climate model available on the [PROJETA platform](https://projeta.cptec.inpe.br/) for the climatic scenario: 05 km, RCP4.5, sudesteD2-BR, HADGEM2-ES.

## 2.2 - Cold waves definition

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Cold waves were defined as at least 3 consecutive days with Tmin and Tmax below its 10th percentiles. We calculated the percentiles (P10-Tmin and P10-max) for each day using the historical time series from 1961 to 1990 and a time window of 15 days, centered in the day of interest. For example, to calculate the P10-Tmin for 08/01 we used a time window from 01/01 to 15/01, for all 30 years in the historical series (see [suppl.](https://github.com/climate-and-health-datasci-Unicamp/ldl-cholesterol-climate-analysis/blob/master/references/How_do_we_calculate_thermal_waves.docx?raw=true)).

## 2.3 - Stratification
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Patients were stratified into different age groups: young (<20 years old), adults (20 - 65 years old), Elderly (>65 years old), Male and Female.

## 2.4 - Statistical analysis 	

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; We separated the data into two groups: days under influence of a cold wave and control days. Control days were defined as the ones without influence of hot or cold waves. We used a density probability plot to analyse the percentage of exams with LDL-C above reference level. We applied the Mann Whitney U test, a nonparametric test, to compare these groups because our data distribution was not normal. We also compared the control group with stratified LDL-C results collected k days after a cold spell, with k ranging from 0 to 10, in order to analyse retarded effects of the cold wave.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; All analysis were done using Python and the libraries scipy, numpy, pandas, matplotlib and statsmodels.

## 2.5 - Cold waves forecasting

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; In order to estimate the occurrences of cold waves in the future, we applied two different approaches: (1) use of historical data from IAC weather station to model future climate data; (2) use of data from the ETA regionalized model for geographic coordinates near IAC.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; For the first method, we divided the data in training (1989 to 2013) and test datasets (2014 - 2018) and converted into weekly aggregation. Seasonal ARIMA (Auto-Regressive Integrated Moving Average) was applied to the training set, using the AIC criterion to choose the best model and selecting a period of 52 weeks to account for data yearly seasonality. After the implementation of the model for both maximum and minimum temperatures, we calculated the error between the original data and the test set and estimated the daily temperatures for the next 10 years (2019 to 2028). Using the predicted temperatures, we applied the algorithm for detection of cold waves. Noise was also added to the model to make it more realistic.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; For the second method, we computed cold waves using daily temperature data obtained from the ETA climate model. Cold wave metrics of quantity (CWN - number of cold wave events per year), duration (CWD - longest duration in days of cold waves per year) and frequency (CWF - number of days under cold waves per year) were generated considering historical data (2008 - 2018) and projections (2019 - 2050).


# Evolução do Projeto
~~~
<Relate a evolução do projeto: possíveis problemas enfrentados e possíveis mudanças de trajetória. Relatar o processo para se alcançar os resultados é tão importante quanto os resultados.>
~~~

# Resultados e Discussão
~~~
<Apresente os resultados da forma mais rica possível, com gráficos e tabelas. Mesmo que o seu código rode online em um notebook, copie para esta parte a figura estática. A referência a código e links para execução online pode ser feita aqui ou na seção de detalhamento do projeto (o que for mais pertinente).

A discussão dos resultados também pode ser feita aqui na medida em que os resultados são apresentados ou em seção independente. Aspectos importantes a serem discutidos: É possível tirar conclusões dos resultados? Quais? Há indicações de direções para estudo? São necessários trabalhos mais profundos?>
~~~

# Conclusões
~~~
<Apresente aqui as conclusões finais do trabalho e as lições aprendidas.>
~~~

# Trabalhos Futuros
~~~
<Indique trabalhos futuros a partir do ponto alcançado.>
~~~
