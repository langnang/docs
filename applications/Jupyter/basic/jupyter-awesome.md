<!-- @format -->

# Awesome Jupyter

## Contents

- [Notebook Environments](#notebook-environments) _16 projects_
- [Interactive Widgets & Visualization](#interactive-widgets--visualization) _56 projects_
- [Jupyter Extensions](#jupyter-extensions) _25 projects_
- [Jupyter Magic](#jupyter-magic) _12 projects_
- [Jupyter Kernels](#jupyter-kernels) _41 projects_
- [Notebook Sharing & Conversion](#notebook-sharing--conversion) _24 projects_
- [Notebook Tools](#notebook-tools) _26 projects_
- [JupyterLab Renderer](#jupyterlab-renderer) _8 projects_
- [JupyterLab Themes](#jupyterlab-themes) _9 projects_
- [JupyterLab Extensions](#jupyterlab-extensions) _52 projects_
- [JupyterHub Authenticators](#jupyterhub-authenticators) _15 projects_
- [JupyterHub Spawners](#jupyterhub-spawners) _8 projects_
- [Jupyter Components](#jupyter-components) _3 projects_
- [Others](#others) _4 projects_

## Explanation

- 🥇🥈🥉&nbsp; Combined project-quality score
- ⭐️&nbsp; Star count from GitHub
- 🐣&nbsp; New project _(less than 6 months old)_
- 💤&nbsp; Inactive project _(6 months no activity)_
- 💀&nbsp; Dead project _(12 months no activity)_
- 📈📉&nbsp; Project is trending up or down
- ➕&nbsp; Project was recently added
- ❗️&nbsp; Warning _(e.g. missing/risky license)_
- 👨‍💻&nbsp; Contributors count from GitHub
- 🔀&nbsp; Fork count from GitHub
- 📋&nbsp; Issue count from GitHub
- ⏱️&nbsp; Last update timestamp on package manager
- 📥&nbsp; Download count from package manager
- 📦&nbsp; Number of dependent projects

<br>
## Notebook Environments

_Development environments with support for Jupyter Notebooks._

<details><summary><b><a href="https://github.com/jupyter/notebook">Jupyter</a></b> (🥇43 ·  ⭐ 11K) - Jupyter Interactive Notebook. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/notebook) (👨‍💻 620 · 🔀 4K · 📥 11K · 📦 19 · 📋 4.6K - 44% open · ⏱️ 01.03.2023):

  ```sh
  git clone https://github.com/jupyter/notebook
  ```

- [PyPi](https://pypi.org/project/notebook) (📥 12M / month · 📦 8.9K · ⏱️ 19.01.2023):
  ```sh
  pip install notebook
  ```
- [Conda](https://anaconda.org/conda-forge/jupyter) (📥 3M · ⏱️ 05.12.2022):
  ```sh
  conda install -c conda-forge jupyter
  ```
- [Docker Hub](https://hub.docker.com/r/jupyter/datascience-notebook) (📥 29M · ⭐ 980 · ⏱️ 28.02.2023):
`cmd
	docker pull jupyter/datascience-notebook
	`
</details>
<details><summary><b><a href="https://github.com/jupyterhub/jupyterhub">JupyterHub</a></b> (🥇39 ·  ⭐ 7.4K) - Multi-user server for Jupyter notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/jupyterhub) (👨‍💻 330 · 🔀 1.9K · 📦 2.2K · 📋 2.3K - 8% open · ⏱️ 01.03.2023):

  ```
  git clone https://github.com/jupyterhub/jupyterhub
  ```

- [PyPi](https://pypi.org/project/jupyterhub) (📥 200K / month · 📦 380 · ⏱️ 27.01.2023):
  ```
  pip install jupyterhub
  ```
- [Conda](https://anaconda.org/conda-forge/jupyterhub) (📥 860K · ⏱️ 27.01.2023):
  ```
  conda install -c conda-forge jupyterhub
  ```
- [Docker Hub](https://hub.docker.com/r/jupyterhub/jupyterhub) (📥 3.2M · ⭐ 320 · ⏱️ 01.03.2023):
`
	docker pull jupyterhub/jupyterhub
	`
</details>
<details><summary><b><a href="https://github.com/nteract/nteract">nteract</a></b> (🥈33 ·  ⭐ 6K) - The interactive computing suite for you!. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/nteract) (👨‍💻 180 · 🔀 570 · 📥 1.4M · 📦 2 · 📋 1.7K - 10% open · ⏱️ 15.02.2023):

  ```
  git clone https://github.com/nteract/nteract
  ```

- [PyPi](https://pypi.org/project/nteract_on_jupyter) (📥 4.1K / month · 📦 5 · ⏱️ 16.07.2019):
  ```
  pip install nteract_on_jupyter
  ```
- [npm](https://www.npmjs.com/package/@nteract/messaging) (📥 66K / month · 📦 35 · ⏱️ 22.10.2021):
`
	npm install @nteract/messaging
	`
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab">JupyterLab</a></b> (🥈30 ·  ⭐ 13K) - JupyterLab computational environment. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab) (👨‍💻 430 · 🔀 2.5K):

  ```
  git clone https://github.com/jupyterlab/jupyterlab
  ```

- [PyPi](https://pypi.org/project/jupyterlab) (📥 2.1M / month · 📦 2.1K · ⏱️ 09.06.2022):
  ```
  pip install jupyterlab
  ```
- [Conda](https://anaconda.org/conda-forge/jupyterlab) (📥 7.4M · ⏱️ 15.02.2023):
  ```
  conda install -c conda-forge jupyterlab
  ```
- [npm](https://www.npmjs.com/package/@jupyterlab/ui-components) (📥 200K / month · 📦 330 · ⏱️ 14.02.2023):
`
	npm install @jupyterlab/ui-components
	`
</details>
<details><summary><b><a href="https://github.com/jupyter/docker-stacks">Docker Stacks</a></b> (🥈30 ·  ⭐ 7.5K) - Ready-to-run Docker images containing Jupyter applications. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/docker-stacks) (👨‍💻 230 · 🔀 2.8K · 📋 810 - 3% open · ⏱️ 01.03.2023):

  ```
  git clone https://github.com/jupyter/docker-stacks
  ```

- [Docker Hub](https://hub.docker.com/r/jupyter/scipy-notebook) (📥 89M · ⭐ 380 · ⏱️ 28.02.2023):
`
	docker pull jupyter/scipy-notebook
	`
</details>
<details><summary><b><a href="https://github.com/microsoft/vscode-jupyter">VSCode Jupyter</a></b> (🥈29 ·  ⭐ 930) - VS Code Jupyter extension. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/vscode-jupyter) (👨‍💻 260 · 🔀 200 · 📋 8.6K - 4% open · ⏱️ 02.03.2023):

  ```
  git clone https://github.com/microsoft/vscode-jupyter
  ```

- [Conda](https://anaconda.org/conda-forge/vscode-jupyter) (📥 48K · ⏱️ 06.10.2022):
`
	conda install -c conda-forge vscode-jupyter
	`
</details>
<details><summary><b><a href="https://github.com/vatlab/sos">sos</a></b> (🥈28 ·  ⭐ 240) - SoS workflow system for daily data analysis. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/vatlab/sos) (👨‍💻 36 · 🔀 33 · 📦 3.7K · 📋 1.4K - 4% open · ⏱️ 18.02.2023):

  ```
  git clone https://github.com/vatlab/SOS
  ```

- [PyPi](https://pypi.org/project/sos-notebook) (📥 1.5K / month · 📦 36 · ⏱️ 09.08.2022):
  ```
  pip install sos-notebook
  ```
- [Conda](https://anaconda.org/conda-forge/sos) (📥 140K · ⏱️ 19.02.2023):
`
	conda install -c conda-forge sos
	`
</details>
<details><summary><b><a href="https://github.com/Kaggle/docker-python">docker-python</a></b> (🥉26 ·  ⭐ 2.3K) - Kaggle Python docker image. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Kaggle/docker-python) (👨‍💻 150 · 🔀 870 · 📋 310 - 8% open · ⏱️ 01.03.2023):

  ```
  git clone https://github.com/kaggle/docker-python
  ```

- [Docker Hub](https://hub.docker.com/r/kaggle/python) (📥 190K · ⭐ 170 · ⏱️ 24.02.2023):
`
	docker pull kaggle/python
	`
</details>
<details><summary><b><a href="https://github.com/googledatalab/datalab">DataLab</a></b> (🥉26 ·  ⭐ 980) - Interactive tools and developer experiences for Big Data on Google.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/googledatalab/datalab) (👨‍💻 53 · 🔀 260 · 📋 900 - 25% open · ⏱️ 02.09.2022):

  ```
  git clone https://github.com/googledatalab/datalab
  ```

- [PyPi](https://pypi.org/project/datalab) (📥 94K / month · 📦 12 · ⏱️ 02.09.2022):
`
	pip install datalab
	`
</details>
<details><summary><b><a href="https://github.com/nteract/hydrogen">Hydrogen</a></b> (🥉23 ·  ⭐ 3.8K) - Run code interactively, inspect data, and plot. All the power of Jupyter.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nteract/hydrogen) (👨‍💻 90 · 🔀 350 · 📋 1.3K - 13% open · ⏱️ 10.01.2023):

      ```
      git clone https://github.com/nteract/hydrogen
      ```

  </details>
  <details><summary><b><a href="https://github.com/jupyterlab/retrolab">retrolab</a></b> (🥉20 ·  ⭐ 260) - JupyterLab distribution with a retro look and feel. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/retrolab) (👨‍💻 17 · 🔀 46 · 📥 900 · 📦 110 · 📋 120 - 3% open · ⏱️ 16.02.2023):

  ```
  git clone https://github.com/jupyterlab/retrolab
  ```

- [PyPi](https://pypi.org/project/retrolab) (📥 3.6K / month · 📦 3 · ⏱️ 04.05.2022):
  ```
  pip install retrolab
  ```
- [Conda](https://anaconda.org/conda-forge/retrolab) (📥 34K · ⏱️ 04.05.2022):
  ```
  conda install -c conda-forge retrolab
  ```
- [npm](https://www.npmjs.com/package/@jupyterlab-classic/application) (📥 39 / month · 📦 4 · ⏱️ 19.04.2021):
`
	npm install @jupyterlab-classic/application
	`
</details>
<details><summary><b><a href="https://github.com/iot-salzburg/gpu-jupyter">gpu-jupyter</a></b> (🥉15 ·  ⭐ 470) - Leverage the flexibility of Jupyterlab through the power of your.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/iot-salzburg/gpu-jupyter) (👨‍💻 11 · 🔀 170 · 📋 66 - 10% open · ⏱️ 17.11.2022):

      ```
      git clone https://github.com/iot-salzburg/gpu-jupyter
      ```

  </details>
  <details><summary><b><a href="https://github.com/jtpio/jupyterlite">jupyterlite</a></b> (🥉14 ·  ⭐ 77) - Wasm powered Jupyter running in the browser. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jtpio/jupyterlite) (👨‍💻 44 · 🔀 6 · ⏱️ 15.02.2023):

      ```
      git clone https://github.com/jtpio/jupyterlite
      ```

  </details>
  <details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/ml-tooling/ml-workspace">ML Workspace</a></b> (🥉21 · ⭐ 3K · 💀) - All-in-one web-based IDE specialized for machine learning.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/jupyter-server/jupyverse">jupyverse</a></b> (🥉16 · ⭐ 120) - A Jupyter server based on FastAPI. <code><a href="https://tldrlegal.com/search?q=BSD-1-Clause">❗️BSD-1-Clause</a></code>
- <b><a href="https://github.com/ml-tooling/ml-hub">ML Hub</a></b> (🥉15 · ⭐ 270 · 💀) - Multi-user development platform for machine learning teams. Simple.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Interactive Widgets & Visualization

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Extensions that provide interactive UI-widgets and visualization tools._

🔗&nbsp;<b><a href="https://github.com/ml-tooling/best-of-ml-python#data-visualization">best-of-ml-python - Data Visualization</a></b> - Python-based data visualization libraries.

<details><summary><b><a href="https://github.com/bokeh/bokeh">bokeh</a></b> (🥇43 ·  ⭐ 17K) - Interactive Data Visualization in the browser, from Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/bokeh/bokeh) (👨‍💻 640 · 🔀 4K · 📦 200 · 📋 7.2K - 9% open · ⏱️ 01.03.2023):

  ```
  git clone https://github.com/bokeh/bokeh
  ```

- [PyPi](https://pypi.org/project/bokeh) (📥 3.5M / month · 📦 3.7K · ⏱️ 20.12.2022):
  ```
  pip install bokeh
  ```
- [Conda](https://anaconda.org/conda-forge/bokeh) (📥 10M · ⏱️ 12.12.2022):
  ```
  conda install -c conda-forge bokeh
  ```
- [npm](https://www.npmjs.com/package/@bokeh/bokehjs) (📥 15K / month · 📦 7 · ⏱️ 27.02.2023):
`
	npm install @bokeh/bokehjs
	`
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/ipywidgets">ipywidgets</a></b> (🥇38 ·  ⭐ 2.7K) - Interactive Widgets for the Jupyter Notebook. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-widgets/ipywidgets) (👨‍💻 200 · 🔀 880 · 📦 6.2K · 📋 1.9K - 34% open · ⏱️ 03.02.2023):

  ```
  git clone https://github.com/jupyter-widgets/ipywidgets
  ```

- [PyPi](https://pypi.org/project/ipywidgets) (📥 8.7M / month · 📦 9K · ⏱️ 22.12.2022):
  ```
  pip install ipywidgets
  ```
- [Conda](https://anaconda.org/conda-forge/ipywidgets) (📥 8.1M · ⏱️ 10.02.2023):
  ```
  conda install -c conda-forge ipywidgets
  ```
- [npm](https://www.npmjs.com/package/@jupyter-widgets/jupyterlab-manager) (📥 70K / month · 📦 90 · ⏱️ 09.02.2023):
`
	npm install @jupyter-widgets/jupyterlab-manager
	`
</details>
<details><summary><b><a href="https://github.com/ydataai/ydata-profiling">pandas-profiling</a></b> (🥇37 ·  ⭐ 10K) - Create HTML profiling reports from pandas DataFrame objects. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ydataai/ydata-profiling) ![](https://shields.io/github/stars/ydataai/ydata-profiling)(👨‍💻 110 · 🔀 1.4K · 📦 84 · 📋 640 - 20% open · ⏱️ 30.01.2023):

```
git clone https://github.com/pandas-profiling/pandas-profiling
```

- [PyPi](https://pypi.org/project/pandas-profiling) (📥 1.1M / month · 📦 180 · ⏱️ 31.01.2023):

```
pip install pandas-profiling
```

- [Conda](https://anaconda.org/conda-forge/pandas-profiling) (📥 340K · ⏱️ 25.01.2023):
`
	conda install -c conda-forge pandas-profiling
	`
</details>
<details><summary><b><a href="https://github.com/holoviz/panel">panel</a></b> (🥇37 ·  ⭐ 2.6K) - A high-level app and dashboarding solution for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/holoviz/panel) (👨‍💻 120 · 🔀 320 · 📦 5.9K · 📋 2.3K - 30% open · ⏱️ 02.03.2023):

  ```
  git clone https://github.com/holoviz/panel
  ```

- [PyPi](https://pypi.org/project/panel) (📥 430K / month · 📦 140 · ⏱️ 31.01.2023):
  ```
  pip install panel
  ```
- [Conda](https://anaconda.org/conda-forge/panel) (📥 870K · ⏱️ 31.01.2023):
  ```
  conda install -c conda-forge panel
  ```
- [npm](https://www.npmjs.com/package/@holoviz/panel) (📥 99K / month · 📦 2 · ⏱️ 28.02.2023):
`
	npm install @holoviz/panel
	`
</details>
<details><summary><b><a href="https://github.com/evidentlyai/evidently">evidently</a></b> (🥇33 ·  ⭐ 3.2K) - Evaluate and monitor ML models from validation to production... <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/evidentlyai/evidently) (👨‍💻 35 · 🔀 340 · 📦 1.4K · 📋 180 - 27% open · ⏱️ 22.02.2023):

  ```
  git clone https://github.com/evidentlyai/evidently
  ```

- [PyPi](https://pypi.org/project/evidently) (📥 180K / month · 📦 5 · ⏱️ 07.07.2022):
  ```
  pip install evidently
  ```
- [Conda](https://anaconda.org/conda-forge/evidently) (📥 3K · ⏱️ 18.02.2023):
`
	conda install -c conda-forge evidently
	`
</details>
<details><summary><b><a href="https://github.com/matplotlib/ipympl">jupyter-matplotlib</a></b> (🥇33 ·  ⭐ 1.4K) - Matplotlib Jupyter Integration. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/matplotlib/ipympl) (👨‍💻 31 · 🔀 210 · 📦 6.6K · 📋 290 - 47% open · ⏱️ 27.02.2023):

  ```
  git clone https://github.com/matplotlib/ipympl
  ```

- [PyPi](https://pypi.org/project/ipympl) (📥 200K / month · 📦 120 · ⏱️ 22.08.2022):
  ```
  pip install ipympl
  ```
- [Conda](https://anaconda.org/conda-forge/ipympl) (📥 1.3M · ⏱️ 16.02.2023):
  ```
  conda install -c conda-forge ipympl
  ```
- [npm](https://www.npmjs.com/package/jupyter-matplotlib) (📥 32K / month · 📦 2 · ⏱️ 15.02.2023):
`
	npm install jupyter-matplotlib
	`
</details>
<details><summary><b><a href="https://github.com/nteract/papermill">papermill</a></b> (🥈32 ·  ⭐ 5.1K) - Parameterize, execute, and analyze notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/papermill) (👨‍💻 110 · 🔀 390 · 📦 4.6K · 📋 360 - 33% open · ⏱️ 18.10.2022):

  ```
  git clone https://github.com/nteract/papermill
  ```

- [PyPi](https://pypi.org/project/papermill) (📥 1M / month · 📦 200 · ⏱️ 15.08.2022):
  ```
  pip install papermill
  ```
- [Conda](https://anaconda.org/conda-forge/papermill) (📥 390K · ⏱️ 23.01.2022):
`
	conda install -c conda-forge papermill
	`
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/ipyleaflet">ipyleaflet</a></b> (🥈32 ·  ⭐ 1.3K) - A Jupyter - Leaflet.js bridge. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jupyter-widgets/ipyleaflet) (👨‍💻 82 · 🔀 350 · 📦 3.8K · 📋 560 - 41% open · ⏱️ 10.02.2023):

  ```
  git clone https://github.com/jupyter-widgets/ipyleaflet
  ```

- [PyPi](https://pypi.org/project/ipyleaflet) (📥 170K / month · 📦 130 · ⏱️ 19.10.2022):
  ```
  pip install ipyleaflet
  ```
- [Conda](https://anaconda.org/conda-forge/ipyleaflet) (📥 970K · ⏱️ 19.10.2022):
  ```
  conda install -c conda-forge ipyleaflet
  ```
- [npm](https://www.npmjs.com/package/jupyter-leaflet) (📥 58K / month · 📦 5 · ⏱️ 19.10.2022):
`
	npm install jupyter-leaflet
	`
</details>
<details><summary><b><a href="https://github.com/PAIR-code/facets">facets-overview</a></b> (🥈31 ·  ⭐ 7.1K) - Visualizations for machine learning datasets. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PAIR-code/facets) (👨‍💻 30 · 🔀 910 · 📦 170 · 📋 160 - 51% open · ⏱️ 18.02.2023):

  ```
  git clone https://github.com/pair-code/facets
  ```

- [PyPi](https://pypi.org/project/facets-overview) (📥 580K / month · 📦 8 · ⏱️ 30.01.2023):
`
	pip install facets-overview
	`
</details>
<details><summary><b><a href="https://github.com/bqplot/bqplot">bqplot</a></b> (🥈31 ·  ⭐ 3.4K · 📉) - Plotting library for IPython/Jupyter notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/bqplot/bqplot) (👨‍💻 60 · 🔀 470 · 📦 38 · 📋 610 - 40% open · ⏱️ 15.02.2023):

  ```
  git clone https://github.com/bqplot/bqplot
  ```

- [PyPi](https://pypi.org/project/bqplot) (📥 150K / month · 📦 100 · ⏱️ 02.09.2022):
  ```
  pip install bqplot
  ```
- [Conda](https://anaconda.org/conda-forge/bqplot) (📥 1.1M · ⏱️ 02.09.2022):
  ```
  conda install -c conda-forge bqplot
  ```
- [npm](https://www.npmjs.com/package/bqplot) (📥 4.1K / month · 📦 14 · ⏱️ 02.09.2022):
`
	npm install bqplot
	`
</details>
<details><summary><b><a href="https://github.com/microsoft/responsible-ai-toolbox">responsible-ai-widgets</a></b> (🥈30 ·  ⭐ 700) - Responsible AI Toolbox is a suite of tools providing.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/responsible-ai-toolbox) (👨‍💻 32 · 🔀 180 · 📦 47 · 📋 280 - 21% open · ⏱️ 01.03.2023):

  ```
  git clone https://github.com/microsoft/responsible-ai-toolbox
  ```

- [PyPi](https://pypi.org/project/raiwidgets) (📥 8.8K / month · 📦 3 · ⏱️ 18.01.2023):
`
	pip install raiwidgets
	`
</details>
<details><summary><b><a href="https://github.com/widgetti/ipyvolume">ipyvolume</a></b> (🥈29 ·  ⭐ 1.8K) - 3d plotting for Python in the Jupyter notebook based on IPython.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/widgetti/ipyvolume) (👨‍💻 45 · 🔀 240 · 📦 15 · 📋 310 - 57% open · ⏱️ 25.02.2023):

  ```
  git clone https://github.com/maartenbreddels/ipyvolume
  ```

- [PyPi](https://pypi.org/project/ipyvolume) (📥 70K / month · 📦 51 · ⏱️ 27.01.2023):
  ```
  pip install ipyvolume
  ```
- [Conda](https://anaconda.org/conda-forge/ipyvolume) (📥 410K · ⏱️ 25.02.2023):
  ```
  conda install -c conda-forge ipyvolume
  ```
- [npm](https://www.npmjs.com/package/ipyvolume) (📥 2.1K / month · 📦 5 · ⏱️ 24.02.2023):
`
	npm install ipyvolume
	`
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/pythreejs">pythreejs</a></b> (🥈29 ·  ⭐ 860) - A Jupyter - Three.js bridge. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-widgets/pythreejs) (👨‍💻 30 · 🔀 180 · 📦 24 · 📋 230 - 26% open · ⏱️ 20.02.2023):

  ```
  git clone https://github.com/jupyter-widgets/pythreejs
  ```

- [PyPi](https://pypi.org/project/pythreejs) (📥 81K / month · 📦 52 · ⏱️ 25.08.2022):
  ```
  pip install pythreejs
  ```
- [Conda](https://anaconda.org/conda-forge/pythreejs) (📥 460K · ⏱️ 06.09.2022):
  ```
  conda install -c conda-forge pythreejs
  ```
- [npm](https://www.npmjs.com/package/jupyter-threejs) (📥 5.4K / month · 📦 10 · ⏱️ 20.02.2023):
`
	npm install jupyter-threejs
	`
</details>
<details><summary><b><a href="https://github.com/InsightSoftwareConsortium/itkwidgets">itkwidgets</a></b> (🥈28 ·  ⭐ 500) - Interactive Jupyter widgets to visualize images, point sets, and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/InsightSoftwareConsortium/itkwidgets) (👨‍💻 26 · 🔀 71 · 📥 71 · 📦 220 · 📋 240 - 43% open · ⏱️ 27.02.2023):

  ```
  git clone https://github.com/InsightSoftwareConsortium/itkwidgets
  ```

- [PyPi](https://pypi.org/project/itkwidgets) (📥 6.7K / month · 📦 14 · ⏱️ 26.01.2023):
  ```
  pip install itkwidgets
  ```
- [Conda](https://anaconda.org/conda-forge/itkwidgets) (📥 310K · ⏱️ 10.08.2020):
  ```
  conda install -c conda-forge itkwidgets
  ```
- [npm](https://www.npmjs.com/package/itkwidgets) (📥 1.1K / month · 📦 1 · ⏱️ 28.12.2022):
`
	npm install itkwidgets
	`
</details>
<details><summary><b><a href="https://github.com/plotly/jupyter-dash">jupyter-dash</a></b> (🥈27 ·  ⭐ 880) - Develop Dash apps in the Jupyter Notebook and JupyterLab. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/plotly/jupyter-dash) (👨‍💻 10 · 🔀 240 · 📥 80 · 📦 2.5K · 📋 74 - 68% open · ⏱️ 21.10.2022):

  ```
  git clone https://github.com/plotly/jupyter-dash
  ```

- [PyPi](https://pypi.org/project/jupyter-dash) (📥 150K / month · 📦 39 · ⏱️ 01.04.2022):
  ```
  pip install jupyter-dash
  ```
- [Conda](https://anaconda.org/conda-forge/jupyter-dash) (📥 300K · ⏱️ 02.04.2022):
  ```
  conda install -c conda-forge jupyter-dash
  ```
- [npm](https://www.npmjs.com/package/jupyterlab-dash) (📥 11K / month · ⏱️ 22.01.2021):
`
	npm install jupyterlab-dash
	`
</details>
<details><summary><b><a href="https://github.com/finos/ipyregulartable">ipyregulartable</a></b> (🥈26 ·  ⭐ 2.7K) - High performance, editable, stylable datagrids in jupyter.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/finos/ipyregulartable) (👨‍💻 5 · 🔀 880 · 📦 11 · 📋 26 - 38% open · ⏱️ 25.02.2023):

  ```
  git clone https://github.com/jpmorganchase/ipyregulartable
  ```

- [PyPi](https://pypi.org/project/ipyregulartable) (📥 110 / month · 📦 2 · ⏱️ 24.09.2022):
  ```
  pip install ipyregulartable
  ```
- [Conda](https://anaconda.org/conda-forge/ipyregulartable) (📥 4K · ⏱️ 24.09.2022):
  ```
  conda install -c conda-forge ipyregulartable
  ```
- [npm](https://www.npmjs.com/package/@jupyter-widgets/jupyterlab-manager) (📥 70K / month · 📦 90 · ⏱️ 09.02.2023):
`
	npm install @jupyter-widgets/jupyterlab-manager
	`
</details>
<details><summary><b><a href="https://github.com/timkpaine/ipydagred3">ipydagred3</a></b> (🥈26 ·  ⭐ 2.7K) - ipywidgets library for drawing directed acyclic graphs in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/ipydagred3) (👨‍💻 3 · 🔀 880 · 📦 2 · 📋 21 - 19% open · ⏱️ 23.02.2023):

  ```
  git clone https://github.com/timkpaine/ipydagred3
  ```

- [PyPi](https://pypi.org/project/ipydagred3) (📥 480 / month · 📦 2 · ⏱️ 23.09.2022):
  ```
  pip install ipydagred3
  ```
- [Conda](https://anaconda.org/conda-forge/ipydagred3) (📥 17K · ⏱️ 24.09.2022):
  ```
  conda install -c conda-forge ipydagred3
  ```
- [npm](https://www.npmjs.com/package/@jupyter-widgets/jupyterlab-manager) (📥 70K / month · 📦 90 · ⏱️ 09.02.2023):
`
	npm install @jupyter-widgets/jupyterlab-manager
	`
</details>
<details><summary><b><a href="https://github.com/lux-org/lux">lux</a></b> (🥈25 ·  ⭐ 4.5K · 💤) - Automatically visualize your pandas dataframe via a single print!. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/lux-org/lux) (👨‍💻 20 · 🔀 340 · 📦 130 · 📋 230 - 31% open · ⏱️ 21.05.2022):

  ```
  git clone https://github.com/lux-org/lux
  ```

- [PyPi](https://pypi.org/project/lux-api) (📥 46K / month · ⏱️ 19.02.2022):
  ```
  pip install lux-api
  ```
- [Conda](https://anaconda.org/conda-forge/lux-api) (📥 16K · ⏱️ 22.02.2022):
  ```
  conda install -c conda-forge lux-api
  ```
- [npm](https://www.npmjs.com/package/luxwidget) (📥 500 / month · ⏱️ 17.02.2022):
`
	npm install luxwidget
	`
</details>
<details><summary><b><a href="https://github.com/nglviewer/nglview">nglview</a></b> (🥈25 ·  ⭐ 640) - Jupyter widget to interactively view molecular structures and trajectories. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nglviewer/nglview) (👨‍💻 34 · 🔀 120 · 📥 260 · 📦 5 · 📋 450 - 8% open · ⏱️ 11.12.2022):

  ```
  git clone https://github.com/nglviewer/nglview
  ```

- [PyPi](https://pypi.org/project/nglview) (📥 7.8K / month · 📦 51 · ⏱️ 11.06.2021):
  ```
  pip install nglview
  ```
- [Conda](https://anaconda.org/conda-forge/nglview) (📥 560K · ⏱️ 11.06.2021):
  ```
  conda install -c conda-forge nglview
  ```
- [npm](https://www.npmjs.com/package/nglview-js-widgets) (📥 6.6K / month · 📦 4 · ⏱️ 16.04.2021):
`
	npm install nglview-js-widgets
	`
</details>
<details><summary><b><a href="https://github.com/mwouts/itables">itables</a></b> (🥈25 ·  ⭐ 390) - Pandas DataFrames as Interactive DataTables. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mwouts/itables) (👨‍💻 5 · 🔀 34 · 📦 210 · 📋 81 - 17% open · ⏱️ 31.01.2023):

  ```
  git clone https://github.com/mwouts/itables
  ```

- [PyPi](https://pypi.org/project/itables) (📥 28K / month · 📦 8 · ⏱️ 31.01.2023):
  ```
  pip install itables
  ```
- [Conda](https://anaconda.org/conda-forge/itables) (📥 11K · ⏱️ 01.02.2023):
`
	conda install -c conda-forge itables
	`
</details>
<details><summary><b><a href="https://github.com/vega/ipyvega">vega</a></b> (🥉24 ·  ⭐ 340) - IPython/Jupyter notebook module for Vega and Vega-Lite. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/vega/ipyvega) (👨‍💻 13 · 🔀 59 · 📦 2 · 📋 100 - 11% open · ⏱️ 28.02.2023):

  ```
  git clone https://github.com/vega/ipyvega
  ```

- [PyPi](https://pypi.org/project/vega) (📥 10K / month · 📦 84 · ⏱️ 10.02.2022):
  ```
  pip install vega
  ```
- [Conda](https://anaconda.org/conda-forge/vega) (📥 530K · ⏱️ 05.12.2022):
`
	conda install -c conda-forge vega
	`
</details>
<details><summary><b><a href="https://github.com/cytoscape/ipycytoscape">ipycytoscape</a></b> (🥉24 ·  ⭐ 220) - A Cytoscape Jupyter widget. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/cytoscape/ipycytoscape) (👨‍💻 32 · 🔀 57 · 📥 3 · 📦 120 · 📋 160 - 38% open · ⏱️ 12.09.2022):

  ```
  git clone https://github.com/cytoscape/ipycytoscape
  ```

- [PyPi](https://pypi.org/project/ipycytoscape) (📥 6.6K / month · 📦 11 · ⏱️ 04.04.2022):
  ```
  pip install ipycytoscape
  ```
- [Conda](https://anaconda.org/conda-forge/ipycytoscape) (📥 250K · ⏱️ 12.09.2022):
  ```
  conda install -c conda-forge ipycytoscape
  ```
- [npm](https://www.npmjs.com/package/jupyter-cytoscape) (📥 1.3K / month · ⏱️ 04.04.2022):
`
	npm install jupyter-cytoscape
	`
</details>
<details><summary><b><a href="https://github.com/vizzuhq/ipyvizzu">ipyvizzu</a></b> (🥉23 ·  ⭐ 760 · 📈) - Build animated charts in Jupyter Notebook and similar.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/vizzuhq/ipyvizzu) (👨‍💻 10 · 🔀 60 · 📥 39 · 📦 36 · 📋 80 - 37% open · ⏱️ 01.03.2023):

  ```
  git clone https://github.com/vizzuhq/ipyvizzu
  ```

- [PyPi](https://pypi.org/project/ipyvizzu) (📥 570 / month · 📦 3 · ⏱️ 19.10.2022):
`
	pip install ipyvizzu
	`
</details>
<details><summary><b><a href="https://github.com/martinRenou/ipycanvas">ipycanvas</a></b> (🥉23 ·  ⭐ 650) - Interactive Canvas in Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/martinRenou/ipycanvas) (👨‍💻 21 · 🔀 57 · 📦 7 · 📋 130 - 40% open · ⏱️ 24.10.2022):

  ```
  git clone https://github.com/martinRenou/ipycanvas
  ```

- [PyPi](https://pypi.org/project/ipycanvas) (📥 14K / month · 📦 24 · ⏱️ 29.08.2022):
  ```
  pip install ipycanvas
  ```
- [Conda](https://anaconda.org/conda-forge/ipycanvas) (📥 130K · ⏱️ 29.08.2022):
  ```
  conda install -c conda-forge ipycanvas
  ```
- [npm](https://www.npmjs.com/package/ipycanvas) (📥 2.1K / month · 📦 3 · ⏱️ 29.08.2022):
`
	npm install ipycanvas
	`
</details>
<details><summary><b><a href="https://github.com/bloomberg/ipydatagrid">ipydatagrid</a></b> (🥉23 ·  ⭐ 340) - Fast Datagrid widget for the Jupyter Notebook and JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/bloomberg/ipydatagrid) (👨‍💻 17 · 🔀 41 · 📦 54 · 📋 110 - 44% open · ⏱️ 24.02.2023):

  ```
  git clone https://github.com/bloomberg/ipydatagrid
  ```

- [PyPi](https://pypi.org/project/ipydatagrid) (📥 3.7K / month · 📦 5 · ⏱️ 29.11.2022):
  ```
  pip install ipydatagrid
  ```
- [Conda](https://anaconda.org/conda-forge/ipydatagrid) (📥 36K · ⏱️ 15.02.2023):
  ```
  conda install -c conda-forge ipydatagrid
  ```
- [npm](https://www.npmjs.com/package/ipydatagrid) (📥 800 / month · 📦 2 · ⏱️ 15.02.2023):
`
	npm install ipydatagrid
	`
</details>
<details><summary><b><a href="https://github.com/widgetti/ipyvuetify">ipyvuetify</a></b> (🥉23 ·  ⭐ 280) - Jupyter widgets based on vuetify UI components. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/widgetti/ipyvuetify) (👨‍💻 11 · 🔀 48 · 📦 730 · 📋 180 - 30% open · ⏱️ 23.02.2023):

  ```
  git clone https://github.com/mariobuikhuizen/ipyvuetify
  ```

- [PyPi](https://pypi.org/project/ipyvuetify) (📥 140K / month · 📦 29 · ⏱️ 02.09.2022):
  ```
  pip install ipyvuetify
  ```
- [Conda](https://anaconda.org/conda-forge/ipyvuetify) (📥 110K · ⏱️ 02.09.2022):
  ```
  conda install -c conda-forge ipyvuetify
  ```
- [npm](https://www.npmjs.com/package/jupyter-vuetify) (📥 8.7K / month · 📦 3 · ⏱️ 02.09.2022):
`
	npm install jupyter-vuetify
	`
</details>
<details><summary><b><a href="https://github.com/QuantStack/ipysheet">ipysheet</a></b> (🥉22 ·  ⭐ 520) - Jupyter handsontable integration. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/QuantStack/ipysheet) (👨‍💻 13 · 🔀 66 · 📦 6 · 📋 130 - 53% open · ⏱️ 28.11.2022):

  ```
  git clone https://github.com/QuantStack/ipysheet
  ```

- [PyPi](https://pypi.org/project/ipysheet) (📥 48K / month · 📦 21 · ⏱️ 28.11.2022):
  ```
  pip install ipysheet
  ```
- [Conda](https://anaconda.org/conda-forge/ipysheet) (📥 72K · ⏱️ 28.11.2022):
  ```
  conda install -c conda-forge ipysheet
  ```
- [npm](https://www.npmjs.com/package/ipysheet) (📥 1.7K / month · 📦 2 · ⏱️ 28.11.2022):
`
	npm install ipysheet
	`
</details>
<details><summary><b><a href="https://github.com/lgpage/nbtutor">nbtutor</a></b> (🥉22 ·  ⭐ 430) - Visualize Python code execution (line-by-line) in Jupyter Notebook cells. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/lgpage/nbtutor) (👨‍💻 4 · 🔀 39 · 📦 33 · 📋 43 - 44% open · ⏱️ 02.03.2023):

  ```
  git clone https://github.com/lgpage/nbtutor
  ```

- [PyPi](https://pypi.org/project/nbtutor) (📥 190 / month · 📦 3 · ⏱️ 19.04.2022):
  ```
  pip install nbtutor
  ```
- [Conda](https://anaconda.org/conda-forge/nbtutor) (📥 120K · ⏱️ 19.04.2022):
`
	conda install -c conda-forge nbtutor
	`
</details>
<details><summary><b><a href="https://github.com/spacetelescope/jdaviz">jdaviz</a></b> (🥉22 ·  ⭐ 88) - JWST astronomical data analysis tools in the Jupyter platform. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/spacetelescope/jdaviz) (👨‍💻 31 · 🔀 45 · 📋 870 - 37% open · ⏱️ 01.03.2023):

  ```
  git clone https://github.com/spacetelescope/jdaviz
  ```

- [PyPi](https://pypi.org/project/jdaviz) (📥 440 / month · ⏱️ 06.07.2022):
`
	pip install jdaviz
	`
</details>
<details><summary><b><a href="https://github.com/widgetti/ipyvue">ipyvue</a></b> (🥉22 ·  ⭐ 48) - Jupyter widgets base for Vue libraries. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/widgetti/ipyvue) (👨‍💻 3 · 🔀 12 · 📦 400 · 📋 8 - 37% open · ⏱️ 23.02.2023):

  ```
  git clone https://github.com/mariobuikhuizen/ipyvue
  ```

- [PyPi](https://pypi.org/project/ipyvue) (📥 140K / month · 📦 18 · ⏱️ 22.09.2022):
  ```
  pip install ipyvue
  ```
- [Conda](https://anaconda.org/conda-forge/ipyvue) (📥 76K · ⏱️ 26.09.2022):
  ```
  conda install -c conda-forge ipyvue
  ```
- [npm](https://www.npmjs.com/package/jupyter-vue) (📥 4.2K / month · 📦 12 · ⏱️ 23.02.2023):
`
	npm install jupyter-vue
	`
</details>
<details><summary><b><a href="https://github.com/vidartf/ipydatawidgets">ipydatawidgets</a></b> (🥉22 ·  ⭐ 36) - A set of widgets to help facilitate reuse of large datasets.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/vidartf/ipydatawidgets) (👨‍💻 5 · 🔀 9 · 📦 710 · 📋 16 - 43% open · ⏱️ 19.02.2023):

  ```
  git clone https://github.com/vidartf/ipydatawidgets
  ```

- [PyPi](https://pypi.org/project/ipydatawidgets) (📥 84K / month · 📦 26 · ⏱️ 24.08.2022):
  ```
  pip install ipydatawidgets
  ```
- [Conda](https://anaconda.org/conda-forge/ipydatawidgets) (📥 210K · ⏱️ 24.08.2022):
`
	conda install -c conda-forge ipydatawidgets
	`
</details>
<details><summary><b><a href="https://github.com/medialab/ipysigma">ipysigma</a></b> (🥉21 ·  ⭐ 83) - A Jupyter widget using sigma.js to render interactive networks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/medialab/ipysigma) (👨‍💻 6 · 🔀 10 · 📦 20 · 📋 190 - 21% open · ⏱️ 04.02.2023):

  ```
  git clone https://github.com/Yomguithereal/ipysigma
  ```

- [PyPi](https://pypi.org/project/ipysigma) (📥 490 / month · 📦 1 · ⏱️ 18.01.2023):
  ```
  pip install ipysigma
  ```
- [npm](https://www.npmjs.com/package/ipysigma) (📥 560 / month · 📦 2 · ⏱️ 18.01.2023):
`
	npm install ipysigma
	`
</details>
<details><summary><b><a href="https://github.com/QuantStack/ipytree">ipytree</a></b> (🥉19 ·  ⭐ 100) - A Tree Widget using Jupyter-widgets protocol and jsTree. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/QuantStack/ipytree) (👨‍💻 9 · 🔀 26 · 📦 2 · 📋 36 - 52% open · ⏱️ 23.11.2022):

  ```
  git clone https://github.com/QuantStack/ipytree
  ```

- [PyPi](https://pypi.org/project/ipytree) (📥 76K / month · 📦 8 · ⏱️ 23.08.2022):
  ```
  pip install ipytree
  ```
- [Conda](https://anaconda.org/conda-forge/ipytree) (📥 63K · ⏱️ 23.08.2022):
  ```
  conda install -c conda-forge ipytree
  ```
- [npm](https://www.npmjs.com/package/ipytree) (📥 500 / month · ⏱️ 23.08.2022):
`
	npm install ipytree
	`
</details>
<details><summary><b><a href="https://github.com/altair-viz/altair_viewer">Altair Viewer</a></b> (🥉17 ·  ⭐ 57) - Viewer for Altair and Vega-Lite visualizations. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/altair-viz/altair_viewer) (👨‍💻 3 · 🔀 8 · 📋 9 - 55% open · ⏱️ 23.02.2023):

  ```
  git clone https://github.com/altair-viz/altair_viewer
  ```

- [PyPi](https://pypi.org/project/altair_viewer) (📥 330K / month · 📦 12 · ⏱️ 06.11.2021):
  ```
  pip install altair_viewer
  ```
- [Conda](https://anaconda.org/conda-forge/altair_viewer) (📥 57K · ⏱️ 06.11.2021):
`
	conda install -c conda-forge altair_viewer
	`
</details>
<details><summary><b><a href="https://github.com/g2nb/igv-jupyter">igv.js widget</a></b> (🥉16 ·  ⭐ 150) - Extension for Jupyter which integrates igv.js. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/g2nb/igv-jupyter) (👨‍💻 5 · 🔀 15 · 📦 12 · ⏱️ 03.01.2023):

  ```
  git clone https://github.com/igvteam/igv-jupyter
  ```

- [PyPi](https://pypi.org/project/igv-jupyter) (📥 510 / month · 📦 1 · ⏱️ 14.06.2022):
`
	pip install igv-jupyter
	`
</details>
<details><summary>Show 20 hidden projects...</summary>

- <b><a href="https://github.com/man-group/dtale">D-Tale</a></b> (🥈30 · ⭐ 3.9K) - Visualizer for Pandas Data Structures. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code>
- <b><a href="https://github.com/quantopian/qgrid">qgrid</a></b> (🥈26 · ⭐ 2.9K · 💀) - An interactive grid for sorting, filtering, and editing DataFrames.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/pbugnion/gmaps">gmaps</a></b> (🥉23 · ⭐ 750 · 💀) - Google maps for Jupyter notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/mapbox/mapboxgl-jupyter">Mapbox GL</a></b> (🥉23 · ⭐ 630 · 💀) - Use Mapbox GL JS to visualize data in a Python Jupyter notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/maartenbreddels/ipywebrtc">ipywebrtc</a></b> (🥉23 · ⭐ 220 · 💀) - WebRTC for Jupyter notebook/lab. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/nicolaskruchten/jupyter_pivottablejs">pivottablejs</a></b> (🥉22 · ⭐ 520 · 💀) - Dragndrop Pivot Tables and Charts for Jupyter/IPython Notebook,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/PAIR-code/what-if-tool">What-If Tool</a></b> (🥉21 · ⭐ 780 · 💀) - Source code/webpage/demos for the What-If Tool. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/OpenGeoscience/geonotebook">geonotebook</a></b> (🥉16 · ⭐ 1.1K · 💀) - A Jupyter notebook extension for geospatial visualization.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/CermakM/jupyter-datatables">Jupyter DataTables</a></b> (🥉15 · ⭐ 180 · 💀) - Jupyter Notebook extension leveraging pandas DataFrames.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/nipy/niwidgets">niwidgets</a></b> (🥉15 · ⭐ 81 · 💀) - Neuroimaging widgets for jupyter notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/vidartf/ipyscales">ipyscales</a></b> (🥉15 · ⭐ 13 · 📉) - A widget library for scales. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/agermanidis/pigeon">pigeon</a></b> (🥉13 · ⭐ 660 · 💀) - Quickly annotate data from the comfort of your Jupyter notebook. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/DGothrek/ipyaggrid">ipyaggrid</a></b> (🥉13 · ⭐ 13 · 💀) - Jupyter widget - ag-grid in the notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/maartenbreddels/ipymaterialui">ipymaterialui</a></b> (🥉12 · ⭐ 84 · 💀) - Jupyter Widgets based on React Material UI components. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/leifwalsh/perfume">perfume</a></b> (🥉12 · ⭐ 33 · 💀) - Interactive performance benchmarking in Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/ipyannotate/ipyannotate">ipyannotate</a></b> (🥉11 · ⭐ 130 · 💀) - Jupyter Widget for data annotation. <code>❗Unlicensed</code>
- <b><a href="https://github.com/jtpio/ipyp5">ipyp5</a></b> (🥉11 · ⭐ 33 · 💀) - p5.js Jupyter Widget. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/timkpaine/tributary">tributary</a></b> (🥉11 · ⭐ 7) - Streaming reactive and dataflow graphs in Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/GianniBalistreri/easyexplore">easyexplore</a></b> (🥉9 · ⭐ 4 · 💤) - Toolbox for easy and effective data exploration in Python. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/asvcode/Vision_UI">Vision UI</a></b> (🥉7 · ⭐ 250 · 💀) - UI visual interface for fastai - now compatible with Google.. <code>❗Unlicensed</code>
</details>
<br>

## Jupyter Extensions

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Application plugins that extend the functionality of Jupyter itself._

<details><summary><b><a href="https://github.com/ipython-contrib/jupyter_contrib_nbextensions">Contrib NBextensions</a></b> (🥇31 ·  ⭐ 5K · 📉) - A collection of various notebook extensions for.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/ipython-contrib/jupyter_contrib_nbextensions) (👨‍💻 140 · 🔀 800 · 📋 810 - 43% open · ⏱️ 21.12.2022):

  ```
  git clone https://github.com/ipython-contrib/jupyter_contrib_nbextensions
  ```

- [PyPi](https://pypi.org/project/jupyter_contrib_nbextensions) (📥 340K / month · 📦 220 · ⏱️ 15.11.2022):
  ```
  pip install jupyter_contrib_nbextensions
  ```
- [Conda](https://anaconda.org/conda-forge/jupyter_contrib_nbextensions) (📥 1.6M · ⏱️ 03.12.2022):
`
	conda install -c conda-forge jupyter_contrib_nbextensions
	`
</details>
<details><summary><b><a href="https://github.com/jupyter/nbgrader">nbgrader</a></b> (🥇29 ·  ⭐ 1.2K) - A system for assigning and grading notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbgrader) (👨‍💻 98 · 🔀 320 · 📥 100 · 📦 380 · 📋 860 - 27% open · ⏱️ 06.01.2023):

  ```
  git clone https://github.com/jupyter/nbgrader
  ```

- [PyPi](https://pypi.org/project/nbgrader) (📥 7.2K / month · 📦 17 · ⏱️ 27.09.2022):
  ```
  pip install nbgrader
  ```
- [Conda](https://anaconda.org/conda-forge/nbgrader) (📥 130K · ⏱️ 28.09.2022):
`
	conda install -c conda-forge nbgrader
	`
</details>
<details><summary><b><a href="https://github.com/jupyter-server/jupyter-resource-usage">Resource Usage</a></b> (🥈27 ·  ⭐ 360) - Jupyter Notebook Extension for monitoring your own Resource.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/jupyter-server/jupyter-resource-usage) (👨‍💻 30 · 🔀 87 · 📥 180 · 📦 310 · 📋 69 - 49% open · ⏱️ 21.02.2023):

  ```
  git clone https://github.com/jupyter-server/jupyter-resource-usage
  ```

- [PyPi](https://pypi.org/project/jupyter-resource-usage) (📥 25K / month · 📦 5 · ⏱️ 06.01.2023):
  ```
  pip install jupyter-resource-usage
  ```
- [Conda](https://anaconda.org/conda-forge/nbresuse) (📥 520K · ⏱️ 23.11.2020):
  ```
  conda install -c conda-forge nbresuse
  ```
- [npm](https://www.npmjs.com/package/@jupyter-server/resource-usage) (📥 730 / month · 📦 2 · ⏱️ 20.02.2023):
`
	npm install @jupyter-server/resource-usage
	`
</details>
<details><summary><b><a href="https://github.com/jupyterhub/jupyter-server-proxy">jupyter-server-proxy</a></b> (🥈26 ·  ⭐ 270) - Jupyter notebook server extension to proxy web services. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/jupyter-server-proxy) (👨‍💻 66 · 🔀 130 · 📦 2 · 📋 180 - 38% open · ⏱️ 04.02.2023):

  ```
  git clone https://github.com/jupyterhub/jupyter-server-proxy
  ```

- [PyPi](https://pypi.org/project/jupyter-server-proxy) (📥 160K / month · 📦 120 · ⏱️ 08.09.2022):
  ```
  pip install jupyter-server-proxy
  ```
- [Conda](https://anaconda.org/conda-forge/jupyter-server-proxy) (📥 1.2M · ⏱️ 08.09.2022):
  ```
  conda install -c conda-forge jupyter-server-proxy
  ```
- [npm](https://www.npmjs.com/package/@jupyterlab/server-proxy) (📥 8.4K / month · 📦 3 · ⏱️ 08.09.2022):
`
	npm install @jupyterlab/server-proxy
	`
</details>
<details><summary><b><a href="https://github.com/jupyterhub/nbgitpuller">nbgitpuller</a></b> (🥈26 ·  ⭐ 170) - Jupyter server extension to sync a git repository one-way to a.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/nbgitpuller) (👨‍💻 25 · 🔀 71 · 📦 600 · 📋 150 - 45% open · ⏱️ 04.01.2023):

  ```
  git clone https://github.com/jupyterhub/nbgitpuller
  ```

- [PyPi](https://pypi.org/project/nbgitpuller) (📥 11K / month · 📦 18 · ⏱️ 08.11.2022):
  ```
  pip install nbgitpuller
  ```
- [Conda](https://anaconda.org/conda-forge/nbgitpuller) (📥 55K · ⏱️ 09.11.2022):
`
	conda install -c conda-forge nbgitpuller
	`
</details>
<details><summary><b><a href="https://github.com/Jupyter-contrib/jupyter_nbextensions_configurator">NBextensions Configurator</a></b> (🥈25 ·  ⭐ 920) - A jupyter notebook serverextension providing config.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Jupyter-contrib/jupyter_nbextensions_configurator) (👨‍💻 22 · 🔀 110 · 📋 88 - 63% open · ⏱️ 21.12.2022):

  ```
  git clone https://github.com/jupyter-contrib/jupyter_nbextensions_configurator
  ```

- [PyPi](https://pypi.org/project/jupyter_nbextensions_configurator) (📥 360K / month · 📦 180 · ⏱️ 29.12.2018):
  ```
  pip install jupyter_nbextensions_configurator
  ```
- [Conda](https://anaconda.org/conda-forge/jupyter_nbextensions_configurator) (📥 1.3M · ⏱️ 11.12.2022):
`
	conda install -c conda-forge jupyter_nbextensions_configurator
	`
</details>
<details><summary><b><a href="https://github.com/jupyterhub/jupyter-rsession-proxy">Rsession Proxy</a></b> (🥈22 ·  ⭐ 100) - Jupyter extensions for running an RStudio rsession proxy. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/jupyter-rsession-proxy) (👨‍💻 21 · 🔀 83 · 📦 43 · 📋 79 - 40% open · ⏱️ 24.09.2022):

  ```
  git clone https://github.com/jupyterhub/jupyter-rsession-proxy
  ```

- [PyPi](https://pypi.org/project/jupyter-rsession-proxy) (📥 16K / month · 📦 1 · ⏱️ 07.09.2022):
  ```
  pip install jupyter-rsession-proxy
  ```
- [Conda](https://anaconda.org/conda-forge/jupyter-rsession-proxy) (📥 16K · ⏱️ 08.09.2022):
`
	conda install -c conda-forge jupyter-rsession-proxy
	`
</details>
<details><summary><b><a href="https://github.com/mamba-org/gator">gator</a></b> (🥉18 ·  ⭐ 240) - Conda environment and package management extension from within Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mamba-org/gator) (👨‍💻 25 · 🔀 27 · 📥 2 · 📦 4 · 📋 61 - 34% open · ⏱️ 08.01.2023):

  ```
  git clone https://github.com/mamba-org/gator
  ```

- [PyPi](https://pypi.org/project/mamba-gator) (📥 26 / month · ⏱️ 25.07.2022):
  ```
  pip install mamba-gator
  ```
- [Conda](https://anaconda.org/conda-forge/mamba_gator) (📥 27K · ⏱️ 26.07.2022):
  ```
  conda install -c conda-forge mamba_gator
  ```
- [npm](https://www.npmjs.com/package/@mamba-org/gator-lab) (📥 120 / month · 📦 2 · ⏱️ 03.09.2021):
`
	npm install @mamba-org/gator-lab
	`
</details>
<details><summary><b><a href="https://github.com/jupyterlab-contrib/jupyter-archive">jupyter-archive</a></b> (🥉18 ·  ⭐ 61) - A Jupyter/Jupyterlab extension to make, download and extract.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab-contrib/jupyter-archive) (👨‍💻 10 · 🔀 11 · 📥 3.3K · 📦 2 · 📋 36 - 5% open · ⏱️ 03.02.2023):

  ```
  git clone https://github.com/jupyterlab-contrib/jupyter-archive
  ```

- [PyPi](https://pypi.org/project/jupyter-archive) (📥 5.1K / month · 📦 1 · ⏱️ 09.01.2023):
  ```
  pip install jupyter-archive
  ```
- [Conda](https://anaconda.org/conda-forge/jupyter-archive) (📥 38K · ⏱️ 08.01.2023):
  ```
  conda install -c conda-forge jupyter-archive
  ```
- [npm](https://www.npmjs.com/package/@hadim/jupyter-archive) (📥 350 / month · 📦 2 · ⏱️ 08.01.2023):
`
	npm install @hadim/jupyter-archive
	`
</details>
<details><summary><b><a href="https://github.com/krishnan-r/sparkmonitor">Spark Monitor</a></b> (🥉16 ·  ⭐ 170 · 💤) - Monitor Apache Spark from Jupyter Notebook. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/krishnan-r/sparkmonitor) (👨‍💻 3 · 🔀 51 · 📥 2.4K · 📋 37 - 81% open · ⏱️ 16.05.2022):

  ```
  git clone https://github.com/krishnan-r/sparkmonitor
  ```

- [PyPi](https://pypi.org/project/sparkmonitor) (📥 2.6K / month · ⏱️ 18.01.2022):
  ```
  pip install sparkmonitor
  ```
- [Docker Hub](https://hub.docker.com/r/krishnanr/sparkmonitor) (📥 940 · ⏱️ 04.10.2019):
`
	docker pull krishnanr/sparkmonitor
	`
</details>
<details><summary><b><a href="https://github.com/drillan/jupyter-black">Jupyter Black</a></b> (🥉8 ·  ⭐ 420 · 💀) - Black formatter for Jupyter Notebook. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/drillan/jupyter-black) (👨‍💻 2 · 🔀 23 · 📋 23 - 43% open · ⏱️ 01.02.2020):

      ```
      git clone https://github.com/drillan/jupyter-black
      ```

  </details>
  <details><summary>Show 14 hidden projects...</summary>

- <b><a href="https://github.com/man-group/dtale">dtale</a></b> (🥇30 · ⭐ 3.9K) - Visualizer for pandas data structures. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code>
- <b><a href="https://github.com/dunovank/jupyter-themes">Jupyter Themes</a></b> (🥈28 · ⭐ 9.5K · 💀) - Custom Jupyter Notebook Themes. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/oschuett/appmode">Appmode</a></b> (🥈22 · ⭐ 410 · 💀) - A Jupyter extensions that turns notebooks into web applications. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/8080labs/pyforest">pyforest</a></b> (🥉20 · ⭐ 1K · 💀) - pyforest - feel the bliss of automated imports. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/lspvic/jupyter_tensorboard">jupyter-tensorboard</a></b> (🥉19 · ⭐ 460 · 💀) - Start Tensorboard in Jupyter Notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/googlecolab/jupyter_http_over_ws">HTTP-over-WebSocket</a></b> (🥉18 · ⭐ 250 · 💀) - Jupyter support for HTTP-over-ws. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/mozilla/jupyter-spark">Jupyter Spark</a></b> (🥉18 · ⭐ 190 · 💀) - Jupyter Notebook extension for Apache Spark integration. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code>
- <b><a href="https://github.com/codota/jupyter-tabnine">jupyter-tabnine</a></b> (🥉17 · ⭐ 770 · 💀) - Autocompletion with Deep Learning on Jupyter Notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/data-8/nbzip">nbzip</a></b> (🥉17 · ⭐ 80 · 💀) - Zips and downloads all the contents of a jupyter notebook. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/jupyter-incubator/contentmanagement">Content Management</a></b> (🥉16 · ⭐ 76 · 💀) - Jupyter Content Management Extensions. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/Anaconda-Platform/nb_conda">nb_conda</a></b> (🥉15 · ⭐ 130 · 💀) - Conda environment and package access extension from within Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/thoth-station/jupyter-nbrequirements">jupyter-nbrequirements</a></b> (🥉15 · ⭐ 14) - Dependency management and optimization in Jupyter.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/paypal/PPExtensions">PPExtensions</a></b> (🥉13 · ⭐ 48 · 💀) - Set of iPython and Jupyter extensions to improve user.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/willkessler/jupyterterminals">jupyterterminals</a></b> (🥉7 · ⭐ 8) - Jupyter plugin to support inline terminal shells along with.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Jupyter Magic

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Extensions that provide magic commands to access convenient functionality within a notebook._

<details><summary><b><a href="https://github.com/jupyter-incubator/sparkmagic">sparkmagic</a></b> (🥇32 ·  ⭐ 1.2K) - Jupyter magics and kernels for working with remote Spark clusters. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-incubator/sparkmagic) (👨‍💻 59 · 🔀 420 · 📦 300 · 📋 430 - 32% open · ⏱️ 11.02.2023):

  ```
  git clone https://github.com/jupyter-incubator/sparkmagic
  ```

- [PyPi](https://pypi.org/project/sparkmagic) (📥 40K / month · 📦 20 · ⏱️ 30.01.2023):
  ```
  pip install sparkmagic
  ```
- [Conda](https://anaconda.org/conda-forge/sparkmagic) (📥 66K · ⏱️ 30.01.2023):
`
	conda install -c conda-forge sparkmagic
	`
</details>
<details><summary><b><a href="https://github.com/catherinedevlin/ipython-sql">ipython-sql</a></b> (🥇31 ·  ⭐ 1.7K · 📈) - %%sql magic for IPython, hopefully evolving into full SQL client. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/catherinedevlin/ipython-sql) (👨‍💻 55 · 🔀 290 · 📦 4.1K · 📋 150 - 73% open · ⏱️ 26.02.2023):

  ```
  git clone https://github.com/catherinedevlin/ipython-sql
  ```

- [PyPi](https://pypi.org/project/ipython-sql) (📥 120K / month · 📦 69 · ⏱️ 12.06.2022):
  ```
  pip install ipython-sql
  ```
- [Conda](https://anaconda.org/conda-forge/ipython-sql) (📥 210K · ⏱️ 13.11.2021):
`
	conda install -c conda-forge ipython-sql
	`
</details>
<details><summary><b><a href="https://github.com/rasbt/watermark">watermark</a></b> (🥈22 ·  ⭐ 770) - An IPython magic extension for printing date and time stamps, version.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/rasbt/watermark) (👨‍💻 17 · 🔀 81 · 📦 1.8K · 📋 45 - 37% open · ⏱️ 13.09.2022):

  ```
  git clone https://github.com/rasbt/watermark
  ```

- [PyPi](https://pypi.org/project/watermark) (📥 44K / month · 📦 79 · ⏱️ 27.05.2022):
  ```
  pip install watermark
  ```
- [Conda](https://anaconda.org/conda-forge/watermark) (📥 250K · ⏱️ 30.05.2022):
`
	conda install -c conda-forge watermark
	`
</details>
<details><summary><b><a href="https://github.com/rossant/ipycache">ipycache</a></b> (🥉16 ·  ⭐ 130 · 💤) - Defines a %%cache cell magic in the IPython notebook to cache.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/rossant/ipycache) (👨‍💻 10 · 🔀 24 · 📦 24 · 📋 39 - 43% open · ⏱️ 22.08.2022):

  ```
  git clone https://github.com/rossant/ipycache
  ```

- [PyPi](https://pypi.org/project/ipycache) (📥 160 / month · 📦 6 · ⏱️ 13.10.2013):
  ```
  pip install ipycache
  ```
- [Conda](https://anaconda.org/conda-forge/ipycache) (📥 75K · ⏱️ 07.07.2020):
`
	conda install -c conda-forge ipycache
	`
</details>
<details><summary>Show 8 hidden projects...</summary>

- <b><a href="https://github.com/nteract/pick">pick</a></b> (🥈21 · ⭐ 570 · 💀) - Customize your kernels on Launch!. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/csurfer/pyheatmagic">heat</a></b> (🥈17 · ⭐ 1K · 💀) - IPython magic command to profile and view your python code as a heat map. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/csurfer/blackcellmagic">blackcellmagic</a></b> (🥈17 · ⭐ 300 · 💀) - IPython magic command to format python code in cell using.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/ShopRunner/jupyter-notify">jupyter-notify</a></b> (🥉16 · ⭐ 570 · 💀) - A Jupyter Notebook magic for browser notifications of cell.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/ResidentMario/py_d3">py_d3</a></b> (🥉15 · ⭐ 450 · 💀) - D3 block magic for Jupyter notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/tmthyjames/SQLCell">SQLCell</a></b> (🥉13 · ⭐ 150 · 💀) - SQLCell is a magic function for the Jupyter Notebook that executes.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/dnanhkhoa/nb_black">nb_black</a></b> (🥉13 · ⭐ 62 · 💀) - A simple extension for Jupyter Notebook and Jupyter Lab to beautify.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/krassowski/jupyter-manim">jupyter-manim</a></b> (🥉12 · ⭐ 190 · 💀) - manim cell magic for IPython/Jupyter to show the output video. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Jupyter Extensions

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Application plugins that extend the functionality of Jupyter itself._

<details><summary><b><a href="https://github.com/ipython-contrib/jupyter_contrib_nbextensions">Contrib NBextensions</a></b> (🥇31 ·  ⭐ 5K · 📉) - A collection of various notebook extensions for.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/ipython-contrib/jupyter_contrib_nbextensions) (👨‍💻 140 · 🔀 800 · 📋 810 - 43% open · ⏱️ 21.12.2022):

  ```
  git clone https://github.com/ipython-contrib/jupyter_contrib_nbextensions
  ```

- [PyPi](https://pypi.org/project/jupyter_contrib_nbextensions) (📥 340K / month · 📦 220 · ⏱️ 15.11.2022):
  ```
  pip install jupyter_contrib_nbextensions
  ```
- [Conda](https://anaconda.org/conda-forge/jupyter_contrib_nbextensions) (📥 1.6M · ⏱️ 03.12.2022):
`
	conda install -c conda-forge jupyter_contrib_nbextensions
	`
</details>
<details><summary><b><a href="https://github.com/jupyter/nbgrader">nbgrader</a></b> (🥇29 ·  ⭐ 1.2K) - A system for assigning and grading notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbgrader) (👨‍💻 98 · 🔀 320 · 📥 100 · 📦 380 · 📋 860 - 27% open · ⏱️ 06.01.2023):

  ```
  git clone https://github.com/jupyter/nbgrader
  ```

- [PyPi](https://pypi.org/project/nbgrader) (📥 7.2K / month · 📦 17 · ⏱️ 27.09.2022):
  ```
  pip install nbgrader
  ```
- [Conda](https://anaconda.org/conda-forge/nbgrader) (📥 130K · ⏱️ 28.09.2022):
`
	conda install -c conda-forge nbgrader
	`
</details>
<details><summary><b><a href="https://github.com/jupyter-server/jupyter-resource-usage">Resource Usage</a></b> (🥈27 ·  ⭐ 360) - Jupyter Notebook Extension for monitoring your own Resource.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/jupyter-server/jupyter-resource-usage) (👨‍💻 30 · 🔀 87 · 📥 180 · 📦 310 · 📋 69 - 49% open · ⏱️ 21.02.2023):

  ```
  git clone https://github.com/jupyter-server/jupyter-resource-usage
  ```

- [PyPi](https://pypi.org/project/jupyter-resource-usage) (📥 25K / month · 📦 5 · ⏱️ 06.01.2023):
  ```
  pip install jupyter-resource-usage
  ```
- [Conda](https://anaconda.org/conda-forge/nbresuse) (📥 520K · ⏱️ 23.11.2020):
  ```
  conda install -c conda-forge nbresuse
  ```
- [npm](https://www.npmjs.com/package/@jupyter-server/resource-usage) (📥 730 / month · 📦 2 · ⏱️ 20.02.2023):
`
	npm install @jupyter-server/resource-usage
	`
</details>
<details><summary><b><a href="https://github.com/jupyterhub/jupyter-server-proxy">jupyter-server-proxy</a></b> (🥈26 ·  ⭐ 270) - Jupyter notebook server extension to proxy web services. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/jupyter-server-proxy) (👨‍💻 66 · 🔀 130 · 📦 2 · 📋 180 - 38% open · ⏱️ 04.02.2023):

  ```
  git clone https://github.com/jupyterhub/jupyter-server-proxy
  ```

- [PyPi](https://pypi.org/project/jupyter-server-proxy) (📥 160K / month · 📦 120 · ⏱️ 08.09.2022):
  ```
  pip install jupyter-server-proxy
  ```
- [Conda](https://anaconda.org/conda-forge/jupyter-server-proxy) (📥 1.2M · ⏱️ 08.09.2022):
  ```
  conda install -c conda-forge jupyter-server-proxy
  ```
- [npm](https://www.npmjs.com/package/@jupyterlab/server-proxy) (📥 8.4K / month · 📦 3 · ⏱️ 08.09.2022):
`
	npm install @jupyterlab/server-proxy
	`
</details>
<details><summary><b><a href="https://github.com/jupyterhub/nbgitpuller">nbgitpuller</a></b> (🥈26 ·  ⭐ 170) - Jupyter server extension to sync a git repository one-way to a.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/nbgitpuller) (👨‍💻 25 · 🔀 71 · 📦 600 · 📋 150 - 45% open · ⏱️ 04.01.2023):

  ```
  git clone https://github.com/jupyterhub/nbgitpuller
  ```

- [PyPi](https://pypi.org/project/nbgitpuller) (📥 11K / month · 📦 18 · ⏱️ 08.11.2022):
  ```
  pip install nbgitpuller
  ```
- [Conda](https://anaconda.org/conda-forge/nbgitpuller) (📥 55K · ⏱️ 09.11.2022):
`
	conda install -c conda-forge nbgitpuller
	`
</details>
<details><summary><b><a href="https://github.com/Jupyter-contrib/jupyter_nbextensions_configurator">NBextensions Configurator</a></b> (🥈25 ·  ⭐ 920) - A jupyter notebook serverextension providing config.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Jupyter-contrib/jupyter_nbextensions_configurator) (👨‍💻 22 · 🔀 110 · 📋 88 - 63% open · ⏱️ 21.12.2022):

  ```
  git clone https://github.com/jupyter-contrib/jupyter_nbextensions_configurator
  ```

- [PyPi](https://pypi.org/project/jupyter_nbextensions_configurator) (📥 360K / month · 📦 180 · ⏱️ 29.12.2018):
  ```
  pip install jupyter_nbextensions_configurator
  ```
- [Conda](https://anaconda.org/conda-forge/jupyter_nbextensions_configurator) (📥 1.3M · ⏱️ 11.12.2022):
`
	conda install -c conda-forge jupyter_nbextensions_configurator
	`
</details>
<details><summary><b><a href="https://github.com/jupyterhub/jupyter-rsession-proxy">Rsession Proxy</a></b> (🥈22 ·  ⭐ 100) - Jupyter extensions for running an RStudio rsession proxy. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/jupyter-rsession-proxy) (👨‍💻 21 · 🔀 83 · 📦 43 · 📋 79 - 40% open · ⏱️ 24.09.2022):

  ```
  git clone https://github.com/jupyterhub/jupyter-rsession-proxy
  ```

- [PyPi](https://pypi.org/project/jupyter-rsession-proxy) (📥 16K / month · 📦 1 · ⏱️ 07.09.2022):
  ```
  pip install jupyter-rsession-proxy
  ```
- [Conda](https://anaconda.org/conda-forge/jupyter-rsession-proxy) (📥 16K · ⏱️ 08.09.2022):
  `conda install -c conda-forge jupyter-rsession-proxy`
  </de

## Jupyter Kernels

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Jupyter kernels that run and introspect the user's code in a given language._

<details><summary><b><a href="https://github.com/ipython/ipykernel">IPython Kernel</a></b> (🥇38 ·  ⭐ 540 · 📉) - IPython Kernel for Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/ipython/ipykernel) (👨‍💻 160 · 🔀 330 · 📥 1.2K · 📦 230K · 📋 470 - 52% open · ⏱️ 26.02.2023):

  ```
  git clone https://github.com/ipython/ipykernel
  ```

- [PyPi](https://pypi.org/project/ipykernel) (📥 14M / month · 📦 9.9K · ⏱️ 15.06.2022):
  ```
  pip install ipykernel
  ```
- [Conda](https://anaconda.org/anaconda/ipykernel) (📥 610K · 📦 35 · ⏱️ 05.01.2023):
`
	conda install -c anaconda ipykernel
	`
</details>
<details><summary><b><a href="https://github.com/IRkernel/IRkernel">IRkernel</a></b> (🥇25 ·  ⭐ 1.6K) - R kernel for Jupyter. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/IRkernel/IRkernel) (👨‍💻 43 · 🔀 290 · 📋 580 - 11% open · ⏱️ 20.01.2023):

  ```
  git clone https://github.com/IRkernel/IRkernel
  ```

- [Conda](https://anaconda.org/r/r-irkernel) (📥 110K · ⏱️ 31.05.2022):
  ```
  conda install -c r r-irkernel
  ```
- [Docker Hub](https://hub.docker.com/r/jupyter/r-notebook) (📥 1.5M · ⭐ 49 · ⏱️ 28.02.2023):
`
	docker pull jupyter/r-notebook
	`
</details>
<details><summary><b><a href="https://github.com/lfortran/lfortran">LFortran</a></b> (🥇25 ·  ⭐ 540) - Official main repository for LFortran. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lfortran/lfortran) (👨‍💻 54 · 🔀 58 · 📋 780 - 78% open · ⏱️ 02.03.2023):

  ```
  git clone https://github.com/lfortran/lfortran
  ```

- [PyPi](https://pypi.org/project/lfortran) (📥 120 / month · ⏱️ 31.07.2020):
  ```
  pip install lfortran
  ```
- [Conda](https://anaconda.org/conda-forge/lfortran) (📥 52K · ⏱️ 18.10.2022):
`
	conda install -c conda-forge lfortran
	`
</details>
<details><summary><b><a href="https://github.com/Calysto/metakernel">Metakernel</a></b> (🥇25 ·  ⭐ 300) - Jupyter/IPython Kernel Tools. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Calysto/metakernel) (👨‍💻 32 · 🔀 81 · 📥 75 · 📦 700 · 📋 140 - 20% open · ⏱️ 12.12.2022):

  ```
  git clone https://github.com/Calysto/metakernel
  ```

- [PyPi](https://pypi.org/project/metakernel) (📥 29K / month · 📦 75 · ⏱️ 12.12.2022):
  ```
  pip install metakernel
  ```
- [Conda](https://anaconda.org/conda-forge/metakernel) (📥 670K · ⏱️ 12.12.2022):
`
	conda install -c conda-forge metakernel
	`
</details>
<details><summary><b><a href="https://github.com/dotnet/interactive">.NET Interactive</a></b> (🥇24 ·  ⭐ 2.3K) - .NET Interactive combines the power of .NET with many other.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dotnet/interactive) (👨‍💻 100 · 🔀 310 · 📥 410 · 📋 1.2K - 30% open · ⏱️ 02.03.2023):

      ```
      git clone https://github.com/dotnet/interactive
      ```

  </details>
  <details><summary><b><a href="https://github.com/almond-sh/almond">almond</a></b> (🥇24 ·  ⭐ 1.5K) - A Scala kernel for Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/almond-sh/almond) (👨‍💻 39 · 🔀 240 · 📥 1.5K · 📋 320 - 37% open · ⏱️ 01.02.2023):

  ```
  git clone https://github.com/almond-sh/almond
  ```

- [Docker Hub](https://hub.docker.com/r/almondsh/almond) (📥 17K · ⭐ 6 · ⏱️ 01.02.2023):
`
	docker pull almondsh/almond
	`
</details>
<details><summary><b><a href="https://github.com/jupyter-server/kernel_gateway">Kernel Gateway</a></b> (🥇24 ·  ⭐ 420) - Jupyter Kernel Gateway. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-server/kernel_gateway) (👨‍💻 44 · 🔀 130 · 📥 110 · 📋 180 - 8% open · ⏱️ 06.02.2023):

  ```
  git clone https://github.com/jupyter/kernel_gateway
  ```

- [PyPi](https://pypi.org/project/jupyter-kernel-gateway) (📥 43K / month · 📦 6 · ⏱️ 24.08.2021):
  ```
  pip install jupyter-kernel-gateway
  ```
- [Conda](https://anaconda.org/conda-forge/jupyter_kernel_gateway) (📥 190K · ⏱️ 07.02.2023):
`
	conda install -c conda-forge jupyter_kernel_gateway
	`
</details>
<details><summary><b><a href="https://github.com/jupyter-xeus/xeus-python">xeus-python</a></b> (🥇24 ·  ⭐ 370) - Jupyter kernel for the Python programming language. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-xeus/xeus-python) (👨‍💻 21 · 🔀 65 · 📋 180 - 32% open · ⏱️ 02.03.2023):

  ```
  git clone https://github.com/jupyter-xeus/xeus-python
  ```

- [PyPi](https://pypi.org/project/xeus-python) (📥 12K / month · 📦 3 · ⏱️ 06.12.2022):
  ```
  pip install xeus-python
  ```
- [Conda](https://anaconda.org/conda-forge/xeus-python) (📥 1.2M · ⏱️ 16.02.2023):
`
	conda install -c conda-forge xeus-python
	`
</details>
<details><summary><b><a href="https://github.com/n-riesco/ijavascript">IJavascript</a></b> (🥈23 ·  ⭐ 2K) - IJavascript is a javascript kernel for the Jupyter notebook. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/n-riesco/ijavascript) (👨‍💻 16 · 🔀 180 · 📦 71 · 📋 230 - 23% open · ⏱️ 28.12.2022):

  ```
  git clone https://github.com/n-riesco/ijavascript
  ```

- [npm](https://www.npmjs.com/package/ijavascript) (📥 2.8K / month · 📦 22 · ⏱️ 15.11.2021):

```sh
npm install -g ijavascript
```

</details>
<details><summary><b><a href="https://github.com/apache/incubator-toree">Apache Toree</a></b> (🥈23 ·  ⭐ 710) - Jupyter kernel for Apache Spark. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/incubator-toree) (👨‍💻 110 · 🔀 220 · ⏱️ 08.02.2023):

  ```
  git clone https://github.com/apache/incubator-toree
  ```

- [PyPi](https://pypi.org/project/toree) (📥 10K / month · 📦 9 · ⏱️ 21.04.2022):
`
	pip install toree
	`
</details>
<details><summary><b><a href="https://github.com/gopherdata/gophernotes">gophernotes</a></b> (🥈22 ·  ⭐ 3.5K · 💤) - The Go kernel for Jupyter notebooks and nteract. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gopherdata/gophernotes) (👨‍💻 29 · 🔀 240 · 📥 41 · 📦 9 · 📋 180 - 29% open · ⏱️ 08.07.2022):

  ```
  git clone https://github.com/gopherdata/gophernotes
  ```

- [Docker Hub](https://hub.docker.com/r/gopherdata/gophernotes) (📥 86K · ⭐ 7 · ⏱️ 22.12.2018):
  ```
  docker pull gopherdata/gophernotes
  ```
- [Go](https://pkg.go.dev/github.com/gopherdata/gophernotes) (📦 1 · ⏱️ 31.05.2022):
`
	go install github.com/gopherdata/gophernotes
	`
</details>
<details><summary><b><a href="https://github.com/jupyter-xeus/xeus-cling">xeus-cling</a></b> (🥈22 ·  ⭐ 2.5K) - Jupyter kernel for the C++ programming language. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-xeus/xeus-cling) (👨‍💻 24 · 🔀 260 · 📋 260 - 53% open · ⏱️ 03.02.2023):

  ```
  git clone https://github.com/jupyter-xeus/xeus-cling
  ```

- [Conda](https://anaconda.org/conda-forge/xeus-cling) (📥 190K · ⏱️ 31.01.2023):
`
	conda install -c conda-forge xeus-cling
	`
</details>
<details><summary><b><a href="https://github.com/JuliaLang/IJulia.jl">IJulia.jl</a></b> (🥈21 ·  ⭐ 2.6K) - Julia kernel for Jupyter. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/JuliaLang/IJulia.jl) (👨‍💻 110 · 🔀 400 · 📋 820 - 15% open · ⏱️ 17.01.2023):

      ```
      git clone https://github.com/JuliaLang/IJulia.jl
      ```

  </details>
  <details><summary><b><a href="https://github.com/IHaskell/IHaskell">IHaskell</a></b> (🥈21 ·  ⭐ 2.4K) - A Haskell kernel for the Jupyter project. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/IHaskell/IHaskell) (👨‍💻 110 · 🔀 250 · 📋 760 - 6% open · ⏱️ 19.12.2022):

  ```
  git clone https://github.com/gibiansky/IHaskell
  ```

- [npm](https://www.npmjs.com/package/ihaskell_jupyterlab) (📥 13 / month · ⏱️ 01.08.2018):
`
	npm install ihaskell_jupyterlab
	`
</details>
<details><summary><b><a href="https://github.com/takluyver/bash_kernel">Bash Kernel</a></b> (🥈21 ·  ⭐ 620) - A bash kernel for IPython. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/takluyver/bash_kernel) (👨‍💻 16 · 🔀 130 · 📋 99 - 36% open · ⏱️ 18.12.2022):

  ```
  git clone https://github.com/takluyver/bash_kernel
  ```

- [PyPi](https://pypi.org/project/bash_kernel) (📥 12K / month · 📦 28 · ⏱️ 17.12.2022):
  ```
  pip install bash_kernel
  ```
- [Conda](https://anaconda.org/conda-forge/bash_kernel) (📥 100K · ⏱️ 19.12.2022):
  ```
  con
  ```

## Notebook Sharing & Conversion

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Tools to share, convert and simplify collaboration (e.g., via git) with notebook files._

<details><summary><b><a href="https://github.com/jupyter/nbconvert">nbconvert</a></b> (🥇39 ·  ⭐ 1.4K) - Jupyter Notebook Conversion. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbconvert) (👨‍💻 260 · 🔀 510 · 📥 290 · 📦 190K · 📋 1.1K - 44% open · ⏱️ 20.02.2023):

  ```
  git clone https://github.com/jupyter/nbconvert
  ```

- [PyPi](https://pypi.org/project/nbconvert) (📥 20M / month · 📦 8.3K · ⏱️ 24.01.2023):
  ```
  pip install nbconvert
  ```
- [Conda](https://anaconda.org/conda-forge/nbconvert) (📥 11M · ⏱️ 24.01.2023):
`
	conda install -c conda-forge nbconvert
	`
</details>
<details><summary><b><a href="https://github.com/mwouts/jupytext">Jupytext</a></b> (🥇35 ·  ⭐ 5.8K) - Jupyter Notebooks as Markdown Documents, Julia, Python or R scripts. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mwouts/jupytext) (👨‍💻 78 · 🔀 380 · 📦 4.6K · 📋 570 - 16% open · ⏱️ 25.02.2023):

  ```
  git clone https://github.com/mwouts/jupytext
  ```

- [PyPi](https://pypi.org/project/jupytext) (📥 430K / month · 📦 210 · ⏱️ 11.12.2022):
  ```
  pip install jupytext
  ```
- [Conda](https://anaconda.org/conda-forge/jupytext) (📥 510K · ⏱️ 25.02.2023):
  ```
  conda install -c conda-forge jupytext
  ```
- [npm](https://www.npmjs.com/package/jupyterlab-jupytext) (📥 8.6K / month · 📦 2 · ⏱️ 04.12.2021):
`
	npm install jupyterlab-jupytext
	`
</details>
<details><summary><b><a href="https://github.com/voila-dashboards/voila">Voila</a></b> (🥇34 ·  ⭐ 4.6K) - Voil turns Jupyter notebooks into standalone web applications. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/voila-dashboards/voila) (👨‍💻 64 · 🔀 460 · 📥 500 · 📦 9.4K · 📋 670 - 43% open · ⏱️ 21.02.2023):

  ```
  git clone https://github.com/voila-dashboards/voila
  ```

- [PyPi](https://pypi.org/project/voila) (📥 180K / month · 📦 72 · ⏱️ 28.10.2022):
  ```
  pip install voila
  ```
- [Conda](https://anaconda.org/conda-forge/voila) (📥 250K · ⏱️ 27.10.2022):
  ```
  conda install -c conda-forge voila
  ```
- [npm](https://www.npmjs.com/package/@jupyter-voila/jupyterlab-preview) (📥 1.2K / month · 📦 2 · ⏱️ 19.05.2020):
`
	npm install @jupyter-voila/jupyterlab-preview
	`
</details>
<details><summary><b><a href="https://github.com/executablebooks/jupyter-book">Jupyter Book</a></b> (🥇34 ·  ⭐ 3.3K) - Create beautiful, publication-quality books and documents from.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/executablebooks/jupyter-book) (👨‍💻 120 · 🔀 610 · 📦 8.8K · 📋 1.2K - 42% open · ⏱️ 01.03.2023):

  ```
  git clone https://github.com/executablebooks/jupyter-book
  ```

- [PyPi](https://pypi.org/project/jupyter-book) (📥 100K / month · 📦 100 · ⏱️ 16.08.2022):
  ```
  pip install jupyter-book
  ```
- [Conda](https://anaconda.org/conda-forge/jupyter-book) (📥 59K · ⏱️ 07.02.2023):
`
	conda install -c conda-forge jupyter-book
	`
</details>
<details><summary><b><a href="https://github.com/getnikola/nikola">nikola</a></b> (🥈32 ·  ⭐ 2.4K · 📈) - A static website and blog generator. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/getnikola/nikola) (👨‍💻 230 · 🔀 440 · 📦 470 · 📋 2.1K - 2% open · ⏱️ 01.03.2023):

  ```
  git clone https://github.com/getnikola/nikola
  ```

- [PyPi](https://pypi.org/project/nikola) (📥 1.1K / month · 📦 140 · ⏱️ 01.08.2022):
`
	pip install nikola
	`
</details>
<details><summary><b><a href="https://github.com/airbnb/knowledge-repo">Knowledge Repo</a></b> (🥈29 ·  ⭐ 5.3K) - A next-generation curated knowledge sharing platform for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/airbnb/knowledge-repo) (👨‍💻 73 · 🔀 710 · 📋 290 - 42% open · ⏱️ 01.03.2023):

  ```
  git clone https://github.com/airbnb/knowledge-repo
  ```

- [PyPi](https://pypi.org/project/knowledge-repo) (📥 1.2K / month · 📦 1 · ⏱️ 05.01.2023):
`
	pip install knowledge-repo
	`
</details>
<details><summary><b><a href="https://github.com/jupyter/nbdime">nbdime</a></b> (🥈29 ·  ⭐ 2.4K) - Tools for diffing and merging of Jupyter notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbdime) (👨‍💻 43 · 🔀 140 · 📦 100 · 📋 300 - 24% open · ⏱️ 15.01.2023):

  ```
  git clone https://github.com/jupyter/nbdime
  ```

- [PyPi](https://pypi.org/project/nbdime) (📥 210K / month · 📦 140 · ⏱️ 25.10.2021):
  ```
  pip install nbdime
  ```
- [Conda](https://anaconda.org/conda-forge/nbdime) (📥 780K · ⏱️ 26.10.2021):
  ```
  conda install -c conda-forge nbdime
  ```
- [npm](https://www.npmjs.com/package/nbdime-jupyterlab) (📥 42K / month · ⏱️ 26.10.2021):
`
	npm install nbdime-jupyterlab
	`
</details>
<details><summary><b><a href="https://github.com/damianavila/RISE">RISE</a></b> (🥈28 ·  ⭐ 3.5K) - RISE: Live Reveal.js Jupyter/IPython Slideshow Extension. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/damianavila/RISE) (👨‍💻 44 · 🔀 410 · 📦 2.4K · 📋 440 - 34% open · ⏱️ 16.01.2023):

  ```
  git clone https://github.com/damianavila/RISE
  ```

- [PyPi](https://pypi.org/project/RISE) (📥 7.8K / month · 📦 170 · ⏱️ 03.11.2022):
  ```
  pip install RISE
  ```
- [Conda](https://anaconda.org/conda-forge/rise) (📥 250K · ⏱️ 03.11.2022):
  ```
  conda install -c conda-forge rise
  ```
- [npm](https://www.npmjs.com/package/rise-reveal) (📥 7 / month · ⏱️ 03.07.2019):
`
	npm install rise-reveal
	`
</details>
<details><summary><b><a href="https://github.com/jupyter/nbviewer">nbviewer</a></b> (🥈25 ·  ⭐ 2.1K) - nbconvert as a web service: Render Jupyter Notebooks as static web.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbviewer) (👨‍💻 95 · 🔀 530 · 📦 9 · 📋 580 - 30% open · ⏱️ 27.01.2023):

  ```
  git clone https://github.com/jupyter/nbviewer
  ```

- [Docker Hub](https://hub.docker.com/r/jupyter/nbviewer) (📥 2.8M · ⭐ 30 · ⏱️ 27.01.2023):
`
	docker pull jupyter/nbviewer
	`
</details>
<details><summary><b><a href="https://github.com/stencila/stencila">Stencila</a></b> (🥈25 ·  ⭐ 660) - Author, collaborate on, and publish beautiful interactive documents. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/stencila/stencila) (👨‍💻 35 · 🔀 39 · 📥 3.4K · 📦 19 · 📋 570 - 13% open · ⏱️ 31.01.2023):

  ```
  git clone https://github.com/stencila/stencila
  ```

- [npm](https://www.npmjs.com/package/stencila) (📥 220 / month · 📦 8 · ⏱️ 06.11.2020):
  ```
  npm install stencila
  ```
- [Docker Hub](https://hub.docker.com/r/stencila/cloud) (📥 16K · ⏱️ 08.04.2019):
`
	docker pull stencila/cloud
	`
</details>
<details><summary><b><a href="https://github.com/jupyterhub/binderhub">BinderHub</a></b> (🥉24 ·  ⭐ 2.3K) - Run your code in the cloud, with technology so advanced, it feels.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/binderhub) (👨‍💻 91 · 🔀 360 · 📦 7 · 📋 680 - 31% open · ⏱️ 01.03.2023):

  ```
  git clone https://github.com/jupyterhub/binderhub
  ```

- [PyPi](https://pypi.org/project/binderhub) (📥 28 / month · ⏱️ 07.11.2018):
`
	pip install binderhub
	`
</details>
<details><summary><b><a href="https://github.com/executablebooks/thebe">ThebeLab</a></b> (🥉23 ·  ⭐ 310) - Turn static HTML pages into live documents with Jupyter kernels. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/executablebooks/thebe) (👨‍💻 26 · 🔀 58 · 📦 6 · 📋 170 - 46% open · ⏱️ 21.02.2023):

  ```
  git clone https://github.com/executablebooks/thebe
  ```

- [npm](https://www.npmjs.com/package/thebe) (📥 11K / month · 📦 1 · ⏱️ 21.02.2023):
`
	npm install thebe
	`
</details>
<details><summary><b><a href="https://github.com/nteract/scrapbook">scrapbook</a></b> (🥉23 ·  ⭐ 260 · 💤) - A library for recording and reading data in notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/scrapbook) (👨‍💻 11 · 🔀 27 · 📦 210 · 📋 49 - 48% open · ⏱️ 13.04.2022):

  ```
  git clone https://github.com/nteract/scrapbook
  ```

- [PyPi](https://pypi.org/project/nteract-scrapbook) (📥 64K / month · 📦 17 · ⏱️ 06.01.2021):
  ```
  pip install nteract-scrapbook
  ```
- [Conda](https://anaconda.org/conda-forge/nteract-scrapbook) (📥 13K · ⏱️ 27.02.2021):
  ```
  con
  ```

## Notebook Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries and tools that work with or can be used within notebook files._

<details><summary><b><a href="https://github.com/jupyter/jupyter_client">Jupyter Client</a></b> (🥇34 ·  ⭐ 310) - Jupyter protocol client APIs. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/jupyter_client) (👨‍💻 130 · 🔀 260 · 📥 840 · 📋 360 - 45% open · ⏱️ 24.02.2023):

  ```
  git clone https://github.com/jupyter/jupyter_client
  ```

- [PyPi](https://pypi.org/project/jupyter-client) (📥 20M / month · 📦 2.3K · ⏱️ 30.01.2023):
  ```
  pip install jupyter-client
  ```
- [Conda](https://anaconda.org/conda-forge/jupyter_client) (📥 13M · ⏱️ 16.02.2023):
`
	conda install -c conda-forge jupyter_client
	`
</details>
<details><summary><b><a href="https://github.com/jupyter/nbformat">nbformat</a></b> (🥇34 ·  ⭐ 200) - Reference implementation of the Jupyter Notebook format. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbformat) (👨‍💻 74 · 🔀 140 · 📥 98 · 📦 200K · 📋 130 - 41% open · ⏱️ 01.03.2023):

  ```
  git clone https://github.com/jupyter/nbformat
  ```

- [PyPi](https://pypi.org/project/nbformat) (📥 14M / month · 📦 8.6K · ⏱️ 12.01.2023):
  ```
  pip install nbformat
  ```
- [Conda](https://anaconda.org/conda-forge/nbformat) (📥 13M · ⏱️ 12.01.2023):
  ```
  conda install -c conda-forge nbformat
  ```
- [npm](https://www.npmjs.com/package/nbformat-schema) (📥 90 / month · 📦 2 · ⏱️ 12.01.2023):
`
	npm install nbformat-schema
	`
</details>
<details><summary><b><a href="https://github.com/fastai/nbdev">nbdev</a></b> (🥇31 ·  ⭐ 4.1K) - Create delightful software with Jupyter Notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/fastai/nbdev) (👨‍💻 86 · 🔀 420 · 📋 790 - 11% open · ⏱️ 17.02.2023):

  ```
  git clone https://github.com/fastai/nbdev
  ```

- [PyPi](https://pypi.org/project/nbdev) (📥 55K / month · 📦 120 · ⏱️ 17.06.2022):
`
	pip install nbdev
	`
</details>
<details><summary><b><a href="https://github.com/jupyterhub/repo2docker">repo2docker</a></b> (🥇31 ·  ⭐ 1.4K) - Turn repositories into Jupyter-enabled Docker images. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/repo2docker) (👨‍💻 120 · 🔀 330 · 📦 180 · 📋 520 - 34% open · ⏱️ 21.02.2023):

  ```
  git clone https://github.com/jupyterhub/repo2docker
  ```

- [PyPi](https://pypi.org/project/jupyter-repo2docker) (📥 4.2K / month · 📦 26 · ⏱️ 18.10.2022):
`
	pip install jupyter-repo2docker
	`
</details>
<details><summary><b><a href="https://github.com/jupyter/nbclient">nbclient</a></b> (🥇31 ·  ⭐ 120 · 📉) - A client library for executing notebooks. Formally nbconverts.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbclient) (👨‍💻 34 · 🔀 47 · 📥 200 · 📦 92K · 📋 110 - 38% open · ⏱️ 17.02.2023):

  ```
  git clone https://github.com/jupyter/nbclient
  ```

- [PyPi](https://pypi.org/project/nbclient) (📥 11M / month · 📦 97 · ⏱️ 29.11.2022):
  ```
  pip install nbclient
  ```
- [Conda](https://anaconda.org/conda-forge/nbclient) (📥 7.7M · ⏱️ 30.11.2022):
`
	conda install -c conda-forge nbclient
	`
</details>
<details><summary><b><a href="https://github.com/computationalmodelling/nbval">nbval</a></b> (🥈27 ·  ⭐ 400) - A py.test plugin to validate Jupyter notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/computationalmodelling/nbval) (👨‍💻 33 · 🔀 51 · 📦 2.2K · 📋 110 - 39% open · ⏱️ 11.01.2023):

  ```
  git clone https://github.com/computationalmodelling/nbval
  ```

- [PyPi](https://pypi.org/project/nbval) (📥 130K / month · 📦 290 · ⏱️ 11.01.2023):
  ```
  pip install nbval
  ```
- [Conda](https://anaconda.org/conda-forge/nbval) (📥 300K · ⏱️ 31.07.2020):
`
	conda install -c conda-forge nbval
	`
</details>
<details><summary><b><a href="https://github.com/nbQA-dev/nbQA">nbQA</a></b> (🥈26 ·  ⭐ 700) - Run isort, pyupgrade, mypy, pylint, flake8, and more on Jupyter Notebooks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nbQA-dev/nbQA) (👨‍💻 29 · 🔀 35 · 📋 270 - 1% open · ⏱️ 27.02.2023):

  ```
  git clone https://github.com/nbQA-dev/nbQA
  ```

- [PyPi](https://pypi.org/project/nbqa) (📥 72K / month · 📦 19 · ⏱️ 09.01.2023):
  ```
  pip install nbqa
  ```
- [Conda](https://anaconda.org/conda-forge/nbqa) (📥 80K · ⏱️ 16.02.2023):
`
	conda install -c conda-forge nbqa
	`
</details>
<details><summary><b><a href="https://github.com/jupyter/jupyter-sphinx">Jupyter Sphinx</a></b> (🥉24 ·  ⭐ 160 · 💤) - Sphinx extension for rendering of Jupyter interactive.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/jupyter-sphinx) (👨‍💻 25 · 🔀 56 · 📋 130 - 36% open · ⏱️ 25.06.2022):

  ```
  git clone https://github.com/jupyter/jupyter-sphinx
  ```

- [PyPi](https://pypi.org/project/jupyter_sphinx) (📥 130K / month · 📦 140 · ⏱️ 25.06.2022):
  ```
  pip install jupyter_sphinx
  ```
- [Conda](https://anaconda.org/conda-forge/jupyter_sphinx) (📥 190K · ⏱️ 04.11.2022):
`
	conda install -c conda-forge jupyter_sphinx
	`
</details>
<details><summary><b><a href="https://github.com/fastai/fastpages">fastpages</a></b> (🥉23 ·  ⭐ 3.5K) - An easy to use blogging platform, with enhanced support for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/fastai/fastpages) (👨‍💻 55 · 🔀 800 · 📦 140 · ⏱️ 13.11.2022):

      ```
      git clone https://github.com/fastai/fastpages
      ```

  </details>
  <details><summary><b><a href="https://github.com/chmp/ipytest">ipytest</a></b> (🥉22 ·  ⭐ 250) - Pytest in IPython notebooks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/chmp/ipytest) (👨‍💻 5 · 🔀 19 · 📦 260 · 📋 54 - 5% open · ⏱️ 11.01.2023):

  ```
  git clone https://github.com/chmp/ipytest
  ```

- [PyPi](https://pypi.org/project/ipytest) (📥 13K / month · 📦 15 · ⏱️ 05.11.2022):
`
	pip install ipytest
	`
</details>
<details><summary><b><a href="https://github.com/nteract/testbook">testbook</a></b> (🥉21 ·  ⭐ 340) - Unit test your Jupyter Notebooks the right way. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/testbook) (👨‍💻 15 · 🔀 36 · 📦 200 · 📋 91 - 48% open · ⏱️ 29.11.2022):

  ```
  git clone https://github.com/nteract/testbook
  ```

- [PyPi](https://pypi.org/project/nteract-testbook) (📥 14 / month · ⏱️ 11.08.2020):
  ```
  pip install nteract-testbook
  ```
- [Conda](https://anaconda.org/conda-forge/testbook) (📥 44K · ⏱️ 02.06.2021):
`
	conda install -c conda-forge testbook
	`
</details>
<details><summary><b><a href="https://github.com/jupyter-naas/naas">naas</a></b> (🥉20 ·  ⭐ 230) - Schedule notebooks, run them like APIs, expose securely your assets:.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/jupyter-naas/naas) (👨‍💻 18 · 🔀 22 · 📦 3 · 📋 160 - 21% open · ⏱️ 02.03.2023):

  ```
  git clone https://github.com/jupyter-naas/naas
  ```

- [PyPi](https://pypi.org/project/naas) (📥 1.7K / month · ⏱️ 26.01.2023):
`
	pip install naas
	`
</details>
<details><summary><b><a href="https://github.com/tweag/jupyenv">JupyterWith</a></b> (🥉18 ·  ⭐ 430) - Declarative and reproducible Jupyter environments - powered by Nix. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/tweag/jupyenv) (👨‍💻 33 · 🔀 92 · 📋 160 - 14% open · ⏱️ 15.02.2023):

      ```
      git clone https://github.com/tweag/jupyterWith
      ```

  </details>
  <details><summary><b><a href="https://github.com/ReviewNB/treon">treon</a></b> (🥉18 ·  ⭐ 280 · 💤) - Easy to use test framework for Jupyter Notebooks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ReviewNB/treon) (👨‍💻 5 · 🔀 26 · 📦 66 · 📋 14 - 28% open · ⏱️ 04.08.2022):

  ```
  git clone https://github.com/ReviewNB/treon
  ```

- [PyPi](https://pypi.org/project/treon) (📥 2.7K / month · 📦 6 · ⏱️ 04.08.2022):
  ```
  pip install treon
  ```
- [Conda](https://anaconda.org/conda-forge/treon) (📥 4.1K · ⏱️ 05.08.2022):
`
	conda install -c conda-forge treon
	`
</details>
<details><summary><b><a href="https://github.com/takluyver/nbopen">nbopen</a></b> (🥉16 ·  ⭐ 290) - Open a Jupyter notebook in the best available server. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/takluyver/nbopen) (👨‍💻 11 · 🔀 55 · 📋 63 - 58% open · ⏱️ 15.09.2022):

  ```
  git clone https://github.com/takluyver/nbopen
  ```

- [PyPi](https://pypi.org/project/nbopen) (📥 880 / month · 📦 9 · ⏱️ 25.04.2018):
`
	pip install nbopen
	`
</details>
<details><summary>Show 11 hidden projects...</summary>

- <b><a href="https://github.com/ipython/ipyparallel">ipyparallel</a></b> (🥈29 · ⭐ 2.4K) - IPython Parallel: Interactive Parallel Computing in Python. <code>❗Unlicensed</code>
- <b><a href="https://github.com/twosigma/beakerx">BeakerX</a></b> (🥈27 · ⭐ 2.7K · 💀) - Beaker Extensions for Jupyter Notebook. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/pixiedust/pixiedust">PixieDust</a></b> (🥈27 · ⭐ 1K · 💀) - Python Helper library for Jupyter Notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/mljar/mercury">mercury</a></b> (🥈26 · ⭐ 2.4K) - Build Web Apps in Jupyter Notebook with Python only. <code>❗Unlicensed</code>
- <b><a href="https://github.com/QuantEcon/sphinxcontrib-jupyter">sphinxcontrib.jupyter</a></b> (🥉17 · ⭐ 72 · 💀) - A Sphinx Extension for Generating Jupyter Notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/stas00/ipyexperiments">ipyexperiments</a></b> (🥉15 · ⭐ 160 · 💀) - jupyter/ipython experiment containers for GPU and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/takluyver/jupyter_kernel_mgmt">Kernel Management</a></b> (🥉14 · ⭐ 14 · 💀) - Experimental new kernel management framework for Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/treebeardtech/nbmake-action">nbmake-action</a></b> (🥉12 · ⭐ 150 · 💀) - GitHub Action for testing notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/datitran/jupyter2slides">jupyter2slides</a></b> (🥉10 · ⭐ 780 · 💀) - Cloud Native Presentation Slides with Jupyter Notebook +.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/krassowski/jupyter-helpers">Jupyter Helpers</a></b> (🥉9 · ⭐ 44 · 💀) - A collection of helpers for Jupyter/IPython. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Invictify/Jupter-Notebook-REST-API">Jupter-Notebook-REST-API</a></b> (🥉5 · ⭐ 67 · 💀) - Run your jupyter notebooks as a REST API endpoint... <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## JupyterLab Renderer

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Extensions that can render and display files of specific MIME types._

<details><summary><b><a href="https://github.com/jupyterlab/jupyter-renderers">JupyterLab Renderers</a></b> (🥇22 ·  ⭐ 460) - Renderers and renderer extensions for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyter-renderers) (👨‍💻 29 · 🔀 74 · 📦 3 · 📋 110 - 33% open · ⏱️ 07.02.2023):

  ```
  git clone https://github.com/jupyterlab/jupyter-renderers
  ```

- [PyPi](https://pypi.org/project/jupyterlab-katex) (📥 380 / month · 📦 1 · ⏱️ 17.01.2022):
  ```
  pip install jupyterlab-katex
  ```
- [Conda](https://anaconda.org/conda-forge/jupyterlab-vega3) (📥 2.2K · ⏱️ 18.01.2022):
  ```
  conda install -c conda-forge jupyterlab-vega3
  ```
- [npm](https://www.npmjs.com/package/@jupyterlab/geojson-extension) (📥 1.7K / month · 📦 3 · ⏱️ 15.11.2022):
`
	npm install @jupyterlab/geojson-extension
	`
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-latex">JupyterLab Latex</a></b> (🥈20 ·  ⭐ 540) - JupyterLab extension for live editing of LaTeX documents. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-latex) (👨‍💻 22 · 🔀 65 · 📦 5 · 📋 91 - 39% open · ⏱️ 18.11.2022):

  ```
  git clone https://github.com/jupyterlab/jupyterlab-latex
  ```

- [PyPi](https://pypi.org/project/jupyterlab_latex) (📥 3.3K / month · 📦 2 · ⏱️ 15.09.2021):
  ```
  pip install jupyterlab_latex
  ```
- [Conda](https://anaconda.org/conda-forge/jupyterlab-latex) (📥 8.3K · ⏱️ 15.09.2021):
  ```
  conda install -c conda-forge jupyterlab-latex
  ```
- [npm](https://www.npmjs.com/package/@jupyterlab/latex) (📥 1.1K / month · 📦 2 · ⏱️ 06.07.2021):
`
	npm install @jupyterlab/latex
	`
</details>
<details><summary><b><a href="https://github.com/quigleyj97/jupyterlab-spreadsheet">JupyterLab Spreadsheet</a></b> (🥉16 ·  ⭐ 170 · 💤) - JupyterLab plugin for viewing spreadsheets, such as.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/quigleyj97/jupyterlab-spreadsheet) (👨‍💻 4 · 🔀 14 · 📦 5 · 📋 24 - 25% open · ⏱️ 18.07.2022):

  ```
  git clone https://github.com/quigleyj97/jupyterlab-spreadsheet
  ```

- [npm](https://www.npmjs.com/package/jupyterlab-spreadsheet) (📥 2.5K / month · ⏱️ 17.07.2021):
`
	npm install jupyterlab-spreadsheet
	`
</details>
<details><summary>Show 5 hidden projects...</summary>

- <b><a href="https://github.com/plotly/jupyterlab-dash">JupyterLab Dash</a></b> (🥇22 · ⭐ 860 · 💀) - An Extension for the Interactive development of Dash apps in.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/QuantStack/jupyterlab-drawio">JupyterLab Drawio</a></b> (🥈20 · ⭐ 560 · 💀) - A standalone embedding of the FOSS drawio / mxgraph.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/plotly/jupyterlab-chart-editor">JupyterLab Chart Editor</a></b> (🥉18 · ⭐ 210 · 💀) - JupyterLab extension for Plotlys react-chart-editor. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jupytercalpoly/jupyterlab-tabular-data-editor">jupyterlab-tabular-data-editor</a></b> (🥉15 · ⭐ 120 · 💀) - Manipulate your tabular data responsively and.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/altair-viz/jupyterlab_voyager">JupyterLab Voyager</a></b> (🥉13 · ⭐ 280 · 💀) - JupyterLab extension visualize data with Voyager. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## JupyterLab Themes

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Extensions that can customize the appearance of JupyterLab._

<details><summary><b><a href="https://github.com/telamonian/theme-darcula">Darcula Theme</a></b> (🥇21 ·  ⭐ 170 · 💤) - A handsome Darcula theme for Jupyterlab. The first jlab.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/telamonian/theme-darcula) (👨‍💻 7 · 🔀 35 · 📦 1.2K · 📋 37 - 56% open · ⏱️ 20.07.2022):

  ```
  git clone https://github.com/telamonian/theme-darcula
  ```

- [PyPi](https://pypi.org/project/theme-darcula) (📥 2.5K / month · ⏱️ 20.07.2022):
  ```
  pip install theme-darcula
  ```
- [Conda](https://anaconda.org/conda-forge/theme-darcula) (📥 14K · ⏱️ 20.07.2022):
  ```
  conda install -c conda-forge theme-darcula
  ```
- [npm](https://www.npmjs.com/package/@telamonian/theme-darcula) (📥 750 / month · 📦 2 · ⏱️ 20.07.2022):
`
	npm install @telamonian/theme-darcula
	`
</details>
<details><summary><b><a href="https://github.com/mohirio/jupyterlab-horizon-theme">Horizon Theme</a></b> (🥈16 ·  ⭐ 64) - VSCode Horizon Theme port for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mohirio/jupyterlab-horizon-theme) (👨‍💻 3 · 🔀 5 · 📦 2 · 📋 7 - 14% open · ⏱️ 05.12.2022):

  ```
  git clone https://github.com/mohirio/jupyterlab-horizon-theme
  ```

- [PyPi](https://pypi.org/project/jupyterlab-horizon-theme) (📥 420 / month · ⏱️ 30.11.2022):
  ```
  pip install jupyterlab-horizon-theme
  ```
- [npm](https://www.npmjs.com/package/@mohirio/jupyterlab-horizon-theme) (📥 2.1K / month · 📦 2 · ⏱️ 30.11.2022):
`
	npm install @mohirio/jupyterlab-horizon-theme
	`
</details>
<details><summary><b><a href="https://github.com/oriolmirosa/jupyterlab_materialdarker">Material Darker Theme</a></b> (🥈14 ·  ⭐ 140) - The Material Darker theme for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/oriolmirosa/jupyterlab_materialdarker) (👨‍💻 2 · 🔀 18 · 📦 7 · 📋 20 - 25% open · ⏱️ 16.12.2022):

  ```
  git clone https://github.com/oriolmirosa/jupyterlab_materialdarker
  ```

- [PyPi](https://pypi.org/project/jupyterlab-materialdarker) (📥 650 / month · ⏱️ 16.12.2022):
  ```
  pip install jupyterlab-materialdarker
  ```
- [npm](https://www.npmjs.com/package/@oriolmirosa/jupyterlab_materialdarker) (📥 360 / month · 📦 2 · ⏱️ 16.12.2022):
`
	npm install @oriolmirosa/jupyterlab_materialdarker
	`
</details>
<details><summary><b><a href="https://github.com/yeebc/jupyterlab-neon-theme">Neon Theme</a></b> (🥈14 ·  ⭐ 130 · 💤) - A flat, 80s neon inspired theme for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/yeebc/jupyterlab-neon-theme) (👨‍💻 4 · 🔀 8 · 📦 3 · 📋 13 - 15% open · ⏱️ 28.08.2022):

  ```
  git clone https://github.com/yeebc/jupyterlab-neon-theme
  ```

- [npm](https://www.npmjs.com/package/@yeebc/jupyterlab_neon_theme) (📥 840 / month · ⏱️ 07.03.2021):
`
	npm install @yeebc/jupyterlab_neon_theme
	`
</details>
<details><summary><b><a href="https://github.com/dunovank/jupyterlab_darkside_ui">jupyterlab_darkside_ui</a></b> (🥉12 ·  ⭐ 100) - Darkside ui and syntax theme for jupyterlab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dunovank/jupyterlab_darkside_ui) (👨‍💻 5 · 🔀 7 · 📋 5 - 20% open · ⏱️ 04.10.2022):

  ```
  git clone https://github.com/dunovank/jupyterlab_darkside_ui
  ```

- [PyPi](https://pypi.org/project/jupyterlab_darkside_ui) (📥 370 / month · ⏱️ 18.03.2022):
`
	pip install jupyterlab_darkside_ui
	`
</details>
<details><summary><b><a href="https://github.com/AllanChain/jupyterlab-theme-solarized-dark">jupyterlab-theme-solarized-dark</a></b> (🥉11 ·  ⭐ 74) - JupyterLab 2/3 Solarized Dark extension. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/AllanChain/jupyterlab-theme-solarized-dark) (👨‍💻 2 · 🔀 9 · 📦 2 · 📋 3 - 33% open · ⏱️ 04.02.2023):

  ```
  git clone https://github.com/AllanChain/jupyterlab-theme-solarized-dark
  ```

- [PyPi](https://pypi.org/project/jupyterlab_theme_solarized_dark) (📥 17K / month · ⏱️ 22.06.2022):
  ```
  pip install jupyterlab_theme_solarized_dark
  ```
- [npm](https://www.npmjs.com/package/jupyterlab-theme-solarized-dark) (📥 3.1K / month · ⏱️ 22.06.2022):
`
	npm install jupyterlab-theme-solarized-dark
	`
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/Rahlir/theme-gruvbox">Gruvbox Theme</a></b> (🥉12 · ⭐ 48 · 💀) - Gruvbox dark theme for Jupyter Lab. Modeled on classic.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jtpio/jupyterlab-theme-toggle">Theme Toggle</a></b> (🥉10 · ⭐ 11 · 💀) - JupyterLab extension to toggle the theme in the Top Bar area. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/kenshohara/theme-nord-extension">Nord Theme</a></b> (🥉8 · ⭐ 24 · 💀) - JupyterLab - Nord Theme. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## JupyterLab Extensions

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Application plugins that extend the functionality of JupyterLab itself._

<details><summary><b><a href="https://github.com/elyra-ai/elyra">elyra</a></b> (🥇31 ·  ⭐ 1.5K) - Elyra extends JupyterLab with an AI centric approach. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/elyra-ai/elyra) (👨‍💻 57 · 🔀 280 · 📦 42 · 📋 1.6K - 15% open · ⏱️ 01.03.2023):

  ```
  git clone https://github.com/elyra-ai/elyra
  ```

- [PyPi](https://pypi.org/project/elyra) (📥 3.4K / month · 📦 3 · ⏱️ 26.01.2023):
  ```
  pip install elyra
  ```
- [Conda](https://anaconda.org/conda-forge/elyra) (📥 28K · ⏱️ 21.02.2023):
  ```
  conda install -c conda-forge elyra
  ```
- [npm](https://www.npmjs.com/package/@elyra/services) (📥 1.9K / month · 📦 6 · ⏱️ 21.02.2023):
`
	npm install @elyra/services
	`
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-git">JupyterLab Git</a></b> (🥇31 ·  ⭐ 1.2K) - A Git extension for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-git) (👨‍💻 85 · 🔀 270 · 📦 20 · 📋 560 - 18% open · ⏱️ 15.02.2023):

  ```
  git clone https://github.com/jupyterlab/jupyterlab-git
  ```

- [PyPi](https://pypi.org/project/jupyterlab-git) (📥 99K / month · 📦 20 · ⏱️ 15.12.2022):
  ```
  pip install jupyterlab-git
  ```
- [Conda](https://anaconda.org/conda-forge/jupyterlab-git) (📥 370K · ⏱️ 16.12.2022):
  ```
  conda install -c conda-forge jupyterlab-git
  ```
- [npm](https://www.npmjs.com/package/@jupyterlab/git) (📥 22K / month · 📦 6 · ⏱️ 15.12.2022):
`
	npm install @jupyterlab/git
	`
</details>
<details><summary><b><a href="https://github.com/finos/perspective">Perspective</a></b> (🥇30 ·  ⭐ 5.3K) - A data visualization and analytics component, especially well-.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/finos/perspective) (👨‍💻 80 · 🔀 600 · 📦 8 · 📋 610 - 17% open · ⏱️ 01.03.2023):

  ```
  git clone https://github.com/finos/perspective
  ```

- [PyPi](https://pypi.org/project/perspective-python) (📥 2.7K / month · 📦 10 · ⏱️ 20.01.2023):
  ```
  pip install perspective-python
  ```
- [Conda](https://anaconda.org/conda-forge/perspective) (📥 270K · ⏱️ 27.02.2023):
  ```
  conda install -c conda-forge perspective
  ```
- [npm](https://www.npmjs.com/package/@finos/perspective-jupyterlab) (📥 1.5K / month · 📦 2 · ⏱️ 27.02.2023):
`
	npm install @finos/perspective-jupyterlab
	`
</details>
<details><summary><b><a href="https://github.com/jupyter-lsp/jupyterlab-lsp">JupyterLab LSP</a></b> (🥇30 ·  ⭐ 1.4K) - Coding assistance for JupyterLab (code navigation + hover.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-lsp/jupyterlab-lsp) (👨‍💻 46 · 🔀 120 · 📦 1.4K · 📋 460 - 38% open · ⏱️ 02.01.2023):

  ```
  git clone https://github.com/jupyter-lsp/jupyterlab-lsp
  ```

- [PyPi](https://pypi.org/project/jupyterlab-lsp) (📥 23K / month · 📦 9 · ⏱️ 26.08.2022):
  ```
  pip install jupyterlab-lsp
  ```
- [Conda](https://anaconda.org/conda-forge/jupyter-lsp) (📥 77K · ⏱️ 12.12.2021):
  ```
  conda install -c conda-forge jupyter-lsp
  ```
- [npm](https://www.npmjs.com/package/@krassowski/jupyterlab-lsp) (📥 8.4K / month · 📦 4 · ⏱️ 26.08.2022):
`
	npm install @krassowski/jupyterlab-lsp
	`
</details>
<details><summary><b><a href="https://github.com/dask/dask-labextension">dask-labextension</a></b> (🥈24 ·  ⭐ 280) - JupyterLab extension for Dask. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dask/dask-labextension) (👨‍💻 23 · 🔀 55 · 📦 2 · 📋 140 - 30% open · ⏱️ 19.02.2023):

  ```
  git clone https://github.com/dask/dask-labextension
  ```

- [PyPi](https://pypi.org/project/dask-labextension) (📥 8.4K / month · 📦 6 · ⏱️ 02.11.2022):
  ```
  pip install dask-labextension
  ```
- [Conda](https://anaconda.org/conda-forge/dask-labextension) (📥 840K · ⏱️ 19.02.2023):
  ```
  conda install -c conda-forge dask-labextension
  ```
- [npm](https://www.npmjs.com/package/dask-labextension) (📥 1.7K / month · 📦 2 · ⏱️ 21.06.2022):
`
	npm install dask-labextension
	`
</details>
<details><summary><b><a href="https://github.com/ryantam626/jupyterlab_code_formatter">Code Formatter</a></b> (🥈22 ·  ⭐ 660 · 💤) - A JupyterLab plugin to facilitate invocation of code.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ryantam626/jupyterlab_code_formatter) (👨‍💻 37 · 🔀 50 · 📦 2 · 📋 170 - 17% open · ⏱️ 11.08.2022):

  ```
  git clone https://github.com/ryantam626/jupyterlab_code_formatter
  ```

- [PyPi](https://pypi.org/project/jupyterlab_code_formatter) (📥 44K / month · 📦 8 · ⏱️ 10.08.2022):
  ```
  pip install jupyterlab_code_formatter
  ```
- [Conda](https://anaconda.org/conda-forge/jupyterlab_code_formatter) (📥 610K · ⏱️ 11.08.2022):
  ```
  conda install -c conda-forge jupyterlab_code_formatter
  ```
- [npm](https://www.npmjs.com/package/@ryantam626/jupyterlab_code_formatter) (📥 2.6K / month · 📦 2 · ⏱️ 10.08.2022):
`
	npm install @ryantam626/jupyterlab_code_formatter
	`
</details>
<details><summary><b><a href="https://github.com/finos/jupyterlab_templates">JupyterLab Templates</a></b> (🥈22 ·  ⭐ 320) - Support for jupyter notebook templates in jupyterlab. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/finos/jupyterlab_templates) (👨‍💻 17 · 🔀 59 · 📦 7 · 📋 83 - 6% open · ⏱️ 24.02.2023):

  ```
  git clone https://github.com/jpmorganchase/jupyterlab_templates
  ```

- [PyPi](https://pypi.org/project/jupyterlab_templates) (📥 8K / month · ⏱️ 30.06.2019):
  ```
  pip install jupyterlab_templates
  ```
- [Conda](https://anaconda.org/conda-forge/jupyterlab_templates) (📥 9.8K · ⏱️ 17.11.2022):
  ```
  conda install -c conda-forge jupyterlab_templates
  ```
- [npm](https://www.npmjs.com/package/jupyterlab_templates) (📥 4.5K / month · 📦 2 · ⏱️ 16.11.2022):
`
	npm install jupyterlab_templates
	`
</details>
<details><summary><b><a href="https://github.com/lckr/jupyterlab-variableInspector">Variable Inspector</a></b> (🥈21 ·  ⭐ 960) - Variable Inspector extension for Jupyterlab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/lckr/jupyterlab-variableInspector) (👨‍💻 19 · 🔀 84 · 📦 5 · 📋 160 - 24% open · ⏱️ 10.01.2023):

  ```
  git clone https://github.com/lckr/jupyterlab-variableInspector
  ```

- [PyPi](https://pypi.org/project/lckr-jupyterlab-variableinspector) (📥 9.5K / month · ⏱️ 10.04.2021):
  ```
  pip install lckr-jupyterlab-variableinspector
  ```
- [Conda](https://anaconda.org/conda-forge/jupyterlab-variableinspector) (📥 13K · ⏱️ 10.04.2021):
  ```
  conda install -c conda-forge jupyterlab-variableinspector
  ```
- [npm](https://www.npmjs.com/package/@lckr/jupyterlab_variableinspector) (📥 4.3K / month · ⏱️ 10.04.2021):
`
	npm install @lckr/jupyterlab_variableinspector
	`
</details>
<details><summary><b><a href="https://github.com/rapidsai/jupyterlab-nvdashboard">GPU Dashboards</a></b> (🥈21 ·  ⭐ 490) - A JupyterLab extension for displaying dashboards of GPU usage. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/rapidsai/jupyterlab-nvdashboard) (👨‍💻 18 · 🔀 66 · 📦 2 · 📋 70 - 47% open · ⏱️ 15.02.2023):

  ```
  git clone https://github.com/rapidsai/jupyterlab-nvdashboard
  ```

- [PyPi](https://pypi.org/project/jupyterlab-nvdashboard) (📥 70K / month · 📦 1 · ⏱️ 23.11.2022):
  ```
  pip install jupyterlab-nvdashboard
  ```
- [Conda](https://anaconda.org/conda-forge/jupyterlab-nvdashboard) (📥 29K · ⏱️ 11.05.2022):
  ```
  conda install -c conda-forge jupyterlab-nvdashboard
  ```
- [npm](https://www.npmjs.com/package/jupyterlab-nvdashboard) (📥 870 / month · 📦 2 · ⏱️ 27.04.2021):
`
	npm install jupyterlab-nvdashboard
	`
</details>
<details><summary><b><a href="https://github.com/jupyterlab-contrib/spellchecker">JupyterLab Spellchecker</a></b> (🥈21 ·  ⭐ 170) - Spellchecker for JupyterLab notebook markdown cells.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab-contrib/spellchecker) (👨‍💻 6 · 🔀 17 · 📦 3 · 📋 50 - 30% open · ⏱️ 08.02.2023):

  ```
  git clone https://github.com/jupyterlab-contrib/spellchecker
  ```

- [PyPi](https://pypi.org/project/jupyterlab-spellchecker) (📥 2.8K / month · 📦 1 · ⏱️ 08.10.2021):
  ```
  pip install jupyterlab-spellchecker
  ```
- [Conda](https://anaconda.org/conda-forge/jupyterlab-spellchecker) (📥 65K · ⏱️ 08.10.2021):
  ```
  conda install -c conda-forge jupyterlab-spellchecker
  ```
- [npm](https://www.npmjs.com/package/@ijmbarr/jupyterlab_spellchecker) (📥 2.7K / month · 📦 2 · ⏱️ 08.10.2021):
`
	npm install @ijmbarr/jupyterlab_spellchecker
	`
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-github">JupyterLab GitHub</a></b> (🥈20 ·  ⭐ 350) - GitHub integration for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-github) (👨‍💻 16 · 🔀 98 · 📦 5 · 📋 65 - 43% open · ⏱️ 05.09.2022):

  ```
  git clone https://github.com/jupyterlab/jupyterlab-github
  ```

- [PyPi](https://pypi.org/project/jupyterlab-github) (📥 1.2K / month · 📦 2 · ⏱️ 27.11.2021):
  ```
  pip install jupyterlab-github
  ```
- [npm](https://www.npmjs.com/package/@jupyterlab/github) (📥 6.4K / month · 📦 2 · ⏱️ 27.11.2021):
`
	npm install @jupyterlab/github
	`
</details>
<details><summary><b><a href="https://github.com/bokeh/jupyter_bokeh">Jupyter Bokeh</a></b> (🥈20 ·  ⭐ 210) - An extension for rendering Bokeh content in JupyterLab notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/bokeh/jupyter_bokeh) (👨‍💻 18 · 🔀 42 · 📦 2 · 📋 100 - 21% open · ⏱️ 14.11.2022):

  ```
  git clone https://github.com/bokeh/jupyter_bokeh
  ```

- [PyPi](https://pypi.org/project/jupyter-bokeh) (📥 39K / month · 📦 10 · ⏱️ 20.09.2022):
  ```
  pip install jupyter-bokeh
  ```
- [Conda](https://anaconda.org/conda-forge/jupyter_bokeh) (📥 45K · ⏱️ 20.09.2022):
  ```
  conda install -c conda-forge jupyter_bokeh
  ```
- [npm](https://www.npmjs.com/package/@bokeh/jupyter_bokeh) (📥 13K / month · 📦 2 · ⏱️ 20.09.2022):
`
	npm install @bokeh/jupyter_bokeh
	`
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-google-drive">JupyterLab Google Drive</a></b> (🥈19 ·  ⭐ 380 · 💤) - Cloud storage for JupyterLab using Google Drive. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-google-drive) (👨‍💻 16 · 🔀 79 · 📦 4 · 📋 120 - 43% open · ⏱️ 28.04.2022):

  ```
  git clone https://github.com/jupyterlab/jupyterlab-google-drive
  ```

- [npm](https://www.npmjs.com/package/@jupyterlab/google-drive) (📥 780 / month · 📦 2 · ⏱️ 27.05.2020):
`
	npm install @jupyterlab/google-drive
	`
</details>
<details><summary><b><a href="https://github.com/deshaw/jupyterlab-execute-time">jupyterlab-execute-time</a></b> (🥈19 ·  ⭐ 250) - A JupyterLab extension for displaying cell timings. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/deshaw/jupyterlab-execute-time) (👨‍💻 12 · 🔀 38 · 📦 2 · 📋 42 - 11% open · ⏱️ 28.12.2022):

  ```
  git clone https://github.com/deshaw/jupyterlab-execute-time
  ```

- [PyPi](https://pypi.org/project/jupyterlab-execute-time) (📥 310K / month · ⏱️ 28.12.2022):
  ```
  pip install jupyterlab-execute-time
  ```
- [Conda](https://anaconda.org/conda-forge/jupyterlab_execute_time) (📥 33K · ⏱️ 28.12.2022):
  ```
  conda install -c conda-forge jupyterlab_execute_time
  ```
- [npm](https://www.npmjs.com/package/jupyterlab-execute-time) (📥 2.5K / month · 📦 2 · ⏱️ 18.01.2021):
`
	npm install jupyterlab-execute-time
	`
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/jupyterlab-sidecar">JupyterLab SideCar</a></b> (🥈19 ·  ⭐ 210) - A sidecar output widget for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-widgets/jupyterlab-sidecar) (👨‍💻 14 · 🔀 40 · 📦 6 · 📋 48 - 77% open · ⏱️ 10.12.2022):

  ```
  git clone https://github.com/jupyter-widgets/jupyterlab-sidecar
  ```

- [PyPi](https://pypi.org/project/sidecar) (📥 2.5K / month · 📦 8 · ⏱️ 10.12.2022):
  ```
  pip install sidecar
  ```
- [Conda](https://anaconda.org/conda-forge/sidecar) (📥 15K · ⏱️ 10.12.2022):
  ```
  conda install -c conda-forge sidecar
  ```
- [npm](https://www.npmjs.com/package/@jupyter-widgets/jupyterlab-sidecar) (📥 300 / month · 📦 2 · ⏱️ 05.07.2021):
`
	npm install @jupyter-widgets/jupyterlab-sidecar
	`
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_iframe">JupyterLab IFrame</a></b> (🥈19 ·  ⭐ 88) - View html as an embedded iframe in JupyterLab. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_iframe) (👨‍💻 5 · 🔀 15 · 📦 6 · 📋 68 - 8% open · ⏱️ 23.02.2023):

  ```
  git clone https://github.com/timkpaine/jupyterlab_iframe
  ```

- [PyPi](https://pypi.org/project/jupyterlab_iframe) (📥 770 / month · 📦 8 · ⏱️ 29.06.2019):
  ```
  pip install jupyterlab_iframe
  ```
- [Conda](https://anaconda.org/conda-forge/jupyterlab_iframe) (📥 18K · ⏱️ 12.04.2022):
  ```
  conda install -c conda-forge jupyterlab_iframe
  ```
- [npm](https://www.npmjs.com/package/jupyterlab_iframe) (📥 600 / month · 📦 2 · ⏱️ 11.04.2022):
`
	npm install jupyterlab_iframe
	`
</details>
<details><summary><b><a href="https://github.com/timkpaine/lantern">Lantern</a></b> (🥉17 ·  ⭐ 330) - Data exploration glue. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/lantern) (👨‍💻 3 · 🔀 20 · 📦 18 · 📋 200 - 5% open · ⏱️ 22.11.2022):

  ```
  git clone https://github.com/timkpaine/lantern
  ```

- [PyPi](https://pypi.org/project/pylantern) (📥 87 / month · 📦 1 · ⏱️ 02.02.2020):
`
	pip install pylantern
	`
</details>
<details><summary><b><a href="https://github.com/jpmorganchase/jupyter-fs">jupyter-fs</a></b> (🥉17 ·  ⭐ 140) - A filesystem-like contents manager for multiple backends in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jpmorganchase/jupyter-fs) (👨‍💻 10 · 🔀 26 · 📦 2 · 📋 58 - 24% open · ⏱️ 08.01.2023):

  ```
  git clone https://github.com/jpmorganchase/jupyter-fs
  ```

- [PyPi](https://pypi.org/project/jupyter-fs) (📥 420 / month · ⏱️ 04.06.2021):
  ```
  pip install jupyter-fs
  ```
- [Conda](https://anaconda.org/conda-forge/jupyter-fs) (📥 5.9K · ⏱️ 04.06.2021):
`
	conda install -c conda-forge jupyter-fs
	`
</details>
<details><summary><b><a href="https://github.com/jtpio/ipylab">ipylab</a></b> (🥉17 ·  ⭐ 130) - Control JupyterLab from Python Notebooks with Jupyter Widgets. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jtpio/ipylab) (👨‍💻 6 · 🔀 9 · 📥 48 · 📦 2 · 📋 35 - 45% open · ⏱️ 07.02.2023):

  ```
  git clone https://github.com/jtpio/ipylab
  ```

- [PyPi](https://pypi.org/project/ipylab) (📥 19K / month · 📦 4 · ⏱️ 25.08.2022):
  ```
  pip install ipylab
  ```
- [Conda](https://anaconda.org/conda-forge/ipylab) (📥 18K · ⏱️ 25.08.2022):
  ```
  conda install -c conda-forge ipylab
  ```
- [npm](https://www.npmjs.com/package/ipylab) (📥 210 / month · 📦 2 · ⏱️ 25.08.2022):
`
	npm install ipylab
	`
</details>
<details><summary><b><a href="https://github.com/chaoleili/jupyterlab_tensorboard">JupyterLab Tensorboard</a></b> (🥉16 ·  ⭐ 300 · 💤) - Tensorboard extension for jupyterlab. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/chaoleili/jupyterlab_tensorboard) (👨‍💻 7 · 🔀 33 · 📦 4 · 📋 28 - 64% open · ⏱️ 18.07.2022):

  ```
  git clone https://github.com/chaoleili/jupyterlab_tensorboard
  ```

- [npm](https://www.npmjs.com/package/jupyterlab_tensorboard) (📥 6.9K / month · ⏱️ 27.06.2020):
`
	npm install jupyterlab_tensorboard
	`
</details>
<details><summary><b><a href="https://github.com/jupytercalpoly/jupyterlab-interactive-dashboard-editor">jupyterlab-interactive-dashboard-editor</a></b> (🥉16 ·  ⭐ 200 · 💤) - A drag-and-drop dashboard editor for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupytercalpoly/jupyterlab-interactive-dashboard-editor) (👨‍💻 11 · 🔀 27 · 📦 2 · 📋 44 - 72% open · ⏱️ 13.04.2022):

  ```
  git clone https://github.com/jupytercalpoly/jupyterlab-interactive-dashboard-editor
  ```

- [PyPi](https://pypi.org/project/jupyterlab-interactive-dashboard-editor) (📥 110 / month · ⏱️ 01.04.2021):
  ```
  pip install jupyterlab-interactive-dashboard-editor
  ```
- [Conda](https://anaconda.org/conda-forge/jupyterlab-interactive-dashboard-editor) (📥 1.2K · ⏱️ 13.05.2021):
  ```
  conda install -c conda-forge jupyterlab-interactive-dashboard-editor
  ```
- [npm](https://www.npmjs.com/package/jupyterlab-interactive-dashboard-editor) (📥 45 / month · ⏱️ 27.01.2021):
`
	npm install jupyterlab-interactive-dashboard-editor
	`
</details>
<details><summary><b><a href="https://github.com/microsoft/gather">nbgather</a></b> (🥉15 ·  ⭐ 470) - Spit shine for Jupyter notebooks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/gather) (👨‍💻 13 · 🔀 31 · 📦 2 · 📋 27 - 37% open · ⏱️ 28.11.2022):

  ```
  git clone https://github.com/microsoft/gather
  ```

- [npm](https://www.npmjs.com/package/nbgather) (📥 55 / month · ⏱️ 06.02.2020):
`
	npm install nbgather
	`
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_email">JupyterLab Flake8</a></b> (🥉15 ·  ⭐ 110) - A jupyterlab extension to email notebooks directly from.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_email) (👨‍💻 2 · 🔀 10 · 📋 36 - 11% open · ⏱️ 23.02.2023):

  ```
  git clone https://github.com/timkpaine/jupyterlab_email
  ```

- [PyPi](https://pypi.org/project/jupyterlab-email) (📥 47 / month · ⏱️ 15.03.2022):
  ```
  pip install jupyterlab-email
  ```
- [npm](https://www.npmjs.com/package/jupyterlab-flake8) (📥 210 / month · ⏱️ 16.09.2021):
`
	npm install jupyterlab-flake8
	`
</details>
<details><summary><b><a href="https://github.com/jpmorganchase/nbcelltests">nbcelltests</a></b> (🥉15 ·  ⭐ 68) - Cell-by-cell testing for production Jupyter notebooks in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jpmorganchase/nbcelltests) (👨‍💻 7 · 🔀 15 · 📋 120 - 26% open · ⏱️ 07.12.2022):

  ```
  git clone https://github.com/jpmorganchase/nbcelltests
  ```

- [PyPi](https://pypi.org/project/nbcelltests) (📥 22 / month · ⏱️ 05.10.2020):
  ```
  pip install nbcelltests
  ```
- [Conda](https://anaconda.org/conda-forge/nbcelltests) (📥 6.9K · ⏱️ 05.10.2020):
  ```
  conda install -c conda-forge nbcelltests
  ```
- [npm](https://www.npmjs.com/package/jupyterlab_celltests) (📥 44 / month · ⏱️ 05.10.2020):
`
	npm install jupyterlab_celltests
	`
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_autoversion">JupyterLab Autoversion</a></b> (🥉15 ·  ⭐ 62) - Automatically version jupyter notebooks in JupyterLab. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_autoversion) (👨‍💻 5 · 🔀 9 · 📋 33 - 12% open · ⏱️ 04.02.2023):

  ```
  git clone https://github.com/timkpaine/jupyterlab_autoversion
  ```

- [PyPi](https://pypi.org/project/jupyterlab_autoversion) (📥 59 / month · ⏱️ 29.06.2019):
  ```
  pip install jupyterlab_autoversion
  ```
- [Conda](https://anaconda.org/conda-forge/jupyterlab_autoversion) (📥 12K · ⏱️ 11.04.2022):
  ```
  conda install -c conda-forge jupyterlab_autoversion
  ```
- [npm](https://www.npmjs.com/package/jupyterlab_autoversion) (📥 42 / month · 📦 2 · ⏱️ 11.04.2022):
`
	npm install jupyterlab_autoversion
	`
</details>
<details><summary><b><a href="https://github.com/vatlab/jupyterlab-sos">jupyterlab-sos</a></b> (🥉15 ·  ⭐ 60) - Jupyterlab extension for SoS Polyglot Notebook and Workflow.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/vatlab/jupyterlab-sos) (👨‍💻 4 · 🔀 3 · 📦 2 · 📋 59 - 13% open · ⏱️ 06.12.2022):

  ```
  git clone https://github.com/vatlab/jupyterlab-sos
  ```

- [PyPi](https://pypi.org/project/jupyterlab-sos) (📥 130 / month · ⏱️ 06.12.2022):
  ```
  pip install jupyterlab-sos
  ```
- [Conda](https://anaconda.org/conda-forge/jupyterlab-sos) (📥 24K · ⏱️ 07.12.2022):
  ```
  conda install -c conda-forge jupyterlab-sos
  ```
- [npm](https://www.npmjs.com/package/jupyterlab-sos) (📥 160 / month · 📦 2 · ⏱️ 14.01.2021):
`
	npm install jupyterlab-sos
	`
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_commands">jupyterlab_commands</a></b> (🥉15 ·  ⭐ 43) - Add arbitrary python commands to the jupyterlab.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_commands) (👨‍💻 2 · 🔀 5 · 📦 6 · 📋 24 - 8% open · ⏱️ 23.02.2023):

  ```
  git clone https://github.com/timkpaine/jupyterlab_commands
  ```

- [PyPi](https://pypi.org/project/jupyterlab-commands) (📥 73 / month · ⏱️ 11.04.2022):
  ```
  pip install jupyterlab-commands
  ```
- [Conda](https://anaconda.org/conda-forge/jupyterlab_commands) (📥 8.8K · ⏱️ 11.04.2022):
`
	conda install -c conda-forge jupyterlab_commands
	`
</details>
<details><summary><b><a href="https://github.com/itsjafer/jupyterlab-sparkmonitor">jupyterlab-sparkmonitor</a></b> (🥉14 ·  ⭐ 91 · 💤) - JupyterLab extension that enables monitoring launched.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/itsjafer/jupyterlab-sparkmonitor) (👨‍💻 10 · 🔀 20 · 📋 16 - 50% open · ⏱️ 01.04.2022):

  ```
  git clone https://github.com/itsjafer/jupyterlab-sparkmonitor
  ```

- [PyPi](https://pypi.org/project/jupyterlab-sparkmonitor) (📥 6.8K / month · ⏱️ 04.08.2021):
  ```
  pip install jupyterlab-sparkmonitor
  ```
- [npm](https://www.npmjs.com/package/jupyterlab_sparkmonitor) (📥 110 / month · ⏱️ 29.07.2020):
  ```
  npm install jupyterlab_sparkmonitor
  ```
- [Docker Hub](https://hub.docker.com/r/itsjafer/sparkmonitor) (📥 320 · ⏱️ 02.06.2021):
`
	docker pull itsjafer/sparkmonitor
	`
</details>
<details><summary><b><a href="https://github.com/timkpaine/knowledgelab">KnowledgeLab</a></b> (🥉14 ·  ⭐ 46) - KnowledgeRepo + JupyterLab. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/knowledgelab) (👨‍💻 3 · 🔀 6 · 📦 5 · 📋 29 - 17% open · ⏱️ 10.12.2022):

  ```
  git clone https://github.com/timkpaine/knowledgelab
  ```

- [PyPi](https://pypi.org/project/knowledgelab) (📥 15 / month · ⏱️ 19.10.2017):
  ```
  pip install knowledgelab
  ```
- [npm](https://www.npmjs.com/package/knowledgelab) (📥 13 / month · ⏱️ 16.10.2018):
`
	npm install knowledgelab
	`
</details>
<details><summary><b><a href="https://github.com/xiaohk/stickyland">StickyLand</a></b> (🥉13 ·  ⭐ 280 · 💤) - Break the linear presentation of Jupyter Notebooks with sticky.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/xiaohk/stickyland) (👨‍💻 2 · 🔀 16 · 📥 14 · 📦 3 · 📋 9 - 11% open · ⏱️ 30.05.2022):

  ```
  git clone https://github.com/xiaohk/stickyland
  ```

- [PyPi](https://pypi.org/project/jupyterlab-stickyland) (📥 260 / month · 📦 1 · ⏱️ 30.05.2022):
  ```
  pip install jupyterlab-stickyland
  ```
- [npm](https://www.npmjs.com/package/jupyterlab-stickyland) (📥 27 / month · ⏱️ 23.11.2021):
`
	npm install jupyterlab-stickyland
	`
</details>
<details><summary><b><a href="https://github.com/jupyterlab-contrib/jupyterlab-kernelspy">JupyterLab Kernelspy</a></b> (🥉13 ·  ⭐ 69) - A Jupyter Lab extension for inspecting messages to/from.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab-contrib/jupyterlab-kernelspy) (👨‍💻 4 · 🔀 9 · 📦 6 · 📋 13 - 15% open · ⏱️ 03.02.2023):

  ```
  git clone https://github.com/jupyterlab-contrib/jupyterlab-kernelspy
  ```

- [PyPi](https://pypi.org/project/jupyterlab-kernelspy) (📥 140 / month · ⏱️ 19.04.2022):
  ```
  pip install jupyterlab-kernelspy
  ```
- [Conda](https://anaconda.org/conda-forge/jupyterlab-kernelspy) (📥 7.4K · ⏱️ 19.04.2022):
  ```
  conda install -c conda-forge jupyterlab-kernelspy
  ```
- [npm](https://www.npmjs.com/package/jupyterlab-kernelspy) (📥 300 / month · ⏱️ 19.04.2022):
`
	npm install jupyterlab-kernelspy
	`
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_email">JupyterLab Email</a></b> (🥉13 ·  ⭐ 52) - A jupyterlab extension to email notebooks directly from.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_email) (👨‍💻 2 · 🔀 2 · 📋 36 - 11% open · ⏱️ 23.02.2023):

  ```
  git clone https://github.com/timkpaine/jupyterlab_email
  ```

- [PyPi](https://pypi.org/project/jupyterlab_email) (📥 47 / month · ⏱️ 30.06.2019):
  ```
  pip install jupyterlab_email
  ```
- [npm](https://www.npmjs.com/package/jupyterlab_email) (📥 50 / month · 📦 2 · ⏱️ 15.03.2022):
`
	npm install jupyterlab_email
	`
</details>
<details><summary><b><a href="https://github.com/ReviewNB/jupyterlab-gitplus">jupyterlab-gitplus</a></b> (🥉12 ·  ⭐ 99) - JupyterLab extension to create GitHub commits & pull.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/ReviewNB/jupyterlab-gitplus) (👨‍💻 2 · 🔀 8 · 📦 2 · 📋 19 - 57% open · ⏱️ 28.02.2023):

  ```
  git clone https://github.com/ReviewNB/jupyterlab-gitplus
  ```

- [PyPi](https://pypi.org/project/jupyterlab_gitplus) (📥 340 / month · ⏱️ 11.07.2021):
  ```
  pip install jupyterlab_gitplus
  ```
- [npm](https://www.npmjs.com/package/@reviewnb/jupyterlab_gitplus) (📥 110 / month · 📦 2 · ⏱️ 28.02.2023):
`
	npm install @reviewnb/jupyterlab_gitplus
	`
</details>
<details><summary>Show 19 hidden projects...</summary>

- <b><a href="https://github.com/jupyterlab/debugger">JupyterLab Debugger</a></b> (🥇28 · ⭐ 13K · 💀) - A visual debugger for Jupyter notebooks, consoles,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jupyterlab/jupyterlab-toc">JupyterLab TOC</a></b> (🥇28 · ⭐ 13K · 💀) - Table of Contents extension for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jtpio/jupyterlab-system-monitor">JupyterLab System Monitor</a></b> (🥈20 · ⭐ 280 · 💀) - JupyterLab extension to display system metrics. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jupyterlab/jupyterlab-data-explorer">JupyterLab Data Explorer</a></b> (🥈18 · ⭐ 170 · 💀) - First class datasets in JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jupyterlab/jupyterlab-hdf5">JupyterLab HDF5</a></b> (🥈18 · ⭐ 100 · 💀) - Open and explore HDF5 files in JupyterLab. Can handle very.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jwkvam/jupyterlab-vim">JupyterLab Vim</a></b> (🥉17 · ⭐ 940 · 💀) - Vim notebook cell bindings for JupyterLab. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/aquirdTurtle/Collapsible_Headings">Collapsible Headings</a></b> (🥉17 · ⭐ 170 · 💀) - Implements Collapsible Headers for Jupyter Lab.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/pbugnion/jupyterlab-sql">JupyterLab SQL</a></b> (🥉16 · ⭐ 390 · 💀) - SQL GUI for JupyterLab. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/mlshapiro/jupyterlab-flake8">jupyterlab-flake8</a></b> (🥉16 · ⭐ 110 · 💀) - Jupyterlab python linter for notebooks and text files.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/krassowski/jupyterlab-go-to-definition">JupyterLab Go-To-Definition</a></b> (🥉15 · ⭐ 210 · 💀) - Navigate to variables definition with a click in.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jupyterlab/jupyterlab-commenting">JupyterLab Commenting</a></b> (🥉15 · ⭐ 95 · 💀) - Commenting and annotation for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jtpio/jupyterlab-topbar">JupyterLab Top Bar</a></b> (🥉14 · ⭐ 95 · 💀) - JupyterLab Top Bar extension. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jupyterlab/jupyterlab-shortcutui">JupyterLab Shortcutui</a></b> (🥉14 · ⭐ 56 · 💀) - A JupyterLab extension for managing keyboard shortcuts. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/parente/jupyterlab-quickopen">JupyterLab Quickopen</a></b> (🥉13 · ⭐ 74 · 💀) - Quickly open a file in JupyterLab by typing part of.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jtpio/jupyterlab-python-file">JupyterLab Python Files</a></b> (🥉11 · ⭐ 53 · 💀) - JupyterLab extension to create Python files. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jupyterlab/jupyterlab-celltags">jupyterlab-celltags</a></b> (🥉10 · ⭐ 110 · 💀) - A JupyterLab extension for notebook cell tags. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jtpio/jupyterlab-python-bytecode">JupyterLab Bytecode</a></b> (🥉10 · ⭐ 60 · 💀) - JupyterLab extension to explore CPython Bytecode. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/manuzhang/jupyterlab_spark">JupyterLab Spark</a></b> (🥉8 · ⭐ 9 · 💀) - Spark Application UI extension for JupyterLab. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/gavincyi/jupyterlab-executor">jupyterlab-executor</a></b> (🥉8 · ⭐ 6 · 💀) - JupyterLab extension to execute the scripts from the.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## JupyterHub Authenticators

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Authentication modules that manage and control how users can access the JupyterHub deployment._

<details><summary><b><a href="https://github.com/jupyterhub/oauthenticator">OAuthenticator</a></b> (🥇30 ·  ⭐ 360) - OAuth + JupyterHub Authenticator = OAuthenticator. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/oauthenticator) (👨‍💻 110 · 🔀 340 · 📦 330 · 📋 250 - 17% open · ⏱️ 07.02.2023):

  ```
  git clone https://github.com/jupyterhub/oauthenticator
  ```

- [PyPi](https://pypi.org/project/oauthenticator) (📥 24K / month · 📦 44 · ⏱️ 08.09.2022):
  ```
  pip install oauthenticator
  ```
- [Conda](https://anaconda.org/conda-forge/oauthenticator) (📥 33K · ⏱️ 08.09.2022):
`
	conda install -c conda-forge oauthenticator
	`
</details>
<details><summary><b><a href="https://github.com/jupyterhub/ltiauthenticator">LTI Authenticator</a></b> (🥈22 ·  ⭐ 58) - A JupyterHub authenticator for LTI. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/ltiauthenticator) (👨‍💻 15 · 🔀 47 · 📦 88 · 📋 41 - 12% open · ⏱️ 01.03.2023):

  ```
  git clone https://github.com/jupyterhub/ltiauthenticator
  ```

- [PyPi](https://pypi.org/project/jupyterhub-ltiauthenticator) (📥 2.1K / month · 📦 9 · ⏱️ 15.11.2021):
`
	pip install jupyterhub-ltiauthenticator
	`
</details>
<details><summary><b><a href="https://github.com/jupyterhub/nativeauthenticator">Native Authenticator</a></b> (🥈21 ·  ⭐ 60) - JupyterHub-native User Authenticator https://native-.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/nativeauthenticator) (👨‍💻 21 · 🔀 61 · 📦 49 · 📋 99 - 29% open · ⏱️ 07.02.2023):

  ```
  git clone https://github.com/jupyterhub/nativeauthenticator
  ```

- [PyPi](https://pypi.org/project/jupyterhub-nativeauthenticator) (📥 6.5K / month · ⏱️ 09.09.2022):
`
	pip install jupyterhub-nativeauthenticator
	`
</details>
<details><summary><b><a href="https://github.com/HewlettPackard/jupyterhub-samlauthenticator">SAML Authenticator</a></b> (🥈14 ·  ⭐ 34 · 💤) - jupyterhub-samlauthenticator. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/HewlettPackard/jupyterhub-samlauthenticator) (👨‍💻 7 · 🔀 21 · 📥 13 · 📋 30 - 53% open · ⏱️ 21.03.2022):

  ```
  git clone https://github.com/HewlettPackard/jupyterhub-samlauthenticator
  ```

- [PyPi](https://pypi.org/project/jupyterhub-samlauthenticator) (📥 360 / month · ⏱️ 13.07.2020):
`
	pip install jupyterhub-samlauthenticator
	`
</details>
<details><summary>Show 11 hidden projects...</summary>

- <b><a href="https://github.com/jupyterhub/ldapauthenticator">LDAP Authenticator</a></b> (🥇23 · ⭐ 180 · 💀) - LDAP Authenticator Plugin for Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jupyterhub/firstuseauthenticator">First Use Authenticator</a></b> (🥈17 · ⭐ 45 · 💀) - JupyterHub Authenticator that lets users set.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/mogthesprog/jwtauthenticator">JWT Authenticator</a></b> (🥉13 · ⭐ 46 · 💀) - A Token Authenticator for JupyterHub. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/jupyterhub/dummyauthenticator">dummyauthenticator</a></b> (🥉13 · ⭐ 28 · 💀) - A Dummy JupyterHub Authenticator to make testing easy. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jupyterhub/nullauthenticator">Null Authenticator</a></b> (🥉13 · ⭐ 8 · 💤) - Null Authenticator for JupyterHub instances that should.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/cwaldbieser/jhub_remote_user_authenticator">Remote User Auth</a></b> (🥉12 · ⭐ 37 · 💀) - REMOTE_USER authenticator for Jupyterhub. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/cwaldbieser/jhub_cas_authenticator">CAS Authenticator</a></b> (🥉11 · ⭐ 21 · 💤) - CAS authenticator for Jupyterhub. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/thedataincubator/jupyterhub-hashauthenticator">Hash Authenticator</a></b> (🥉11 · ⭐ 4) - Authenticate users with passwords generated from their.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/ucphhpc/jhub-authenticators">Remote Authenticator</a></b> (🥉9 · ⭐ 1) - A collection of JupyterHub Authenticators, including.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/jupyterhub/kerberosauthenticator">Keberos Authenticator</a></b> (🥉8 · ⭐ 10 · 💀) - A JupyterHub authenticator using Kerberos. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/andreas-h/sshauthenticator">SSH Authenticator</a></b> (🥉4 · ⭐ 6 · 💀) - A simple SSH authenticator for JupyterHub. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## JupyterHub Spawners

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Spawner modules that start, monitor, and stop single-user notebook servers._

<details><summary><b><a href="https://github.com/jupyterhub/kubespawner">KubeSpawner</a></b> (🥇30 ·  ⭐ 450) - Kubernetes spawner for JupyterHub. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/kubespawner) (👨‍💻 78 · 🔀 280 · 📦 130 · 📋 320 - 21% open · ⏱️ 07.02.2023):

  ```
  git clone https://github.com/jupyterhub/kubespawner
  ```

- [PyPi](https://pypi.org/project/jupyterhub-kubespawner) (📥 61K / month · 📦 14 · ⏱️ 03.11.2022):
  ```
  pip install jupyterhub-kubespawner
  ```
- [Conda](https://anaconda.org/conda-forge/jupyterhub-kubespawner) (📥 12K · ⏱️ 13.09.2022):
`
	conda install -c conda-forge jupyterhub-kubespawner
	`
</details>
<details><summary><b><a href="https://github.com/jupyterhub/dockerspawner">DockerSpawner</a></b> (🥈26 ·  ⭐ 440) - Spawns JupyterHub single user servers in Docker containers. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/dockerspawner) (👨‍💻 66 · 🔀 300 · 📦 150 · 📋 260 - 8% open · ⏱️ 27.02.2023):

  ```
  git clone https://github.com/jupyterhub/dockerspawner
  ```

- [PyPi](https://pypi.org/project/dockerspawner) (📥 38K / month · 📦 26 · ⏱️ 22.07.2021):
  ```
  pip install dockerspawner
  ```
- [Conda](https://anaconda.org/conda-forge/dockerspawner) (📥 16K · ⏱️ 17.08.2021):
`
	conda install -c conda-forge dockerspawner
	`
</details>
<details><summary><b><a href="https://github.com/jupyterhub/batchspawner">BatchSpawner</a></b> (🥈23 ·  ⭐ 150 · 📈) - Custom Spawner for Jupyterhub to start servers in batch.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/batchspawner) (👨‍💻 42 · 🔀 120 · 📦 25 · 📋 140 - 46% open · ⏱️ 01.03.2023):

  ```
  git clone https://github.com/jupyterhub/batchspawner
  ```

- [PyPi](https://pypi.org/project/batchspawner) (📥 4.2K / month · 📦 4 · ⏱️ 05.10.2022):
`
	pip install batchspawner
	`
</details>
<details><summary><b><a href="https://github.com/jupyterhub/systemdspawner">SystemdSpawner</a></b> (🥉20 ·  ⭐ 86) - Spawn JupyterHub single-user notebook servers with systemd. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/systemdspawner) (👨‍💻 18 · 🔀 44 · 📦 21 · 📋 70 - 54% open · ⏱️ 11.01.2023):

  ```
  git clone https://github.com/jupyterhub/systemdspawner
  ```

- [PyPi](https://pypi.org/project/jupyterhub-systemdspawner) (📥 3.1K / month · 📦 1 · ⏱️ 11.01.2023):
  ```
  pip install jupyterhub-systemdspawner
  ```
- [Conda](https://anaconda.org/conda-forge/jupyterhub-systemdspawner) (📥 24K · ⏱️ 10.11.2022):
`
	conda install -c conda-forge jupyterhub-systemdspawner
	`
</details>
<details><summary><b><a href="https://github.com/jupyterhub/wrapspawner">WrapSpawner</a></b> (🥉13 ·  ⭐ 56 · 💤) - Mechanism for runtime configuration of spawners for JupyterHub. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/wrapspawner) (👨‍💻 16 · 🔀 51 · 📦 9 · 📋 32 - 56% open · ⏱️ 04.03.2022):

      ```
      git clone https://github.com/jupyterhub/wrapspawner
      ```

  </details>
  <details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/jupyterhub/sudospawner">SudoSpawner</a></b> (🥉16 · ⭐ 45 · 💀) - Spawn JupyterHub single-user servers with sudo. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/uktrade/fargatespawner">FargateSpawner</a></b> (🥉14 · ⭐ 37 · 💀) - Spawns JupyterHub single user servers in Docker containers.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/jupyterhub/yarnspawner">YarnSpawner</a></b> (🥉10 · ⭐ 19 · 💀) - Spawn JupyterHub single user notebook servers in Hadoop/YARN.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## Jupyter Components

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Core components of the Jupyter architecture._

<details><summary><b><a href="https://github.com/ipython/ipython">ipython</a></b> (🥇47 ·  ⭐ 16K) - Official repository for IPython itself. Other repos in the IPython.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/ipython/ipython) (👨‍💻 940 · 🔀 4.4K · 📥 320K · 📦 370K · 📋 7.1K - 22% open · ⏱️ 28.02.2023):

  ```
  git clone https://github.com/ipython/ipython
  ```

- [PyPi](https://pypi.org/project/ipython) (📥 21M / month · 📦 36K · ⏱️ 10.02.2023):
  ```
  pip install ipython
  ```
- [Conda](https://anaconda.org/conda-forge/ipython) (📥 17M · ⏱️ 28.02.2023):
`
	conda install -c conda-forge ipython
	`
</details>
<details><summary><b><a href="https://github.com/jupyter-server/jupyter_server">jupyter_server</a></b> (🥉36 ·  ⭐ 380) - The backendi.e. core services, APIs, and REST endpointsto.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-server/jupyter_server) (👨‍💻 500 · 🔀 210 · 📥 1.2K · 📋 390 - 34% open · ⏱️ 24.02.2023):

  ```
  git clone https://github.com/jupyter-server/jupyter_server
  ```

- [PyPi](https://pypi.org/project/jupyter_server) (📥 13M / month · 📦 260 · ⏱️ 19.09.2022):
  ```
  pip install jupyter_server
  ```
- [Conda](https://anaconda.org/conda-forge/jupyter_server) (📥 4M · ⏱️ 15.02.2023):
`
	conda install -c conda-forge jupyter_server
	`
</details>
<details><summary><b><a href="https://github.com/jupyter/jupyter-packaging">jupyter-packaging</a></b> (🥉24 ·  ⭐ 60) - Tools to help build and install Jupyter Python packages. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/jupyter-packaging) (👨‍💻 30 · 🔀 50 · 📥 49 · 📋 41 - 26% open · ⏱️ 07.02.2023):

  ```
  git clone https://github.com/jupyter/jupyter-packaging
  ```

- [PyPi](https://pypi.org/project/jupyter-packaging) (📥 380K / month · 📦 52 · ⏱️ 25.08.2022):
  ```
  pip install jupyter-packaging
  ```
- [Conda](https://anaconda.org/conda-forge/jupyter-packaging) (📥 440K · ⏱️ 25.08.2022):
`
	conda install -c conda-forge jupyter-packaging
	`
</details>
<br>

## Others

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/jupyter/qtconsole">qtconsole</a></b> (🥇36 ·  ⭐ 350 · 📈) - Jupyter Qt Console. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/qtconsole) (👨‍💻 120 · 🔀 190 · 📦 130K · 📋 320 - 32% open · ⏱️ 02.11.2022):

  ```
  git clone https://github.com/jupyter/qtconsole
  ```

- [PyPi](https://pypi.org/project/qtconsole) (📥 3.3M / month · 📦 6.3K · ⏱️ 02.11.2022):
  ```
  pip install qtconsole
  ```
- [Conda](https://anaconda.org/conda-forge/qtconsole) (📥 3.6M · ⏱️ 02.11.2022):
`
	conda install -c conda-forge qtconsole
	`
</details>
<details><summary><b><a href="https://github.com/jupyter/jupyter_console">jupyter-console</a></b> (🥈29 ·  ⭐ 220) - Jupyter Terminal Console. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/jupyter_console) (👨‍💻 60 · 🔀 150 · 📥 150 · 📋 150 - 40% open · ⏱️ 27.02.2023):

  ```
  git clone https://github.com/jupyter/jupyter_console
  ```

- [PyPi](https://pypi.org/project/jupyter-console) (📥 3.9M / month · 📦 99 · ⏱️ 22.06.2022):
  ```
  pip install jupyter-console
  ```
- [Conda](https://anaconda.org/conda-forge/jupyter_console) (📥 3.2M · ⏱️ 28.02.2023):
`
	conda install -c conda-forge jupyter_console
	`
</details>
<details><summary><b><a href="https://github.com/datapane/datapane">datapane</a></b> (🥉24 ·  ⭐ 790) - Build full-stack data analytics apps in Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/datapane/datapane) (👨‍💻 16 · 🔀 64 · 📋 100 - 5% open · ⏱️ 01.03.2023):

  ```
  git clone https://github.com/datapane/datapane
  ```

- [PyPi](https://pypi.org/project/datapane) (📥 40K / month · 📦 11 · ⏱️ 09.04.2022):
  ```
  pip install datapane
  ```
- [Conda](https://anaconda.org/conda-forge/datapane) (📥 54K · ⏱️ 28.02.2023):
`
	conda install -c conda-forge datapane
	`
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/abhishekkrthakur/colabcode">colabcode</a></b> (🥉21 · ⭐ 1.9K · 💀) - Run VSCode (codeserver) on Google Colab or Kaggle Notebooks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>

---

## Related Resources

- [**Best-of lists**](https://best-of.org): Discover other best-of lists with awesome open-source projects on all kinds of topics.
- [**best-of-ml-python**](https://github.com/ml-tooling/best-of-ml-python): A ranked list of awesome machine learning python libraries.
- [**awesome-jupyter**](https://github.com/markusschanta/awesome-jupyter): A curated list of awesome Jupyter projects, libraries and resources.
- [**awesome-jupyterlab**](https://github.com/mauhai/awesome-jupyterlab): A curated list of awesome JupyterLab extensions and resources.

## Contribution

Contributions are encouraged and always welcome! If you like to add or update projects, choose one of the following ways:

- Open an issue by selecting one of the provided categories from the [issue page](https://github.com/ml-tooling/best-of-jupyter/issues/new/choose) and fill in the requested information.
- Modify the [projects.yaml](https://github.com/ml-tooling/best-of-jupyter/blob/main/projects.yaml) with your additions or changes, and submit a pull request. This can also be done directly via the [Github UI](https://github.com/ml-tooling/best-of-jupyter/edit/main/projects.yaml).

If you like to contribute to or share suggestions regarding the project metadata collection or markdown generation, please refer to the [best-of-generator](https://github.com/best-of-lists/best-of-generator) repository. If you like to create your own best-of list, we recommend to follow [this guide](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

For more information on how to add or update projects, please read the [contribution guidelines](https://github.com/ml-tooling/best-of-jupyter/blob/main/CONTRIBUTING.md). By participating in this project, you agree to abide by its [Code of Conduct](https://github.com/ml-tooling/best-of-jupyter/blob/main/.github/CODE_OF_CONDUCT.md).

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](https://creativecommons.org/licenses/by-sa/4.0/)da install -c conda-forge nteract-scrapbook

```

</details>
<details><summary><b><a href="https://github.com/danielfrg/mkdocs-jupyter">mkdocs-jupyter</a></b> (🥉23 ·  ⭐ 200) - Use Jupyter Notebook in mkdocs. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/danielfrg/mkdocs-jupyter) (👨‍💻 14 · 🔀 34 · 📦 1K · 📋 80 - 41% open · ⏱️ 07.12.2022):

```

git clone https://github.com/danielfrg/mkdocs-jupyter

```

- [PyPi](https://pypi.org/project/mkdocs-jupyter) (📥 34K / month · 📦 19 · ⏱️ 23.09.2022):
```

pip install mkdocs-jupyter

```
- [Conda](https://anaconda.org/conda-forge/mkdocs-jupyter) (📥 31K · ⏱️ 24.09.2022):
`
	conda install -c conda-forge mkdocs-jupyter
	`
</details>
<details><summary><b><a href="https://github.com/nteract/commuter">commuter</a></b> (🥉22 ·  ⭐ 6K · 💤) - Notebook sharing hub. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/commuter) (👨‍💻 27 · 🔀 570 · 📦 5 · 📋 91 - 57% open · ⏱️ 28.04.2022):

```

git clone https://github.com/nteract/commuter

```

- [npm](https://www.npmjs.com/package/@nteract/commuter) (📥 190 / month · 📦 2 · ⏱️ 27.10.2020):
`
	npm install @nteract/commuter
	`
</details>
<details><summary><b><a href="https://github.com/greenape/mknotebooks">mknotebooks</a></b> (🥉21 ·  ⭐ 110) - A plugin for mkdocs to help you include Jupyter notebooks in your.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/greenape/mknotebooks) (👨‍💻 13 · 🔀 20 · 📦 360 · 📋 61 - 59% open · ⏱️ 20.12.2022):

```

git clone https://github.com/greenape/mknotebooks

```

- [PyPi](https://pypi.org/project/mknotebooks) (📥 21K / month · 📦 26 · ⏱️ 20.12.2022):
`
	pip install mknotebooks
	`
</details>
<details><summary><b><a href="https://github.com/danielfrg/jupyter-flex">jupyter-flex</a></b> (🥉20 ·  ⭐ 280) - Build dashboards using Jupyter Notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/danielfrg/jupyter-flex) (👨‍💻 4 · 🔀 53 · 📦 39 · 📋 57 - 19% open · ⏱️ 16.11.2022):

```

git clone https://github.com/danielfrg/jupyter-flex

```

- [PyPi](https://pypi.org/project/jupyter-flex) (📥 1.1K / month · ⏱️ 29.09.2021):
```

pip install jupyter-flex

```
- [Conda](https://anaconda.org/conda-forge/jupyter-flex) (📥 12K · ⏱️ 01.10.2021):
```

conda install -c conda-forge jupyter-flex

```
- [npm](https://www.npmjs.com/package/@danielfrg/jupyter-flex) (📥 51 / month · ⏱️ 02.10.2021):
`
	npm install @danielfrg/jupyter-flex
	`
</details>
<details><summary><b><a href="https://github.com/nbgallery/nbgallery">nbgallery</a></b> (🥉19 ·  ⭐ 150) - Enterprise Jupyter notebook sharing and collaboration app. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nbgallery/nbgallery) (👨‍💻 20 · 🔀 25 · 📋 430 - 11% open · ⏱️ 01.03.2023):

```

git clone https://github.com/nbgallery/nbgallery

```

- [Docker Hub](https://hub.docker.com/r/nbgallery/nbgallery) (📥 170K · ⭐ 3 · ⏱️ 01.03.2023):
`
	docker pull nbgallery/nbgallery
	`
</details>
<details><summary><b><a href="https://github.com/ideonate/cdsdashboards">cdsdashboards</a></b> (🥉17 ·  ⭐ 180) - JupyterHub extension for ContainDS Dashboards. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/ideonate/cdsdashboards) (👨‍💻 14 · 🔀 37 · 📋 92 - 35% open · ⏱️ 12.09.2022):

```

git clone https://github.com/ideonate/cdsdashboards

```

- [PyPi](https://pypi.org/project/cdsdashboards) (📥 880 / month · ⏱️ 19.09.2022):
```

pip install cdsdashboards

````
- [Conda](https://anaconda.org/conda-forge/cdsdashboards) (📥 41K · ⏱️ 12.09.2022):
`
	conda install -c conda-forge cdsdashboards
	`
</details>
<details><summary>Show 5 hidden projects...</summary>

- <b><a href="https://github.com/aaren/notedown">notedown</a></b> (🥉21 · ⭐ 840 · 💀) - Markdown = IPython Notebook. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code>
- <b><a href="https://github.com/SamLau95/nbinteract">nbinteract</a></b> (🥉20 · ⭐ 220 · 💀) - Create interactive webpages from Jupyter Notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/nteract/bookstore">bookstore</a></b> (🥉20 · ⭐ 190 · 💀) - Notebook storage and publishing workflows for the masses. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/elehcimd/pynb">pynb</a></b> (🥉15 · ⭐ 240 · 💀) - Jupyter Notebooks as plain Python code with embedded Markdown text. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/line/jnotebook_reader">jnotebook-reader</a></b> (🥉8 · ⭐ 100) - An awesome viewer to browse and render Jupyter Notebooks.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>da install -c conda-forge bash_kernel
	```
</details>
<details><summary><b><a href="https://github.com/Calysto/octave_kernel">Octave Kernel</a></b> (🥈21 ·  ⭐ 420) - An Octave kernel for IPython. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Calysto/octave_kernel) (👨‍💻 20 · 🔀 62 · 📥 99 · 📋 180 - 16% open · ⏱️ 18.12.2022):

````

git clone https://github.com/calysto/octave_kernel

```

- [PyPi](https://pypi.org/project/octave_kernel) (📥 8.2K / month · 📦 7 · ⏱️ 29.11.2022):
```

pip install octave_kernel

````
- [Conda](https://anaconda.org/conda-forge/octave_kernel) (📥 460K · ⏱️ 29.11.2022):
`
	conda install -c conda-forge octave_kernel
	`
</details>
<details><summary><b><a href="https://github.com/akabe/ocaml-jupyter">OCaml Kernel</a></b> (🥉20 ·  ⭐ 250) - An OCaml kernel for Jupyter (IPython) notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/akabe/ocaml-jupyter) (👨‍💻 22 · 🔀 35 · 📥 82K · 📋 76 - 6% open · ⏱️ 19.02.2023):

    ```
    git clone https://github.com/akabe/ocaml-jupyter
    ```

</details>
<details><summary><b><a href="https://github.com/Calysto/matlab_kernel">Matlab Kernel</a></b> (🥉19 ·  ⭐ 450 · 💤) - Jupyter Kernel for Matlab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Calysto/matlab_kernel) (👨‍💻 18 · 🔀 75 · 📋 130 - 20% open · ⏱️ 09.05.2022):

````

git clone https://github.com/calysto/matlab_kernel

```

- [PyPi](https://pypi.org/project/matlab_kernel) (📥 1.2K / month · 📦 5 · ⏱️ 09.05.2022):
```

pip install matlab_kernel

```
- [Conda](https://anaconda.org/conda-forge/matlab_kernel) (📥 30K · ⏱️ 07.11.2022):
`
	conda install -c conda-forge matlab_kernel
	`
</details>
<details><summary><b><a href="https://github.com/sassoftware/sas_kernel">SAS Kernel</a></b> (🥉19 ·  ⭐ 190) - A Jupyter kernel for SAS. This opens up all the data manipulation.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/sassoftware/sas_kernel) (👨‍💻 11 · 🔀 76 · ⏱️ 13.01.2023):

```

git clone https://github.com/sassoftware/sas_kernel

```

- [PyPi](https://pypi.org/project/sas_kernel) (📥 5.2K / month · 📦 1 · ⏱️ 01.12.2022):
```

pip install sas_kernel

```
- [Conda](https://anaconda.org/anaconda/sas_kernel) (📥 1.9K · ⏱️ 05.03.2022):
`
	conda install -c anaconda sas_kernel
	`
</details>
<details><summary><b><a href="https://github.com/SciRuby/iruby">IRuby</a></b> (🥉18 ·  ⭐ 760) - Official gem repository: Ruby kernel for Jupyter/IPython Notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/SciRuby/iruby) (👨‍💻 46 · 🔀 20 · 📥 15 · 📦 170 · 📋 190 - 23% open · ⏱️ 11.01.2023):

```

git clone https://github.com/SciRuby/iruby

```

- [Docker Hub](https://hub.docker.com/r/rubydata/datascience-notebook) (📥 1.8K · ⭐ 3 · ⏱️ 03.02.2023):
`
	docker pull rubydata/datascience-notebook
	`
</details>
<details><summary><b><a href="https://github.com/fsprojects/IfSharp">F# Kernel</a></b> (🥉17 ·  ⭐ 430 · 💤) - F# for Jupyter Notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/fsprojects/IfSharp) (👨‍💻 28 · 🔀 65 · 📥 5.5K · 📋 140 - 9% open · ⏱️ 17.03.2022):

```

git clone https://github.com/fsprojects/IfSharp

```

- [Docker Hub](https://hub.docker.com/r/fsprojects/ifsharp) (📥 700 · ⏱️ 26.03.2019):
`
	docker pull fsprojects/ifsharp
	`
</details>
<details><summary><b><a href="https://github.com/clojupyter/clojupyter">clojupyter</a></b> (🥉16 ·  ⭐ 770) - a Jupyter kernel for Clojure. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/clojupyter/clojupyter) (👨‍💻 26 · 🔀 82 · 📋 99 - 15% open · ⏱️ 06.11.2022):

```

git clone https://github.com/clojupyter/clojupyter

```

- [Conda](https://anaconda.org/simplect/clojupyter) (📥 3.3K · ⏱️ 02.03.2020):
```

conda install -c simplect clojupyter

```
- [Docker Hub](https://hub.docker.com/r/simplect/clojupyter) (📥 410 · ⏱️ 25.04.2019):
`
	docker pull simplect/clojupyter
	`
</details>
<details><summary><b><a href="https://github.com/Cadair/jupyter_environment_kernels">Kernel Detection</a></b> (🥉16 ·  ⭐ 150) - An Jupyter plugin to enable the automatic detection of conda.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/Cadair/jupyter_environment_kernels) (👨‍💻 8 · 🔀 19 · 📋 30 - 23% open · ⏱️ 23.11.2022):

```

git clone https://github.com/Cadair/jupyter_environment_kernels

```

- [PyPi](https://pypi.org/project/environment_kernels) (📥 4.8K / month · 📦 6 · ⏱️ 12.02.2018):
`
	pip install environment_kernels
	`
</details>
<details><summary><b><a href="https://github.com/jupyter-xeus/xeus-sqlite">xeus-sqlite</a></b> (🥉15 ·  ⭐ 150) - Jupyter kernel for SQLite. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-xeus/xeus-sqlite) (👨‍💻 12 · 🔀 22 · 📋 43 - 30% open · ⏱️ 16.01.2023):

```

git clone https://github.com/jupyter-xeus/xeus-sqlite

```

- [Conda](https://anaconda.org/conda-forge/xeus-sqlite) (📥 23K · ⏱️ 12.12.2022):
`
	conda install -c conda-forge xeus-sqlite
	`
</details>
<details><summary><b><a href="https://github.com/deathbeds/pidgy">pidgy</a></b> (🥉15 ·  ⭐ 39) - Interactive computing in Markdown. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/deathbeds/pidgy) (👨‍💻 3 · 🔀 7 · 📥 1 · 📦 1 · 📋 20 - 40% open · ⏱️ 23.02.2023):

```

git clone https://github.com/deathbeds/pidgy

```

- [PyPi](https://pypi.org/project/pidgy) (📥 36 / month · ⏱️ 09.01.2023):
`
	pip install pidgy
	`
</details>
<details><summary><b><a href="https://github.com/jorgehpo/notebookJS">notebookJS</a></b> (🥉14 ·  ⭐ 220) - notebookJS: seamless JavaScript integration in Python Notebooks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jorgehpo/notebookJS) (👨‍💻 2 · 🔀 43 · 📦 6 · ⏱️ 25.12.2022):

```

git clone https://github.com/jorgehpo/notebookJS

```

- [PyPi](https://pypi.org/project/notebookjs) (📥 180 / month · ⏱️ 17.04.2021):
```

pip install notebookjs

```
- [npm](https://www.npmjs.com/package/notebookjs) (📥 890 / month · 📦 13 · ⏱️ 03.03.2022):
`
	npm install notebookjs
	`
</details>
<details><summary><b><a href="https://github.com/minrk/allthekernels">allthekernels</a></b> (🥉13 ·  ⭐ 71 · 💤) - A multiplexer kernel for Jupyter. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/minrk/allthekernels) (👨‍💻 9 · 🔀 15 · 📦 5 · 📋 11 - 27% open · ⏱️ 22.08.2022):

```

git clone https://github.com/minrk/allthekernels

```

- [PyPi](https://pypi.org/project/allthekernels) (📥 65 / month · ⏱️ 22.08.2022):
```

pip install allthekernels

```
- [Conda](https://anaconda.org/conda-forge/allthekernels) (📥 5.2K · ⏱️ 22.08.2022):
`
	conda install -c conda-forge allthekernels
	`
</details>
<details><summary>Show 14 hidden projects...</summary>

- <b><a href="https://github.com/jupyter-server/enterprise_gateway">Enterprise Gateway</a></b> (🥈23 · ⭐ 550) - A lightweight, multi-tenant, scalable and secure.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/ansible/ansible-jupyter-kernel">Ansible Kernel</a></b> (🥉19 · ⭐ 520 · 💀) - Jupyter Notebook Kernel for running Ansible Tasks and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/vericast/spylon-kernel">Spylon Kernel</a></b> (🥉19 · ⭐ 170 · 💀) - Jupyter kernel for scala and spark. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/SpencerPark/IJava">IJava</a></b> (🥉18 · ⭐ 900 · 💀) - A Jupyter kernel for executing Java code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Anaconda-Platform/nb_conda_kernels">nb_conda_kernels</a></b> (🥉18 · ⭐ 500 · 💀) - Package for managing conda environment-based kernels.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/scijava/scijava-jupyter-kernel">SciJava Kernel</a></b> (🥉17 · ⭐ 170 · 💀) - [RETIRED] Try IJava or BeakerX. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/WolframResearch/WolframLanguageForJupyter">Wolfram Kernel</a></b> (🥉15 · ⭐ 820 · 💀) - Wolfram Language kernel for Jupyter notebooks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/yunabe/lgo">lgo</a></b> (🥉14 · ⭐ 2.3K · 💀) - Interactive Go programming with Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/pprzetacznik/IElixir">IElixir</a></b> (🥉13 · ⭐ 340 · 💀) - Jupyters kernel for Elixir programming language. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/NII-cloud-operation/sshkernel">SSH Kernel</a></b> (🥉13 · ⭐ 56 · 💀) - SSH Kernel for Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/tdaff/remote_ikernel">remote_ikernel</a></b> (🥉11 · ⭐ 13 · 💀) - All your Jupyter kernels, on all your machines, in one place. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code>
- <b><a href="https://github.com/zabirauf/icsharp">ICSharp</a></b> (🥉10 · ⭐ 270 · 💀) - C# kernel for Jupyter. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/bernhard-42/ssh_ipykernel">ssh_ipykernel</a></b> (🥉10 · ⭐ 9 · 💀) - A remote jupyter kernel via ssh. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/nteract/kernel-relay">kernel-relay</a></b> (🥉4 · ⭐ 12 · 💀) - kernel-relay is a GraphQL service for interfacing with.. <code>❗Unlicensed</code>
</details>
<br>tails>
<details><summary><b><a href="https://github.com/mamba-org/gator">gator</a></b> (🥉18 ·  ⭐ 240) - Conda environment and package management extension from within Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mamba-org/gator) (👨‍💻 25 · 🔀 27 · 📥 2 · 📦 4 · 📋 61 - 34% open · ⏱️ 08.01.2023):

```

git clone https://github.com/mamba-org/gator

```

- [PyPi](https://pypi.org/project/mamba-gator) (📥 26 / month · ⏱️ 25.07.2022):
```

pip install mamba-gator

```
- [Conda](https://anaconda.org/conda-forge/mamba_gator) (📥 27K · ⏱️ 26.07.2022):
```

conda install -c conda-forge mamba_gator

```
- [npm](https://www.npmjs.com/package/@mamba-org/gator-lab) (📥 120 / month · 📦 2 · ⏱️ 03.09.2021):
`
	npm install @mamba-org/gator-lab
	`
</details>
<details><summary><b><a href="https://github.com/jupyterlab-contrib/jupyter-archive">jupyter-archive</a></b> (🥉18 ·  ⭐ 61) - A Jupyter/Jupyterlab extension to make, download and extract.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab-contrib/jupyter-archive) (👨‍💻 10 · 🔀 11 · 📥 3.3K · 📦 2 · 📋 36 - 5% open · ⏱️ 03.02.2023):

```

git clone https://github.com/jupyterlab-contrib/jupyter-archive

```

- [PyPi](https://pypi.org/project/jupyter-archive) (📥 5.1K / month · 📦 1 · ⏱️ 09.01.2023):
```

pip install jupyter-archive

```
- [Conda](https://anaconda.org/conda-forge/jupyter-archive) (📥 38K · ⏱️ 08.01.2023):
```

conda install -c conda-forge jupyter-archive

```
- [npm](https://www.npmjs.com/package/@hadim/jupyter-archive) (📥 350 / month · 📦 2 · ⏱️ 08.01.2023):
`
	npm install @hadim/jupyter-archive
	`
</details>
<details><summary><b><a href="https://github.com/krishnan-r/sparkmonitor">Spark Monitor</a></b> (🥉16 ·  ⭐ 170 · 💤) - Monitor Apache Spark from Jupyter Notebook. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/krishnan-r/sparkmonitor) (👨‍💻 3 · 🔀 51 · 📥 2.4K · 📋 37 - 81% open · ⏱️ 16.05.2022):

```

git clone https://github.com/krishnan-r/sparkmonitor

```

- [PyPi](https://pypi.org/project/sparkmonitor) (📥 2.6K / month · ⏱️ 18.01.2022):
```

pip install sparkmonitor

````
- [Docker Hub](https://hub.docker.com/r/krishnanr/sparkmonitor) (📥 940 · ⏱️ 04.10.2019):
`
	docker pull krishnanr/sparkmonitor
	`
</details>
<details><summary><b><a href="https://github.com/drillan/jupyter-black">Jupyter Black</a></b> (🥉8 ·  ⭐ 420 · 💀) - Black formatter for Jupyter Notebook. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/drillan/jupyter-black) (👨‍💻 2 · 🔀 23 · 📋 23 - 43% open · ⏱️ 01.02.2020):

    ```
    git clone https://github.com/drillan/jupyter-black
    ```

</details>
<details><summary>Show 14 hidden projects...</summary>

- <b><a href="https://github.com/man-group/dtale">dtale</a></b> (🥇30 · ⭐ 3.9K) - Visualizer for pandas data structures. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code>
- <b><a href="https://github.com/dunovank/jupyter-themes">Jupyter Themes</a></b> (🥈28 · ⭐ 9.5K · 💀) - Custom Jupyter Notebook Themes. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/oschuett/appmode">Appmode</a></b> (🥈22 · ⭐ 410 · 💀) - A Jupyter extensions that turns notebooks into web applications. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/8080labs/pyforest">pyforest</a></b> (🥉20 · ⭐ 1K · 💀) - pyforest - feel the bliss of automated imports. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/lspvic/jupyter_tensorboard">jupyter-tensorboard</a></b> (🥉19 · ⭐ 460 · 💀) - Start Tensorboard in Jupyter Notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/googlecolab/jupyter_http_over_ws">HTTP-over-WebSocket</a></b> (🥉18 · ⭐ 250 · 💀) - Jupyter support for HTTP-over-ws. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/mozilla/jupyter-spark">Jupyter Spark</a></b> (🥉18 · ⭐ 190 · 💀) - Jupyter Notebook extension for Apache Spark integration. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code>
- <b><a href="https://github.com/codota/jupyter-tabnine">jupyter-tabnine</a></b> (🥉17 · ⭐ 770 · 💀) - Autocompletion with Deep Learning on Jupyter Notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/data-8/nbzip">nbzip</a></b> (🥉17 · ⭐ 80 · 💀) - Zips and downloads all the contents of a jupyter notebook. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/jupyter-incubator/contentmanagement">Content Management</a></b> (🥉16 · ⭐ 76 · 💀) - Jupyter Content Management Extensions. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/Anaconda-Platform/nb_conda">nb_conda</a></b> (🥉15 · ⭐ 130 · 💀) - Conda environment and package access extension from within Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/thoth-station/jupyter-nbrequirements">jupyter-nbrequirements</a></b> (🥉15 · ⭐ 14) - Dependency management and optimization in Jupyter.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/paypal/PPExtensions">PPExtensions</a></b> (🥉13 · ⭐ 48 · 💀) - Set of iPython and Jupyter extensions to improve user.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/willkessler/jupyterterminals">jupyterterminals</a></b> (🥉7 · ⭐ 8) - Jupyter plugin to support inline terminal shells along with.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Jupyter Extensions

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Application plugins that extend the functionality of Jupyter itself._

<details><summary><b><a href="https://github.com/ipython-contrib/jupyter_contrib_nbextensions">Contrib NBextensions</a></b> (🥇31 ·  ⭐ 5K · 📉) - A collection of various notebook extensions for.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/ipython-contrib/jupyter_contrib_nbextensions) (👨‍💻 140 · 🔀 800 · 📋 810 - 43% open · ⏱️ 21.12.2022):

````

git clone https://github.com/ipython-contrib/jupyter_contrib_nbextensions

```

- [PyPi](https://pypi.org/project/jupyter_contrib_nbextensions) (📥 340K / month · 📦 220 · ⏱️ 15.11.2022):
```

pip install jupyter_contrib_nbextensions

```
- [Conda](https://anaconda.org/conda-forge/jupyter_contrib_nbextensions) (📥 1.6M · ⏱️ 03.12.2022):
`
	conda install -c conda-forge jupyter_contrib_nbextensions
	`
</details>
<details><summary><b><a href="https://github.com/jupyter/nbgrader">nbgrader</a></b> (🥇29 ·  ⭐ 1.2K) - A system for assigning and grading notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbgrader) (👨‍💻 98 · 🔀 320 · 📥 100 · 📦 380 · 📋 860 - 27% open · ⏱️ 06.01.2023):

```

git clone https://github.com/jupyter/nbgrader

```

- [PyPi](https://pypi.org/project/nbgrader) (📥 7.2K / month · 📦 17 · ⏱️ 27.09.2022):
```

pip install nbgrader

```
- [Conda](https://anaconda.org/conda-forge/nbgrader) (📥 130K · ⏱️ 28.09.2022):
`
	conda install -c conda-forge nbgrader
	`
</details>
<details><summary><b><a href="https://github.com/jupyter-server/jupyter-resource-usage">Resource Usage</a></b> (🥈27 ·  ⭐ 360) - Jupyter Notebook Extension for monitoring your own Resource.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/jupyter-server/jupyter-resource-usage) (👨‍💻 30 · 🔀 87 · 📥 180 · 📦 310 · 📋 69 - 49% open · ⏱️ 21.02.2023):

```

git clone https://github.com/jupyter-server/jupyter-resource-usage

```

- [PyPi](https://pypi.org/project/jupyter-resource-usage) (📥 25K / month · 📦 5 · ⏱️ 06.01.2023):
```

pip install jupyter-resource-usage

```
- [Conda](https://anaconda.org/conda-forge/nbresuse) (📥 520K · ⏱️ 23.11.2020):
```

conda install -c conda-forge nbresuse

```
- [npm](https://www.npmjs.com/package/@jupyter-server/resource-usage) (📥 730 / month · 📦 2 · ⏱️ 20.02.2023):
`
	npm install @jupyter-server/resource-usage
	`
</details>
<details><summary><b><a href="https://github.com/jupyterhub/jupyter-server-proxy">jupyter-server-proxy</a></b> (🥈26 ·  ⭐ 270) - Jupyter notebook server extension to proxy web services. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/jupyter-server-proxy) (👨‍💻 66 · 🔀 130 · 📦 2 · 📋 180 - 38% open · ⏱️ 04.02.2023):

```

git clone https://github.com/jupyterhub/jupyter-server-proxy

```

- [PyPi](https://pypi.org/project/jupyter-server-proxy) (📥 160K / month · 📦 120 · ⏱️ 08.09.2022):
```

pip install jupyter-server-proxy

```
- [Conda](https://anaconda.org/conda-forge/jupyter-server-proxy) (📥 1.2M · ⏱️ 08.09.2022):
```

conda install -c conda-forge jupyter-server-proxy

```
- [npm](https://www.npmjs.com/package/@jupyterlab/server-proxy) (📥 8.4K / month · 📦 3 · ⏱️ 08.09.2022):
`
	npm install @jupyterlab/server-proxy
	`
</details>
<details><summary><b><a href="https://github.com/jupyterhub/nbgitpuller">nbgitpuller</a></b> (🥈26 ·  ⭐ 170) - Jupyter server extension to sync a git repository one-way to a.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/nbgitpuller) (👨‍💻 25 · 🔀 71 · 📦 600 · 📋 150 - 45% open · ⏱️ 04.01.2023):

```

git clone https://github.com/jupyterhub/nbgitpuller

```

- [PyPi](https://pypi.org/project/nbgitpuller) (📥 11K / month · 📦 18 · ⏱️ 08.11.2022):
```

pip install nbgitpuller

```
- [Conda](https://anaconda.org/conda-forge/nbgitpuller) (📥 55K · ⏱️ 09.11.2022):
`
	conda install -c conda-forge nbgitpuller
	`
</details>
<details><summary><b><a href="https://github.com/Jupyter-contrib/jupyter_nbextensions_configurator">NBextensions Configurator</a></b> (🥈25 ·  ⭐ 920) - A jupyter notebook serverextension providing config.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Jupyter-contrib/jupyter_nbextensions_configurator) (👨‍💻 22 · 🔀 110 · 📋 88 - 63% open · ⏱️ 21.12.2022):

```

git clone https://github.com/jupyter-contrib/jupyter_nbextensions_configurator

```

- [PyPi](https://pypi.org/project/jupyter_nbextensions_configurator) (📥 360K / month · 📦 180 · ⏱️ 29.12.2018):
```

pip install jupyter_nbextensions_configurator

```
- [Conda](https://anaconda.org/conda-forge/jupyter_nbextensions_configurator) (📥 1.3M · ⏱️ 11.12.2022):
`
	conda install -c conda-forge jupyter_nbextensions_configurator
	`
</details>
<details><summary><b><a href="https://github.com/jupyterhub/jupyter-rsession-proxy">Rsession Proxy</a></b> (🥈22 ·  ⭐ 100) - Jupyter extensions for running an RStudio rsession proxy. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/jupyter-rsession-proxy) (👨‍💻 21 · 🔀 83 · 📦 43 · 📋 79 - 40% open · ⏱️ 24.09.2022):

```

git clone https://github.com/jupyterhub/jupyter-rsession-proxy

```

- [PyPi](https://pypi.org/project/jupyter-rsession-proxy) (📥 16K / month · 📦 1 · ⏱️ 07.09.2022):
```

pip install jupyter-rsession-proxy

```
- [Conda](https://anaconda.org/conda-forge/jupyter-rsession-proxy) (📥 16K · ⏱️ 08.09.2022):
`
	conda install -c conda-forge jupyter-rsession-proxy
	`
</details>
<details><summary><b><a href="https://github.com/mamba-org/gator">gator</a></b> (🥉18 ·  ⭐ 240) - Conda environment and package management extension from within Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mamba-org/gator) (👨‍💻 25 · 🔀 27 · 📥 2 · 📦 4 · 📋 61 - 34% open · ⏱️ 08.01.2023):

```

git clone https://github.com/mamba-org/gator

```

- [PyPi](https://pypi.org/project/mamba-gator) (📥 26 / month · ⏱️ 25.07.2022):
```

pip install mamba-gator

```
- [Conda](https://anaconda.org/conda-forge/mamba_gator) (📥 27K · ⏱️ 26.07.2022):
```

conda install -c conda-forge mamba_gator

```
- [npm](https://www.npmjs.com/package/@mamba-org/gator-lab) (📥 120 / month · 📦 2 · ⏱️ 03.09.2021):
`
	npm install @mamba-org/gator-lab
	`
</details>
<details><summary><b><a href="https://github.com/jupyterlab-contrib/jupyter-archive">jupyter-archive</a></b> (🥉18 ·  ⭐ 61) - A Jupyter/Jupyterlab extension to make, download and extract.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab-contrib/jupyter-archive) (👨‍💻 10 · 🔀 11 · 📥 3.3K · 📦 2 · 📋 36 - 5% open · ⏱️ 03.02.2023):

```

git clone https://github.com/jupyterlab-contrib/jupyter-archive

```

- [PyPi](https://pypi.org/project/jupyter-archive) (📥 5.1K / month · 📦 1 · ⏱️ 09.01.2023):
```

pip install jupyter-archive

```
- [Conda](https://anaconda.org/conda-forge/jupyter-archive) (📥 38K · ⏱️ 08.01.2023):
```

conda install -c conda-forge jupyter-archive

```
- [npm](https://www.npmjs.com/package/@hadim/jupyter-archive) (📥 350 / month · 📦 2 · ⏱️ 08.01.2023):
`
	npm install @hadim/jupyter-archive
	`
</details>
<details><summary><b><a href="https://github.com/krishnan-r/sparkmonitor">Spark Monitor</a></b> (🥉16 ·  ⭐ 170 · 💤) - Monitor Apache Spark from Jupyter Notebook. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/krishnan-r/sparkmonitor) (👨‍💻 3 · 🔀 51 · 📥 2.4K · 📋 37 - 81% open · ⏱️ 16.05.2022):

```

git clone https://github.com/krishnan-r/sparkmonitor

```

- [PyPi](https://pypi.org/project/sparkmonitor) (📥 2.6K / month · ⏱️ 18.01.2022):
```

pip install sparkmonitor

````
- [Docker Hub](https://hub.docker.com/r/krishnanr/sparkmonitor) (📥 940 · ⏱️ 04.10.2019):
`
	docker pull krishnanr/sparkmonitor
	`
</details>
<details><summary><b><a href="https://github.com/drillan/jupyter-black">Jupyter Black</a></b> (🥉8 ·  ⭐ 420 · 💀) - Black formatter for Jupyter Notebook. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/drillan/jupyter-black) (👨‍💻 2 · 🔀 23 · 📋 23 - 43% open · ⏱️ 01.02.2020):

    ```
    git clone https://github.com/drillan/jupyter-black
    ```

</details>
<details><summary>Show 14 hidden projects...</summary>

- <b><a href="https://github.com/man-group/dtale">dtale</a></b> (🥇30 · ⭐ 3.9K) - Visualizer for pandas data structures. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code>
- <b><a href="https://github.com/dunovank/jupyter-themes">Jupyter Themes</a></b> (🥈28 · ⭐ 9.5K · 💀) - Custom Jupyter Notebook Themes. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/oschuett/appmode">Appmode</a></b> (🥈22 · ⭐ 410 · 💀) - A Jupyter extensions that turns notebooks into web applications. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/8080labs/pyforest">pyforest</a></b> (🥉20 · ⭐ 1K · 💀) - pyforest - feel the bliss of automated imports. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/lspvic/jupyter_tensorboard">jupyter-tensorboard</a></b> (🥉19 · ⭐ 460 · 💀) - Start Tensorboard in Jupyter Notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/googlecolab/jupyter_http_over_ws">HTTP-over-WebSocket</a></b> (🥉18 · ⭐ 250 · 💀) - Jupyter support for HTTP-over-ws. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/mozilla/jupyter-spark">Jupyter Spark</a></b> (🥉18 · ⭐ 190 · 💀) - Jupyter Notebook extension for Apache Spark integration. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code>
- <b><a href="https://github.com/codota/jupyter-tabnine">jupyter-tabnine</a></b> (🥉17 · ⭐ 770 · 💀) - Autocompletion with Deep Learning on Jupyter Notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/data-8/nbzip">nbzip</a></b> (🥉17 · ⭐ 80 · 💀) - Zips and downloads all the contents of a jupyter notebook. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/jupyter-incubator/contentmanagement">Content Management</a></b> (🥉16 · ⭐ 76 · 💀) - Jupyter Content Management Extensions. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/Anaconda-Platform/nb_conda">nb_conda</a></b> (🥉15 · ⭐ 130 · 💀) - Conda environment and package access extension from within Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/thoth-station/jupyter-nbrequirements">jupyter-nbrequirements</a></b> (🥉15 · ⭐ 14) - Dependency management and optimization in Jupyter.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/paypal/PPExtensions">PPExtensions</a></b> (🥉13 · ⭐ 48 · 💀) - Set of iPython and Jupyter extensions to improve user.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/willkessler/jupyterterminals">jupyterterminals</a></b> (🥉7 · ⭐ 8) - Jupyter plugin to support inline terminal shells along with.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Jupyter Extensions

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Application plugins that extend the functionality of Jupyter itself._

<details><summary><b><a href="https://github.com/ipython-contrib/jupyter_contrib_nbextensions">Contrib NBextensions</a></b> (🥇31 ·  ⭐ 5K · 📉) - A collection of various notebook extensions for.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/ipython-contrib/jupyter_contrib_nbextensions) (👨‍💻 140 · 🔀 800 · 📋 810 - 43% open · ⏱️ 21.12.2022):

````

git clone https://github.com/ipython-contrib/jupyter_contrib_nbextensions

```

- [PyPi](https://pypi.org/project/jupyter_contrib_nbextensions) (📥 340K / month · 📦 220 · ⏱️ 15.11.2022):
```

pip install jupyter_contrib_nbextensions

```
- [Conda](https://anaconda.org/conda-forge/jupyter_contrib_nbextensions) (📥 1.6M · ⏱️ 03.12.2022):
`
	conda install -c conda-forge jupyter_contrib_nbextensions
	`
</details>
<details><summary><b><a href="https://github.com/jupyter/nbgrader">nbgrader</a></b> (🥇29 ·  ⭐ 1.2K) - A system for assigning and grading notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbgrader) (👨‍💻 98 · 🔀 320 · 📥 100 · 📦 380 · 📋 860 - 27% open · ⏱️ 06.01.2023):

```

git clone https://github.com/jupyter/nbgrader

```

- [PyPi](https://pypi.org/project/nbgrader) (📥 7.2K / month · 📦 17 · ⏱️ 27.09.2022):
```

pip install nbgrader

```
- [Conda](https://anaconda.org/conda-forge/nbgrader) (📥 130K · ⏱️ 28.09.2022):
`
	conda install -c conda-forge nbgrader
	`
</details>
<details><summary><b><a href="https://github.com/jupyter-server/jupyter-resource-usage">Resource Usage</a></b> (🥈27 ·  ⭐ 360) - Jupyter Notebook Extension for monitoring your own Resource.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/jupyter-server/jupyter-resource-usage) (👨‍💻 30 · 🔀 87 · 📥 180 · 📦 310 · 📋 69 - 49% open · ⏱️ 21.02.2023):

```

git clone https://github.com/jupyter-server/jupyter-resource-usage

```

- [PyPi](https://pypi.org/project/jupyter-resource-usage) (📥 25K / month · 📦 5 · ⏱️ 06.01.2023):
```

pip install jupyter-resource-usage

```
- [Conda](https://anaconda.org/conda-forge/nbresuse) (📥 520K · ⏱️ 23.11.2020):
```

conda install -c conda-forge nbresuse

```
- [npm](https://www.npmjs.com/package/@jupyter-server/resource-usage) (📥 730 / month · 📦 2 · ⏱️ 20.02.2023):
`
	npm install @jupyter-server/resource-usage
	`
</details>
<details><summary><b><a href="https://github.com/jupyterhub/jupyter-server-proxy">jupyter-server-proxy</a></b> (🥈26 ·  ⭐ 270) - Jupyter notebook server extension to proxy web services. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/jupyter-server-proxy) (👨‍💻 66 · 🔀 130 · 📦 2 · 📋 180 - 38% open · ⏱️ 04.02.2023):

```

git clone https://github.com/jupyterhub/jupyter-server-proxy

```

- [PyPi](https://pypi.org/project/jupyter-server-proxy) (📥 160K / month · 📦 120 · ⏱️ 08.09.2022):
```

pip install jupyter-server-proxy

```
- [Conda](https://anaconda.org/conda-forge/jupyter-server-proxy) (📥 1.2M · ⏱️ 08.09.2022):
```

conda install -c conda-forge jupyter-server-proxy

```
- [npm](https://www.npmjs.com/package/@jupyterlab/server-proxy) (📥 8.4K / month · 📦 3 · ⏱️ 08.09.2022):
`
	npm install @jupyterlab/server-proxy
	`
</details>
<details><summary><b><a href="https://github.com/jupyterhub/nbgitpuller">nbgitpuller</a></b> (🥈26 ·  ⭐ 170) - Jupyter server extension to sync a git repository one-way to a.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/nbgitpuller) (👨‍💻 25 · 🔀 71 · 📦 600 · 📋 150 - 45% open · ⏱️ 04.01.2023):

```

git clone https://github.com/jupyterhub/nbgitpuller

```

- [PyPi](https://pypi.org/project/nbgitpuller) (📥 11K / month · 📦 18 · ⏱️ 08.11.2022):
```

pip install nbgitpuller

```
- [Conda](https://anaconda.org/conda-forge/nbgitpuller) (📥 55K · ⏱️ 09.11.2022):
`
	conda install -c conda-forge nbgitpuller
	`
</details>
<details><summary><b><a href="https://github.com/Jupyter-contrib/jupyter_nbextensions_configurator">NBextensions Configurator</a></b> (🥈25 ·  ⭐ 920) - A jupyter notebook serverextension providing config.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Jupyter-contrib/jupyter_nbextensions_configurator) (👨‍💻 22 · 🔀 110 · 📋 88 - 63% open · ⏱️ 21.12.2022):

```

git clone https://github.com/jupyter-contrib/jupyter_nbextensions_configurator

```

- [PyPi](https://pypi.org/project/jupyter_nbextensions_configurator) (📥 360K / month · 📦 180 · ⏱️ 29.12.2018):
```

pip install jupyter_nbextensions_configurator

```
- [Conda](https://anaconda.org/conda-forge/jupyter_nbextensions_configurator) (📥 1.3M · ⏱️ 11.12.2022):
`
	conda install -c conda-forge jupyter_nbextensions_configurator
	`
</details>
<details><summary><b><a href="https://github.com/jupyterhub/jupyter-rsession-proxy">Rsession Proxy</a></b> (🥈22 ·  ⭐ 100) - Jupyter extensions for running an RStudio rsession proxy. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/jupyter-rsession-proxy) (👨‍💻 21 · 🔀 83 · 📦 43 · 📋 79 - 40% open · ⏱️ 24.09.2022):

```

git clone https://github.com/jupyterhub/jupyter-rsession-proxy

```

- [PyPi](https://pypi.org/project/jupyter-rsession-proxy) (📥 16K / month · 📦 1 · ⏱️ 07.09.2022):
```

pip install jupyter-rsession-proxy

```
- [Conda](https://anaconda.org/conda-forge/jupyter-rsession-proxy) (📥 16K · ⏱️ 08.09.2022):
`
	conda install -c conda-forge jupyter-rsession-proxy
	`
</details>
<details><summary><b><a href="https://github.com/mamba-org/gator">gator</a></b> (🥉18 ·  ⭐ 240) - Conda environment and package management extension from within Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mamba-org/gator) (👨‍💻 25 · 🔀 27 · 📥 2 · 📦 4 · 📋 61 - 34% open · ⏱️ 08.01.2023):

```

git clone https://github.com/mamba-org/gator

```

- [PyPi](https://pypi.org/project/mamba-gator) (📥 26 / month · ⏱️ 25.07.2022):
```

pip install mamba-gator

```
- [Conda](https://anaconda.org/conda-forge/mamba_gator) (📥 27K · ⏱️ 26.07.2022):
```

conda install -c conda-forge mamba_gator

```
- [npm](https://www.npmjs.com/package/@mamba-org/gator-lab) (📥 120 / month · 📦 2 · ⏱️ 03.09.2021):
`
	npm install @mamba-org/gator-lab
	`
</details>
<details><summary><b><a href="https://github.com/jupyterlab-contrib/jupyter-archive">jupyter-archive</a></b> (🥉18 ·  ⭐ 61) - A Jupyter/Jupyterlab extension to make, download and extract.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab-contrib/jupyter-archive) (👨‍💻 10 · 🔀 11 · 📥 3.3K · 📦 2 · 📋 36 - 5% open · ⏱️ 03.02.2023):

```

git clone https://github.com/jupyterlab-contrib/jupyter-archive

```

- [PyPi](https://pypi.org/project/jupyter-archive) (📥 5.1K / month · 📦 1 · ⏱️ 09.01.2023):
```

pip install jupyter-archive

```
- [Conda](https://anaconda.org/conda-forge/jupyter-archive) (📥 38K · ⏱️ 08.01.2023):
```

conda install -c conda-forge jupyter-archive

```
- [npm](https://www.npmjs.com/package/@hadim/jupyter-archive) (📥 350 / month · 📦 2 · ⏱️ 08.01.2023):
`
	npm install @hadim/jupyter-archive
	`
</details>
<details><summary><b><a href="https://github.com/krishnan-r/sparkmonitor">Spark Monitor</a></b> (🥉16 ·  ⭐ 170 · 💤) - Monitor Apache Spark from Jupyter Notebook. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/krishnan-r/sparkmonitor) (👨‍💻 3 · 🔀 51 · 📥 2.4K · 📋 37 - 81% open · ⏱️ 16.05.2022):

```

git clone https://github.com/krishnan-r/sparkmonitor

```

- [PyPi](https://pypi.org/project/sparkmonitor) (📥 2.6K / month · ⏱️ 18.01.2022):
```

pip install sparkmonitor

````
- [Docker Hub](https://hub.docker.com/r/krishnanr/sparkmonitor) (📥 940 · ⏱️ 04.10.2019):
`
	docker pull krishnanr/sparkmonitor
	`
</details>
<details><summary><b><a href="https://github.com/drillan/jupyter-black">Jupyter Black</a></b> (🥉8 ·  ⭐ 420 · 💀) - Black formatter for Jupyter Notebook. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/drillan/jupyter-black) (👨‍💻 2 · 🔀 23 · 📋 23 - 43% open · ⏱️ 01.02.2020):

    ```
    git clone https://github.com/drillan/jupyter-black
    ```

</details>
<details><summary>Show 14 hidden projects...</summary>

- <b><a href="https://github.com/man-group/dtale">dtale</a></b> (🥇30 · ⭐ 3.9K) - Visualizer for pandas data structures. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code>
- <b><a href="https://github.com/dunovank/jupyter-themes">Jupyter Themes</a></b> (🥈28 · ⭐ 9.5K · 💀) - Custom Jupyter Notebook Themes. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/oschuett/appmode">Appmode</a></b> (🥈22 · ⭐ 410 · 💀) - A Jupyter extensions that turns notebooks into web applications. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/8080labs/pyforest">pyforest</a></b> (🥉20 · ⭐ 1K · 💀) - pyforest - feel the bliss of automated imports. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/lspvic/jupyter_tensorboard">jupyter-tensorboard</a></b> (🥉19 · ⭐ 460 · 💀) - Start Tensorboard in Jupyter Notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/googlecolab/jupyter_http_over_ws">HTTP-over-WebSocket</a></b> (🥉18 · ⭐ 250 · 💀) - Jupyter support for HTTP-over-ws. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/mozilla/jupyter-spark">Jupyter Spark</a></b> (🥉18 · ⭐ 190 · 💀) - Jupyter Notebook extension for Apache Spark integration. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code>
- <b><a href="https://github.com/codota/jupyter-tabnine">jupyter-tabnine</a></b> (🥉17 · ⭐ 770 · 💀) - Autocompletion with Deep Learning on Jupyter Notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/data-8/nbzip">nbzip</a></b> (🥉17 · ⭐ 80 · 💀) - Zips and downloads all the contents of a jupyter notebook. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/jupyter-incubator/contentmanagement">Content Management</a></b> (🥉16 · ⭐ 76 · 💀) - Jupyter Content Management Extensions. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/Anaconda-Platform/nb_conda">nb_conda</a></b> (🥉15 · ⭐ 130 · 💀) - Conda environment and package access extension from within Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/thoth-station/jupyter-nbrequirements">jupyter-nbrequirements</a></b> (🥉15 · ⭐ 14) - Dependency management and optimization in Jupyter.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/paypal/PPExtensions">PPExtensions</a></b> (🥉13 · ⭐ 48 · 💀) - Set of iPython and Jupyter extensions to improve user.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/willkessler/jupyterterminals">jupyterterminals</a></b> (🥉7 · ⭐ 8) - Jupyter plugin to support inline terminal shells along with.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>
````
