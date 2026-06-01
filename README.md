

<html>

<head>

<meta charset="utf-8">


</head>

<body>



<h1 align="center">A Mapping of Connected Vehicles Applications Requirements on Telecommunication Technologies</h1>

Taxonomy part of Hugues Blache M.A.Sc project with the participation of him supervisors <a href="https://www.polymtl.ca/expertises/en/sanso-brunilde">Brunilde Sanso</a> and <a href="https://www.polymtl.ca/expertises/en/saunier-nicolas">Nicolas Saunier</a>, with the help of <a href="https://www.concordia.ca/ginacody/computer-science-software-eng/faculty.html?fpid=hakim-mellah">Hakim Mellah</a> and the <a href="https://www.trafficm2modelling.com/home">M2M</a> team

<h2 align="center">Article link</h2>

Cite: <i> A Mapping of Connected Vehicles Applications Requirements on Telecommunication Technologies </i>

<h2 align="center">Data</h2>

The dataset is stored locally as CSV files in the <code>data/</code> folder. It was originally compiled in a spreadsheet during the research project and downloaded as a fixed snapshot in June 2026. The scripts read these files directly; no online connection is required.

<ul>
  <li><code>data/application_data.csv</code> — connected vehicle applications and requirements</li>
  <li><code>data/communication_mode_data.csv</code> — communication modes (V2V, V2I, V2P, …)</li>
  <li><code>data/technologies_data.csv</code> — telecommunication technologies and performance attributes</li>
</ul>

Some data is not fully exploited because the original collection contains more fields than the analysis scripts use. Unclear or incomplete entries may therefore be ignored by the programs.

<h2 align="center">Interactive part</h2>

<h3 align="center">My Binder</h3>



The entire repertoire of Binder can be found in this link [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/HuguesBlache/taxonomy/HEAD)


The interactive parts can be found in the NoteBook <i>interactive_part.ipynb</i> .Launch the first cell and play with the different potibilities described below. 

<h3 align="center">Download script</h3>

Requirement `jupyter notebook`

`git clone https://github.com/HuguesBlache/taxonomy`

Launch with Jupyter NoteBook on our <a href="https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/execute.html#running-the-jupyter-notebook">terminal</a> window or with the app:

`jupyter-notebook <FOLDER_HOME>/interactive_part.ipynb`

<h3 align="center">Possibility</h3>

The following figure represents the different possible paths for the figures:
<p align="center">
  <img src="https://github.com/HuguesBlache/taxonomy/blob/master/Image/interactive_cheminement/Diapositive1.PNG" alt="hi" class="inline">
  <img src="https://github.com/HuguesBlache/taxonomy/blob/master/Image/interactive_cheminement/Diapositive2.PNG" alt="hi" class="inline">
  <img src="https://github.com/HuguesBlache/taxonomy/blob/master/Image/interactive_cheminement/Diapositive3.PNG" alt="hi" class="inline">
</p>

The figures presented in the articles are available in the code and are interactive thanks to the Plotly module. Other figures are available in the program such as 2D plots which allow the attributes to be varied. 
</body>
