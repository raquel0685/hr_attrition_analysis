# ANÁLISE DO DESGATE DE FUNCIONÁRIOS PARA O RH 

## INTRODUÇÃO

Analisar dados para determinar os motivos por trás da rotatividade de funcionários de uma empresa é chamada análise de desgaste de funcionários. Com este conjunto de dados, visamos identificar os fatores que levam às saídas dos funcionários, apontar os departamentos e cargos com o maior número de abandono e compará-los aos funcionários que ficaram para uma avaliação mais abrangente. 
  
## ANÁLISE

#### Limpeza dos dados 
  
Removemos as seguintes colunas por faltar contexto para a interpretação apropriada: *Education*, *EmployeeCount*, *EnvironmentSatisfaction*, *JobInvolvement*, *JobSatisfaction*, *PerformanceRating*, *RelationshipSatisfaction*, *StockOptionLevel*, *WorkLifeBalance*. 
A coluna *Over18*  também foi removida por ter somente um valor para todos os registros que se referiam à idade dos empregados.
Não haviam entradas nulas ou duplicadas, e após a limpeza ficamos com 26 colunas e 1470 registros.
A seguir veremos as visualizações desta análise.

## RECOMENDAÇÕES

- É importante revisar os atuais salários para que homens e mulheres no mesmo nível de cargo tenham salários equiparáveis, aplicando as alterações cabíveis às novas contratações;
- Um possível motivo de cargos com baixo tempo para promoção terem mais demissões poderia ser o salário ofertado, sendo benéfico verificar os valores do mercado e ajustá-los para que  permaneçam competitivos;
- Como os dados relativos à satisfação dos funcionários com a empresa foram removidos por falta de contextualização, seria apropriado realizar uma nova averiguação para uma análise futura;
- Uma vez que a maior parte dos ex-funcionários não tinham alta rotatividade entre empregos, estavam na empresa há algum tempo, ocupavam cargos com alta taxa de horas extras e estavam a pouco tempo trabalhando sob um novo gestor, sugerimos a avaliação das condutas deste quanto a divisão da carga laboral para cargos de nível baixo para possíveis reajustes.

********************************************
# HR ATTRITION ANALYSIS

## INTRODUCTION

Analyzing data to determine the reasons behind employee turnover in an organization is known as employee attrition analytics. With this dataset, we aim to identify the factors that lead to employee departures and pinpoint the departments and roles with the highest numbers of departures, so we can compare them to those who stayed for a more comprehensive evaluation. 
  
## ANALYSIS 

#### Cleaning the data 
  
We removed the following columns because they lacked context for the appropriate interpretation: *Education*, *EmployeeCount*, *EnvironmentSatisfaction*, *JobInvolvement*, *JobSatisfaction*, *PerformanceRating*, *RelationshipSatisfaction*, *StockOptionLevel*, *WorkLifeBalance*. 
The column *Over18* was also removed because it only had one value for all registries and it wasn’t relevant since it pertained to employees' age.
There were no null or duplicated values, and after the cleaning, we had 26 columns and 1470 registries. 
Next, we'll have the visualizations for this analysis.

## RECOMMENDATIONS

- It is important to review the wages for equal pay between men and women in the same job role level and apply any necessary changes for new hires; 
- To address high attrition rates in certain positions with low promotion time, it may be beneficial to verify average pay rates in the market and adjust accordingly to remain competitive;
- Since some of the data that impact employee satisfaction were removed due to lack of context, it would be appropriate to provide answers to these inquiries for a new analysis;
- Based on the fact that most former employees have not worked for many other companies and had been with this one for some time, coupled with high overtime rates and a short period of time under the current manager, we suggest that the current workload for employees in low-level job positions should be evaluated and maybe readjusted.
