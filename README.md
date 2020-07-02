# How cold waves influence ldl cholesterol levels?

# Abstract 

**Introduction:** Cardiovascular diseases (CVD) are drastically affected by environmental changes, and this makes it extremely important to understand how its deleterious health effects happen and identify possible vulnerable populations. Higher concentrations of low-density lipoprotein (LDL-C) are found in periods of lower temperatures, and this acts directly in the formation of atherosclerotic plaques. **Objectives:** To assess the impact of cold waves on LDL-C concentrations in patients who sought medical attention in Campinas-SP, from 2008 to 2018. Our secondary aim was to predict future cold waves. **Methods:** Results of LDL-C exams, from the Campinas Municipal Laboratory and data of minimum and maximum air temperature (°C) were evaluated. Cold waves were defined as at least 3 consecutive days with Tmin and Tmax below its 10th percentiles, considering temperature data from 1961 to 1990. The data were stratified into sex and age groups. We separated the data into cold wave and control days and compared LDL-C levels above reference value (LARV) using Mann-Whitney U and probability density plots. We also compared the control group with lags from 0 to 10 to analyse retarded effects of the cold wave. Regarding the prediction of cold waves, we modelled historical weather data using an auto-regressive model and used a regional climate model (ETA)  to predict the occurrences of cold waves in the future. **Results:** In the evaluated period, 9 cold waves were found, which impacted an increase of 3.32% more people with LARV in the group of adult women for lag 2, 9.27% for elderly women in lag 0  and 11.45% for elderly men in lag 4.  Prediction of cold waves using historical data is computationally expensive and inaccurate if time series residues are not considered. Use of a regionalized climate model showed better results. Conclusion: These analyses point to the influence of cold waves on LDL-C concentrations in adult women and also in elderly men and women. Cold waves tend to be less frequent in the future.

# Como ondas de frio influenciam os níveis de colesterol ldl?

# Resumo

**Introdução:** As doenças cardiovasculares (DCV) são drasticamente afetadas pelas mudanças ambientais, e isso torna extremamente importante entender como seus efeitos deletérios à saúde acontecem e identificar possíveis populações vulneráveis. Maiores concentrações de lipoproteína de baixa densidade (LDL-C) são encontradas em períodos de temperaturas mais baixas, e isso atua diretamente na formação de placas ateroscleróticas. **Objetivo:** Avaliar o impacto das ondas de frio nas concentrações de LDL-C em pacientes que procuraram atendimento médico em Campinas-SP, de 2008 a 2018. Estabelecemos como objetivo secundário a predição de ondas de frio. **Métodos:** Foram avaliados os resultados dos exames de LDL-C, do Laboratório Municipal de Campinas, e os dados de temperatura mínima (Tmin) e máxima (Tmax) do ar (°C). Ondas de frio foram definidas como pelo menos 3 dias consecutivos com Tmin e Tmax abaixo de seus percentis 10, considerando dados de temperatura de 1961 a 1990. Os dados foram estratificados em sexo e faixa etária. Separamos os dados em dias de onda de frio e dias controle e comparamos os níveis de LDL-C acima do valor de referência (AVR), usando o teste U de Mann-Whitney e gráficos de densidade de probabilidade. Também comparamos o grupo controle com efeito lag de 0 a 10 dias para analisar os efeitos de atraso da onda de frio. Em relação à predição das ondas de frio, foi feita uma modelagem dos dados climáticos históricos por meio de um modelo auto-regressivo. Além disso, utilizamos um modelo climático regional (ETA) para prever as próximas ocorrências de ondas de frio. **Resultados:** No período avaliado, foram encontradas 9 ondas de frio, o que impactou em um aumento de 3,32% a mais de pessoas com os níveis de LDL-C AVR no grupo de mulheres adultas para o lag 2, 9,27% para idosas no lag 0 e 11,45% para homens idosos no lag 4.  Predição de ondas de frio utilizando dados históricos tem um elevado custo computacional e pode ser ineficaz caso os resíduos da série temporal não sejam considerados. O modelo climático regionalizado mostrou melhores resultados. Conclusão: Essas análises apontam para a influência das ondas de frio nas concentrações de LDL-C em mulheres adultas e também em homens e mulheres idosos. As ondas de frio tendem a ser menos frequentes no futuro.

# Team
* [Daniela Souza de Oliveira](https://github.com/Danielaso)<sup>a, b</sup> - 155099
* [Júlia Perassolli De Lázari](https://github.com/juliaplazari)<sup>b</sup> - 200298
* [Thiago Ribas Bella](https://www.linkedin.com/in/thiago-ribas-bella-016380149/)<sup>b, c</sup> - 157414
* [Welington Corozolla](https://www.linkedin.com/in/welington-corozolla-7b820b92/)<sup>c</sup> - 188894

<sup>a</sup> *Center for Meteorological and Climatic Research Applied to Agriculture - UNICAMP, Brasil*

<sup>b</sup> *Department of Computer Engineering and Industrial Automation - FEEC/UNICAMP, Brasil*

<sup>c</sup> *Department of clinical pathology - FCM/UNICAMP, Brasil*


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
**Question:** Do cold waves increase LDL-C levels?

**Null Hypothesis:** Cold waves do not increase LDL-C levels.

**Hypothesis:** Cold waves increase LDL-C levels.

# Objective
To assess the impact of cold waves on LDL-C concentrations in patients who sought medical attention in Campinas-SP, from 2008 to 2018. Our secondary aim was to predict future cold waves.

# Resources

## Database

Database | Web Address | Description and Usage
----- | ----- | -----
Campinas Municipal Laboratory | https://bit.ly/CML-database | Database with LDL-c concentrations data from LMC-Campinas (2008-2018)
Agronomic Institute of Campinas | https://bit.ly/cold_wave_IAC | Database with cold waves using IAC data (1961 - 2018)
Agronomic Institute of Campinas | https://bit.ly/heat_wave_IAC | Database with heat waves using IAC data (1961 - 2018)
Projections from ETA | https://bit.ly/ETA_TMIN | Database with predicted minimum temperatures from PROJETA (2019 - 2050) - ETA 5km RCP4.5, sudesteD2-BR, HADGEM2-ES 
Projections from ETA | https://bit.ly/ETA_TMAX | Database with predicted maximum temperatures from PROJETA (2019 - 2050) - ETA 5km RCP4.5, sudesteD2-BR, HADGEM2-ES

## Tools

Tool | Web Address | Description and Usage
----- | ----- | -----
Google Colab | https://colab.research.google.com | Jupyter notebooks environment from google, used to write shared scripts

# Material and Methods
## Database
### Biological data 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; LDL-C concentrations data from the Campinas Municipal Laboratory of Clinical Pathology (LMC-Campinas) between the years 2008 to 2018, where laboratory tests are performed on individuals seen at 63 basic health units in Campinas.

### Weather data

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The database used in this work consisted of daily minimum (Tmin) and maximum temperatures (Tmax) from the weather station of the Agronomic Institute of Campinas (located at latitude 22°52’ S and longitude 47°4’ W) from 1961 to 2018. First, to estimate the impact of cold waves on LDL-C concentrations, data from the period of 2008 to 2018 was used. Further, the period of 1989 to 2018 was used to forecast the temperature time series. The detection of cold waves was based on the data from 1961 - 1990 (climatological normal).

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Daily Tmax and Tmin projections for the period of 2018 - 2050 (Latitude: 22°51' S, Longitude: 47°3' W) were obtained from the regionalized ETA climate model available on the [PROJETA platform](https://projeta.cptec.inpe.br/) for the climatic scenario: 05 km, RCP4.5, sudesteD2-BR, HADGEM2-ES.

## Cold waves definition

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Cold waves were defined as at least 3 consecutive days with Tmin and Tmax below its 10th percentiles. We calculated the percentiles (P10-Tmin and P10-max) for each day using the historical time series from 1961 to 1990 and a time window of 15 days, centered in the day of interest. For example, to calculate the P10-Tmin for 08/01 we used a time window from 01/01 to 15/01, for all 30 years in the historical series (see [supplement](https://github.com/climate-and-health-datasci-Unicamp/ldl-cholesterol-climate-analysis/blob/master/references/How_do_we_calculate_thermal_waves.docx?raw=true)).
We used a Python library to compute cold waves, Extreme_Waves.py, which is available at https://drive.google.com/drive/folders/1CD77t_5z8YKMxb8gDDrKp9MOsE8SBqaC?usp=sharing. 

## Stratification
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Patients were stratified into different age groups: young (<20 years old), adults (20 - 65 years old), Elderly (>65 years old), Male and Female.

## Statistical analysis 	

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; We separated the data into two groups: days under influence of a cold wave and control days. Control days were defined as the ones without influence of hot or cold waves. We used a density probability plot to analyse the percentage of exams with LDL-C above reference level. We applied the Mann Whitney U test, a nonparametric test, to compare these groups because our data distribution was not normal. We also compared the control group with stratified LDL-C results collected k days after a cold spell, with k ranging from 0 to 10, in order to analyse retarded effects of the cold wave.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; All analysis were done using Python and the libraries scipy, numpy, pandas, matplotlib and statsmodels.

## Cold waves forecasting

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; In order to estimate the occurrences of cold waves in the future, we applied two different approaches: (1) use of historical data from IAC weather station to model future climate data; (2) use of data from the ETA regionalized model for geographic coordinates near IAC.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; For the first method, we divided the data in training (1989 to 2013) and test datasets (2014 - 2018) and converted it into weekly aggregation. Seasonal ARIMA (Auto-Regressive Integrated Moving Average) was applied to the training set, using the Akaike information criterion (AIC) to choose the best model and selecting a period of 52 weeks to account for data yearly seasonality. After the implementation of the model for both maximum and minimum temperatures, we calculated the error between the original data and the test set and estimated the daily temperatures for the next 10 years (2019 to 2028). Using the predicted temperatures, we applied the algorithm for detection of cold waves. Noise was also added to the model to make it more realistic.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; For the second method, we computed cold waves using daily temperature data obtained from the ETA climate model. Cold wave metrics of quantity (CWN - number of cold wave events per year), duration (CWD - longest duration in days of cold waves per year) and frequency (CWF - number of days under cold waves per year) were generated considering historical data (2008 - 2018) and projections (2019 - 2050).

# Results and Discussion

## Stratified statistical analysis

The analysis can be found at the [notebook](https://github.com/climate-and-health-datasci-Unicamp/ldl-cholesterol-climate-analysis/blob/master/notebooks/03_LDL_above_average.ipynb)

### Young (<20 years)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Exclusively the female group showed significant differences for our analysis, being them on lags 2, 7 and 9. Intriguingly, the difference between the group on cold waves and the control showed peculiar results, suggesting that the group under cold waves has lower number of people with LDL-C concentrations above reference value when compared to the control group: -11.42%, -7.43% and -8.17% for lags 2, 7 and 9 respectively. Numerous mechanisms of lipid transport and metabolism may be involved. It is known that children and adolescents undergo considerable sex-specific changes during physical growth and sexual maturation and differ significantly between pubertal stages. This phase is marked by metabolic instability with large hormonal fluctuations in growth and sexual maturation, directly affecting lipid and lipoprotein concentrations (17). It is likely that this group is not influenced by thermal stress under cold waves, but there is nothing clear in the literature to corroborate these findings.

| SUBSET 	| lag 	| Cold 	| n1 	| Nor. 	| n2 	| Diff 	| p  	|
|:-:	|:-:	|-	|-	|-	|-	|-	|-	|
| Under 20 female 	| 2 	| 25.58 	| 83 	| 37.00 	| 18771  	| -11.42 	| 0.017 	|
| Under 20 female 	| 7 	| 29.57 	| 106 	| 37.00 	| 18771 	| -7.43 	| 0.012 	|
| Under 20 female 	| 9 	| 28.82 	| 99 	| 37.00 	| 18771 	| -8.17 	| 0.021 	|

### Adults (20-65 years) 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Significant difference was found only for lag 2. This indicates that the physiological response of the group had greater proportions two days after the beginning of the wave. The group under cold waves showed a higher number of people (3.32% more) with LDL-C concentrations above reference value, when compared to the control group.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; We emphasize that only the female group presented a significant difference in our analysis, showing that they are more susceptible to cold waves. The possible mechanism behind these findings is related to the cardioprotective function of testosterone present in higher concentrations in male group. Testosterone levels are inversely correlated with LDL-C and recent epidemiological studies indicate that low serum testosterone levels are associated with more atherosclerotic and CVD events (18,19).

| SUBSET 	| lag 	| Cold 	| n1 	| Nor. 	| n2 	| Diff 	| p  	|
|:-:	|:-:	|-	|-	|-	|-	|-	|-	|
| Between 20 and 65 female 	| 2 	| 46.88 	| 879 	| 43.56 	| 157878 	| 3.32 	| 0.004 	|

### Elderly (>65 years) 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; For females, significant difference, 9.27%, 7.39% and 4.06%, was found for lags 0, 2 and 7, respectively. These findings indicate that the physiological outcomes in response to thermal stress caused by the cold wave start simultaneously. It is worth mentioning that the physiological response continues to happen until the seventh day after the beginning of the cold wave. The male group exhibits significant difference only for lag 4.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; By aging the deterioration of the organism damages several functions necessary for the survival and adaptation to the environment and its oscillations (20).

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; In addition to functional limitations, such as a decline in muscle strength, coordination and cognitive function due to illness, chronic illness or injury, changes in concentrations of growth hormone, adrenocorticotropic, thyroid-stimulating, dehydroepiandrosterone and aldosterone hormones occur; there is also loss of skeletal striated muscles that may reduce basal metabolic rate in men and women (21). Ovarian secretion of estrogen in women, and to a lesser extent, of androgen, decrease abruptly from the sixth decade of life; also, from the 75 years of age, serum concentrations of follicle stimulating hormone and luteinizing hormone gradually decline (21,22). For males, the testicular function gradually declines with increasing age, with reduction in concentrations of serum and total and free testosterone (21,23).

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;It should be emphasized that with advancing age, the metabolism reduces its plasticity and the ability to maintain homeostasis in response to climatic variations (24,25), calling attention and highlighting possible risk groups, the elderly women.

| SUBSET 	| lag 	| Cold 	| n1 	| Nor. 	| n2 	| Diff 	| p  	|
|:-:	|:-:	|-	|-	|-	|-	|-	|-	|
| Over 65 male 	| 4 	| 47.26 	| 87 	| 35.81 	| 40448 	| 11.45 	| 0.025 	|
| Over 65 female 	| 0 	| 52.76 	| 253 	| 43.49 	| 52007 	| 9.27 	| 0.000 	|
| Over 65 female 	| 2 	| 50.89 	| 228 	| 43.49 	| 52007 	| 7.39 	| 0.016 	|
| Over 65 female 	| 7 	| 47.55 	| 290 	| 43.49 	| 52007 	| 4.06 	| 0.026 	|

## Forecasting of Cold waves

### Modeling historical data from IAC

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; After converting training (1989 - 2013) and test (2014 - 2018) datasets of daily temperatures (maximum and minimum) into weekly aggregation, we performed a search using ‘auto-arima’ function in Python and selected the parameters for our model according to the best (smaller) AIC. A SARIMA model has seven hyper-parameters, three are trend parameters (p, d, q) and four are seasonal parameters (P, D, Q, S). The S was chosen according to the yearly seasonality of our data (S = 52 weeks). Two models were generated, one for Tmax and another for Tmin, and the search resulted in the same parameters for both models: (1,1,1)x(0,1,1,52).  After implementing the model, we found AIC for Tmax equal to 5252 and for Tmin equal to 4266. When the model predictions were compared to the test dataset we found mean squared errors of 2.52  and 1.72, respectively, for Tmax and Tmin.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Further, we used the generated models to estimate the daily temperatures for the next 10 years (2019 to 2028), using interpolation to convert data back to daily. With the predicted temperatures, we applied the algorithm for detection of cold waves using the climatological normal of 1961 - 1990 which resulted in no cold waves because our model did not consider the data residues. Due to this problem, we decided to add a random noise to the data, to check if we could detect cold waves. The noise was estimated from the data and added to the temperature time series. After that, the computation of cold waves was successful.


### ETA regionalized model

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; After computation of cold waves using the projections of daily temperature data obtained from ETA regionalized climate (2019 - 2050), the annual cold wave metrics were calculated (CWN, CWD and CWF). Those metrics are presented in the following figures, along with the cold wave metrics from 2008 - 2018 in order to provide a comparison between those periods. Analysing the metrics, we can observe longer periods with an absence of cold waves (12 years, 2017 - 2028 and 8 years, 2035 - 2042) in comparison to the beginning of the time series. There is also a reduction in the number of cold waves and in the total sum of days under cold waves along the years. The duration of cold waves is higher in the first years of the series (2010 and 2011) and then it becomes stable. In summary, our results show that in the future there might be a reduction in the frequency and the number of cold waves.

![image](reports/figures/CWN.png?raw=true)

![Alt text](reports/figures/CWF.png?raw=true)


## Additional considerations

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Changes in lipid concentrations in the cold are often associated with the difference in energy intake from food in different seasons. However, this is a reductionist simplification, since the influence of dietary cholesterol on cholesterolemia is complex (24). Human beings produce cholesterol endogenously and about 25% of serum cholesterol comes from diet and the rest from cell biosynthesis (26–28).

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Several mechanisms are involved in the differences in lipid concentration. Exposure to cold causes physiological changes, such as adaptive thermogenesis. This mechanism promotes energy dissipation in the form of heat by external stimuli, being involved in the energy balance and in the regulation of body temperature. In short, the energy generated in the mitochondria during the Krebs cycle gains an “alternative path”, preventing the generation of ATP (adenosine triphosphate) and allowing this energy to be dissipated in heat (29,30). This regulatory mechanism is extremely efficient, but it triggers high metabolic rates that can adversely modify lipid and lipoprotein concentrations, such as LDL-C (29).

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The impact of cold waves on LDL-C can influence the increase in cardiovascular risk in colder months (12) and can also influence the treatment of patients who have been diagnosed with dyslipidemia close to periods that have cold waves, the patient can be classified as Normal or Pathological if his lipid profile is evaluated during a cold wave. This can cause additional costs to the Health System unnecessarily.


# Project evolution

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Initially we only intended to assess the influence of cold waves on LDL-C concentrations but afterwards we decided to work with predictive climate models in order to estimate the impact of our findings in the next years. One of our difficulties was related to producing these models, to predict daily data is computationally expensive, and we had to add noise to the model, so we could predict the next cold waves.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; We also intended to analyze the impact of each cold wave, to then relate it with the predictive models, but our data was insufficient to perform such analysis.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; We had the intention to conduct a similar analysis to assess the influence of high thermal amplitude on LDL-C concentrations. Days with thermal amplitude above the 90th percentile, based on the historical series, were considered high thermal amplitude days. The results indicated a lower percentage of LARV for days with high thermal amplitude, which was not the expected as it differed from the literature. We concluded that in order to perform a good analysis, we needed to consider more factors (quais? Se puder) and for this reason we chose to focus the analysis only on the cold waves.

# Conclusions

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Cold waves have an adverse influence on LDL-C concentrations in vulnerable groups, such as adult women, elderly men and elderly women. These findings can be used to alert health experts when making treatment decisions and diagnosing patients. Predicted cold waves found in our analyses may impact LDL-C concentrations in the future and, at the same time, cardiovascular risk. Being able to estimate the next occurrences of cold waves can help in the development of early warning systems.

# Future research

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Based on our findings, some future research that could be done is to improve the climate model based on historical data by modeling the noise of the time series; to use a predictive model to estimate the impact of cold waves in the LDL-C concentrations; and to reproduce this analysis for other lipid parameters.

# References
1. M do MA. Plano Nacional de Adaptação à Mudança do Clima. Volume 1 - Estratégia Geral [Internet]. Vol. I. 2016. 46 p. Available from: http://www.mma.gov.br/images/arquivo/80182/PNA_Volume I.pdf

2. Field CB, Barros V, Stocker TF, Dahe Q, Jon Dokken D, Ebi KL, et al. Managing the Risks of Extreme Events and Disasters to Advance Climate Change Adaptation [Internet]. Field CB, Barros V, Stocker TF, Dahe Q, editors. Vol. 9781107025, Managing the Risks of Extreme Events and Disasters to Advance Climate Change Adaptation: Special Report of the Intergovernmental Panel on Climate Change. Cambridge: Cambridge University Press; 2012. 1–582 p. Available from: http://ebooks.cambridge.org/ref/id/CBO9781139177245

3. WHO WHO. Climate change and health [Internet]. 2018. Available from: https://www.who.int/en/news-room/fact-sheets/detail/climate-change-and-health

4. Watts N, Amann M, Ayeb-Karlsson S, Belesova K, Bouley T, Boykoff M, et al. The Lancet Countdown on health and climate change: from 25 years of inaction to a global transformation for public health. Lancet [Internet]. 2018 Feb;391(10120):581–630. Available from: https://linkinghub.elsevier.com/retrieve/pii/S0140673617324649

5. Bhatnagar A. Environmental Determinants of Cardiovascular Disease. Circ Res [Internet]. 2017 Jul 7;121(2):162–80. Available from: https://www.ahajournals.org/doi/10.1161/CIRCRESAHA.117.306458

6. Ribeiro AG, Cotta RMM, Ribeiro SMR. A promoção da saúde e a prevenção integrada dos fatores de risco para doenças cardiovasculares. Cien Saude Colet [Internet]. 2012 Jan;17(1):7–17. Available from: http://www.scielo.br/scielo.php?script=sci_arttext&pid=S1413-81232012000100002&lng=pt&tlng=pt

7. Mc Namara K, Alzubaidi H, Jackson JK. Cardiovascular disease as a leading cause of death: how are pharmacists getting involved? Integr Pharm Res Pract [Internet]. 2019 Feb;Volume 8:1–11. Available from: https://www.dovepress.com/cardiovascular-disease-as-a-leading-cause-of-death-how-are-pharmacists-peer-reviewed-article-IPRP

8. Gasparrini A, Guo Y, Hashizume M, Lavigne E, Zanobetti A, Schwartz J, et al. Mortality risk attributable to high and low ambient temperature: a multicountry observational study. Lancet [Internet]. 2015 Jul;386(9991):369–75. Available from: https://linkinghub.elsevier.com/retrieve/pii/S0140673614621140

9. Xu B, Liu H, Su N, Kong G, Bao X, Li J, et al. Association between winter season and risk of death from cardiovascular diseases: a study in more than half a million inpatients in Beijing, China. BMC Cardiovasc Disord [Internet]. 2013 Dec 30;13(1):93. Available from: http://bmccardiovascdisord.biomedcentral.com/articles/10.1186/1471-2261-13-93

10. Rocklöv J, Forsberg B, Ebi K, Bellander T. Susceptibility to mortality related to temperature and heat and cold wave duration in the population of Stockholm County, Sweden. Glob Health Action [Internet]. 2014 Dec 12;7(1):22737. Available from: https://www.tandfonline.com/doi/full/10.3402/gha.v7.22737

11.	Ma X, Yan H, Zhang H, Wang M, Zhang Q, Zhou X. Progress in the seasonal variations of blood lipids: a mini-review. Lipids Health Dis [Internet]. 2020 Dec 25;19(1):108. Available from: https://lipidworld.biomedcentral.com/articles/10.1186/s12944-020-01237-3

12. Marti-Soler H, Gubelmann C, Aeschbacher S, Alves L, Bobak M, Bongard V, et al. Seasonality of cardiovascular risk factors: an analysis including over 230 000 participants in 15 countries. Heart. 2014;100(19):1517–23.

13. Faludi A, Izar M, Saraiva J, Chacra A, Bianco H, Afiune Neto A, et al. ATUALIZAÇÃO DA DIRETRIZ BRASILEIRA DE DISLIPIDEMIAS E PREVENÇÃO DA ATEROSCLEROSE - 2017. Arq Bras Cardiol [Internet]. 2017;109(1):76. Available from: http://www.gnresearch.org/doi/10.5935/abc.20170121

14. Abdullah SM, Defina LF, Leonard D, Barlow CE, Radford NB, Willis BL, et al. Long-Term Association of Low-Density Lipoprotein Cholesterol With Cardiovascular Mortality in Individuals at Low 10-Year Risk of Atherosclerotic Cardiovascular Disease. Circulation [Internet]. 2018 Nov 20;138(21):2315–25. Available from: https://www.ahajournals.org/doi/10.1161/CIRCULATIONAHA.118.034273

15. Baigent C, Blackwell L, Emberson J, Holland LE, Reith C, Bhala N, et al. Efficacy and safety of more intensive lowering of LDL cholesterol: a meta-analysis of data from 170 000 participants in 26 randomised trials. Lancet [Internet]. 2010 Nov;376(9753):1670–81. Available from: http://dx.doi.org/10.1016/S0140-6736(10)61350-5

16.  Zhou X, Lin H, Zhang S, Ren J, Wang Z, Zhang Y, et al. Effects of climatic factors on plasma lipid levels: A 5-year longitudinal study in a large Chinese population. J Clin Lipidol [Internet]. 2016 Sep;10(5):1119–28. Available from: http://dx.doi.org/10.1016/j.jacl.2016.06.009

17.  Schienkiewitz A, Truthmann J, Ernert A, Wiegand S, Schwab KO, Scheidt-Nave C. Age, maturation and serum lipid parameters: findings from the German Health Survey for Children and Adolescents. BMC Public Health [Internet]. 2019 Dec 3;19(1):1627. Available from: https://bmcpublichealth.biomedcentral.com/articles/10.1186/s12889-019-7901-z

18. Elagizi A, Köhler TS, Lavie CJ. Testosterone and Cardiovascular Health. Mayo Clin Proc [Internet]. 2018 Jan;93(1):83–100. Available from: https://linkinghub.elsevier.com/retrieve/pii/S0025619617308248

19. Palmisano BT, Zhu L, Eckel RH, Stafford JM. Sex differences in lipid and lipoprotein metabolism. Mol Metab [Internet]. 2018;15(May):45–55. Available from: https://doi.org/10.1016/j.molmet.2018.05.008

20. Menna-Barreto L, Wey D. Ontogênese do sistema de temporização: a construção e as reformas dos ritmos biológicos ao longo da vida humana. Psicol USP [Internet]. 2007 Jun;18(2):133–53. Available from: http://www.scielo.br/scielo.php?script=sci_arttext&pid=S0103-65642007000200008&lng=pt&tlng=pt

21. Aires M de M. Fisiologia do Envelhecimento Humano. In: Fisiologia. 4th ed. Rio de Janeiro-RJ: Guanabara Koogan; 2012. p. 1270–9.

22. Ding EL, Song Y, Malik VS, Liu S. Sex Differences of Endogenous Sex Hormones and Risk of Type 2 Diabetes. JAMA [Internet]. 2006 Mar 15;295(11):1288. Available from: http://jama.jamanetwork.com/article.aspx?doi=10.1001/jama.295.11.1288

23. Laughlin GA, Barrett-Connor E, Bergstrom J. Low Serum Testosterone and Mortality in Older Men. J Clin Endocrinol Metab [Internet]. 2008 Jan;93(1):68–75. Available from: https://academic.oup.com/jcem/article-lookup/doi/10.1210/jc.2007-1792

24. Goggins WB, Woo J, Ho S, Chan EYY, Chau PH. Weather, season, and daily stroke admissions in Hong Kong. Int J Biometeorol [Internet]. 2012 Sep 14;56(5):865–72. Available from: http://link.springer.com/10.1007/s00484-011-0491-9

25. Gamble JL, Hurley BJ, Schultz PA, Jaglom WS, Krishnan N, Harris M. Climate Change and Older Americans: State of the Science. Environ Health Perspect [Internet]. 2013 Jan;121(1):15–22. Available from: https://ehp.niehs.nih.gov/doi/10.1289/ehp.1205223

26.	McNamara DJ, Kolb R, Parker TS, Batwin H, Samuel P, Brown CD, et al. Heterogeneity of cholesterol homeostasis in man. Response to changes in dietary fat quality and cholesterol quantity. J Clin Invest [Internet]. 1987 Jun 1;79(6):1729–39. Available from: http://www.jci.org/articles/view/113013

27. Lordan R, Tsoupras A, Mitra B, Zabetakis I. Dairy Fats and Cardiovascular Disease: Do We Really Need to Be Concerned? Foods [Internet]. 2018 Mar 1;7(3):29. Available from: http://www.mdpi.com/2304-8158/7/3/29

28. Santosa S, Varady KA, AbuMweis S, Jones PJH. Physiological and therapeutic factors affecting cholesterol metabolism: Does a reciprocal relationship between cholesterol absorption and synthesis really exist? Life Sci. 2007;80(6):505–14.

29. Dong M, Yang X, Lim S, Cao Z, Honek J, Lu H, et al. Cold Exposure Promotes Atherosclerotic Plaque Growth and Instability via UCP1-Dependent Lipolysis. Cell Metab [Internet]. 2013 Jul;18(1):118–29. Available from: https://linkinghub.elsevier.com/retrieve/pii/S1550413113002477

30. Hoeke G, Nahon KJ, Bakker LEH, Norkauer SSC, Dinnes DLM, Kockx M, et al. Short-term cooling increases serum triglycerides and small high-density lipoprotein levels in humans. J Clin Lipidol [Internet]. 2017 Jul;11(4):920-928.e2. Available from: https://linkinghub.elsevier.com/retrieve/pii/S1933287417302556

31. Dados gerados pelo CPTEC/INPE e disponibilizados na Plataforma PROJETA Available from: https://projeta.cptec.inpe.br/.

32. Chou, S.C, Lyra, A. , Mourão, C. , Dereczynski, C. , Pilotto, I. , Gomes, J. , Bustamante, J. , Tavares, P. , Silva, A. , Rodrigues, D. , Campos, D. , Chagas, D. , Sueiro, G. , Siqueira, G. , Nobre, P. and Marengo, J. (2014) Evaluation of the Eta Simulations Nested in Three Global Climate Models. American Journal of Climate Change, 3, 438-454. doi:10.4236/ajcc.2014.35039. http://www.scirp.org/journal/PaperInformation.aspx?PaperID=52887#.VakHg_lViko.

33.	Chou, S.C, Lyra, A. , Mourão, C. , Dereczynski, C. , Pilotto, I. , Gomes, J. , Bustamante, J. , Tavares, P. , Silva, A. , Rodrigues, D. , Campos, D. , Chagas, D. , Sueiro, G. , Siqueira, G. and Marengo, J. (2014) Assessment of Climate Change over South America under RCP 4.5 and 8.5 Downscaling Scenarios. American Journal of Climate Change,3, 512-527. doi: 10.4236/ajcc.2014.35043. http://www.scirp.org/journal/PaperInformation.aspx?PaperID=52877#.VakIh_lVikp

34.	Lyra, A., Tavares, P., Chou, S.C., Sueiro, G., Dereczynski, C.P., Sondermann, M., Silva, A., Marengo, J., Giarolla, A. 2017. Climate change projections over three metropolitan regions in Southeast Brazil using the non-hydrostatic Eta regional climate model at 5-km resolution Theor Appl Climatol. doi:10.1007/s00704-017-2067-z. https://link.springer.com/article/10.1007/s00704-017-2067-z

35.	Terceira Comunicação Nacional do Brasil à Convenção-Quadro das Nações Unidas sobre Mudança do Clima Executive Summary: http://unfccc.int/resource/docs/natc/branc3es.pdf Volume 1: http://unfccc.int/resource/docs/natc/branc3v1.pdf  Volume 2: http://unfccc.int/resource/docs/natc/branc3v2.pdf  Volume 3: http://unfccc.int/resource/docs/natc/branc3v3.pdf

 

