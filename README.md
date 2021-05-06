# PetroCoder Hackathon
Task is to optimise ROP (Rate of Penetration) for Oil and Drilling. Since the cost of daily penetration is about $40,000 to $300,000.
<hr>
Refer <a href="https://www.sciencedirect.com/science/article/pii/S0920410520311244">Dataset for rate of penetration benchmarking</a> under Journal of Petroleum Science and Engineering by Elsevier to know the Problem faced while calculating ROP and why it still hasn't been perfected.
<br>
For Reference, one can also refer to the code and visualization by <a href="https://github.com/AndrzejTunkiel/USROP">Andrzej Tunkiel</a>.
<hr>
Task was to achieve the highest MAE on an open and closed dataset. Data for 7 oil wells were provided. I achieved an accuracy of 99.76% using MSE criteria and 0.0736 MAE using MAE criteria. MAE recieved on on open dataset on a random well was 7.85.
<br>
Final Notebook will be uploaded after ending of competition.
<hr>
<h2>File Structure</h2>
<ol>
<li><b>PetroCoder_Round3_ByPradhuman.ipynb</b> - A standalone file for reproduction of Graphs and Models.<br></li>
<li><b>exploratoryDataAnalysis_1.ipynb</b> - Explains out the Data Preprocessing step with some visualizations.<br></li>
<li><b>graphMinMaxTrans.xlsx</b> - Contains models, their properties and plots for MinMaxScaler. Produced using RandomSearchCV.<br></li>
<li><b>graphPowerTrans.xlsx</b> - Contains models, their properties and plots for PowerTransform Scaler. Produced using RandomSearchCV.<br></li>
<li><b>graphStandardScalar.xlsx</b> - Contains models, their properties and plots for StandardScaler. Produced using RandomSearchCV.<br></li>
<li><b>tech_challenge2021_train.zip</b> - Contains training dataset provided by Hackathon Organisers.<br></li>
<li><b>tech_challenge2021_test.zip</b> - Contains testing dataset provided by Hackathon Organisers.<br></li>
</ol>
