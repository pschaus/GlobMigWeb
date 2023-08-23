**Innovative Data Sources**
+++++++++++++++++++++++++++++


.. |br| raw:: html

   <br />


|br|

Using machine learning to study and forecast migration
--------------------------------------------------------------

|br|


  .. dropdown:: Golenvaux, N., Alvarez, P. G., Kiossou, H. S., & Schaus, P. (2020). *An LSTM approach to Forecast Migration using Google Trends*. arXiv preprint arXiv:2005.09902.
    
    Being able to model and forecast international migration as precisely as possible is crucial for policymaking. Recently Google Trends data in addition to other economic and demographic 
    data have been shown to improve the forecasting quality of a gravity linear model for the one-year ahead forecasting. In this work, we replace the linear model with a long short-term 
    memory (LSTM) approach and compare it with two existing approaches: the linear gravity model and an artificial neural network (ANN) model. Our LSTM approach combined with Google Trends 
    data outperforms both these models on various metrics in the task of forecasting the one-year ahead incoming international migration to 35 Organization for Economic Co-operation and 
    Development (OECD) countries: for example the root mean square error (RMSE) and the mean average error (MAE) have been divided by 5 and 4 on the test set. This positive result 
    demonstrates that machine learning techniques constitute a serious alternative over traditional approaches for studying migration mechanisms.

    `Link to the article <https://arxiv.org/abs/2005.09902>`_

|br|

  .. dropdown:: Kiossou, H. S., Nijssen, S., Schaus, P., & Houndji, V. R. *Forecasting Migration using Google Trends and Machine Learning*

    Using gravity models, recent work has shown that data from Google Trends can serve as a proxy for migration intentions. However, these studies mainly focused on 
    identifying associations between variables rather than showing how Google Trends data can be used to forecast migration. When it comes to migration modeling, data such as GDP a
    nd population are widely used as control variables. Forecasting using such data is challenging they might not be available at the time of the forecast. Moreover, year fixed effects are 
    commonly used in migration models to account for unobserved factors that may affect migration rates across time. However, these fixed effects are typically calculated using data from the 
    same year as the migration flow data, assuming migration patterns would remain the same.
    Since our study focuses on forecasting future migration, we cannot include fixed effects for the year in our models, which poses a challenge in accurately accounting for time-varying factors.
    Despite these challenges, we employ machine learning approaches, specifically random forests, to forecast and analyze migration patterns in relation to Google Trends data.

    *Working paper*

|br|

  .. dropdown:: Kiossou, H. S., Schenk, Y., Docquier, F., Houndji, V. R., Nijssen, S., & Schaus, P. (2020). *Using an interpretable Machine Learning approach to study the drivers of International Migration*. arXiv preprint arXiv:2006.03560. 
    
    Globally increasing migration pressures call for new modelling approaches in order to design effective policies. It is important to have not only efficient models to predict migration flows but also to understand how specific 
    parameters influence these flows. In this paper, we propose an artificial neural network (ANN) to model international migration. Moreover, we use a technique for interpreting machine learning models, namely 
    Partial Dependence Plots (PDP), to show that one can well study the effects of drivers behind international migration. We train and evaluate the model on a dataset containing annual international bilateral
    migration from 1960 to 2010 from 175 origin countries to 33 mainly OECD destinations, along with the main determinants as identified in the migration literature. The experiments carried out confirm that: 
    1) the ANN model is more efficient w.r.t. a traditional model, and 2) using PDP we are able to gain additional insights on the specific effects of the migration drivers. This approach provides much more 
    information than only using the feature importance information used in previous works.

    `Link to the article <https://arxiv.org/abs/2006.03560>`_

|br|

  .. dropdown:: Derval, G., Docquier, F., & Schaus, P. (2020). *An aggregate learning approach for interpretable semi-supervised population prediction and disaggregation using ancillary data*. **In Machine Learning and Knowledge Discovery in Databases: European Conference**, ECML PKDD 2019, Würzburg, Germany, September 16–20, 2019, Proceedings, Part III (pp. 672-687). Springer International Publishing.  
    
    Census data provide detailed information about population characteristics at a coarse resolution. Nevertheless, fine-grained, high-resolution mappings of population counts are increasingly needed to characterize 
    population dynamics and to assess the consequences of climate shocks, natural disasters, investments in infrastructure, development policies, etc. Disaggregating these census is a complex machine learning, and 
    multiple solutions have been proposed in past research. We propose in this paper to view the problem in the context of the aggregate learning paradigm, where the output value for all training points is not 
    known, but where it is only known for aggregates of the points (i.e. in this context, for regions of pixels where a census is available). We demonstrate with a very simple and interpretable model that this 
    method is on par, and even outperforms on some metrics, the state-of-the-art, despite its simplicity.
    
    `Link to the article <https://link.springer.com/chapter/10.1007/978-3-030-46133-1_40>`_ 

|br|

|br|

Special section on cross-border mobility during COVID-19
--------------------------------------------------------------

**Restrictions on mobility and economic activity mattered more than fears, but were poorly effective.**

  .. dropdown:: Docquier, F. & N. Golenvaux & S. Nijssen & P. Schaus & F. Stips (2022). *Cross-border mobility responses to COVID-19 in Europe: Evidence from Facebook data*. **Globalization and Health**, 18, n. 41.  
 
    Assessing the impact of government responses to Covid-19 is crucial to contain the pandemic and improve preparedness for future crises. We investigate here the impact of non-pharmaceutical interventions (NPIs) 
    and infection threats on the daily evolution of cross-border movements of people during the Covid-19 pandemic. We use a unique database on Facebook users’ mobility, and rely on regression and machine learning 
    models to identify the role of infection threats and containment policies. Permutation techniques allow us to compare the impact and predictive power of these two categories of variables.
 
    `Link to the article <https://doi.org/10.1186/s12992-022-00832-6>`_  

  .. dropdown:: Docquier, F. & N. Golenvaux & P. Schaus (2022). *Are Travel Restrictions the Panacea to Prevent the Spread of a Virus? Lessons from a Multi-Country SIR Model*. 
 
    The SARS-CoV-2 outbreak has given rise to new packages of interventions. Among them, international travel restrictions have been one of the fastest and most visible responses to limit the spread of the virus and its variants. 
    While inducing large economic losses, the epidemiological consequences of such travel restrictions are highly uncertain. They may be poorly effective when a new transmissible virus already circulates across borders. 
    Assessing the effectiveness of travel restrictions is difficult given the paucity of data on daily cross-border mobility and on existing virus circulation. 
    The question was topical and timely when the omicron variant  -- classified as a variant of concern by WHO --  was detected and perceived as more contagious. 
    In this study, we develop a multi-country compartmental model of the SIR type. We use it to simulate the spread of a new virus across European countries, and to assess the effectiveness of unilateral and 
    multilateral travel restrictions.
 
    *Link to Manuscript*

|br|

|br|

:doc:`See the Computer Science Team <computerteam>`
