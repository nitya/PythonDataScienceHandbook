# Self-Study Notes For Python Handbook

This folder documents my learnings and insights from exploring the [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/) from Jake VanderPlas that is related to _this_ repository for relevant hands-on exercises.

## Learning Objectives

1. Instrument the repo with Dev Containers and validate examples work
2. Walk through cookbook to get robust coverage of fundamentals
3. Add or edit notebooks in fork (sandbox) to test my understanding

---

## 1 | Dev Container Setup

The current Dev Container setup contains:
 - Docker image with basic Python v3.11
 - Added features for Python (recommended)
 - Added extensions for Python/Jupyter (recommended)
 - Auto-install dependencies from `requirements.txt`

To test setup, open a Jupyter notebook and verify that it runs successfully in the environment, else make changes to devcontainer or requirements to validate usage -- _and note the changes in this section_.

Here are some changes made:
1. Added GitHub Copilot extension
1. 

---

## 2 | Validating Notebooks

The first step is to make sure we can run all the current notebooks in the dev container configuration setup here (e.g., all dependencies are met). For now, we'll validate only the exercises in the  `notebooks/` folder (latest version) and add a ✅ in the `Validated` column if executed right.

| # | Notebook | Description | Validated |
|:---|:---|:---|:---|
| 00 | [00.00-Preface.ipynb](./../notebooks/00.00-Preface.ipynb)| No Code | ✅ |
| 00 | [01.00-IPython-Beyond-Normal-Python.ipynb](./../notebooks/01.00-IPython-Beyond-Normal-Python.ipynb)|No Code | ✅ |
| 01 | [01.01-Help-And-Documentation.ipynb](./../notebooks/01.01-Help-And-Documentation.ipynb) | No Code | ✅ |
| 02 | [01.02-Shell-Keyboard-Shortcuts.ipynb](./../notebooks/01.02-Shell-Keyboard-Shortcuts.ipynb) | No Code | ✅ |
| 03 | [01.03-Magic-Commands.ipynb](./../notebooks/01.03-Magic-Commands.ipynb) |No Code | ✅ |
| 04 | [01.04-Input-Output-History.ipynb](./../notebooks/01.04-Input-Output-History.ipynb) |No Code | ✅ |
| 05 | [01.05-IPython-And-Shell-Commands.ipynb](./../notebooks/01.05-IPython-And-Shell-Commands.ipynb) | No Code | ✅ |
| 06 | [01.06-Errors-and-Debugging.ipynb](./../notebooks/01.06-Errors-and-Debugging.ipynb) | | |
| 07 | [01.07-Timing-and-Profiling.ipynb](./../notebooks/01.07-Timing-and-Profiling.ipynb) | | |
| 08 | [01.08-More-IPython-Resources.ipynb](./../notebooks/01.08-More-IPython-Resources.ipynb) | | |
| 09 | [02.00-Introduction-to-NumPy.ipynb](./../notebooks/02.00-Introduction-to-NumPy.ipynb) | | |
| 10 | [02.01-Understanding-Data-Types.ipynb](./../notebooks/02.01-Understanding-Data-Types.ipynb) | | |
| 11 | [02.02-The-Basics-Of-NumPy-Arrays.ipynb](./../notebooks/02.02-The-Basics-Of-NumPy-Arrays.ipynb) | | |
| 12 | [02.03-Computation-on-arrays-ufuncs.ipynb](./../notebooks/02.03-Computation-on-arrays-ufuncs.ipynb) | | |
| 13 | [02.04-Computation-on-arrays-aggregates.ipynb](./../notebooks/02.04-Computation-on-arrays-aggregates.ipynb) | | |
| 14 | [02.05-Computation-on-arrays-broadcasting.ipynb](./../notebooks/02.05-Computation-on-arrays-broadcasting.ipynb) | | |
| 15 | [02.06-Boolean-Arrays-and-Masks.ipynb](./../notebooks/02.06-Boolean-Arrays-and-Masks.ipynb) | | |
| 16 | [02.07-Fancy-Indexing.ipynb](./../notebooks/02.07-Fancy-Indexing.ipynb) | | |
| 17 | [02.08-Sorting.ipynb](./../notebooks/02.08-Sorting.ipynb) | | |
| 18 | [02.09-Structured-Data-NumPy.ipynb](./../notebooks/02.09-Structured-Data-NumPy.ipynb) | | |
| 19 | [03.00-Introduction-to-Pandas.ipynb](./../notebooks/03.00-Introduction-to-Pandas.ipynb) | | |
| 20 | [03.01-Introducing-Pandas-Objects.ipynb](./../notebooks/03.01-Introducing-Pandas-Objects.ipynb) | | |
| 21 | [03.02-Data-Indexing-and-Selection.ipynb](./../notebooks/03.02-Data-Indexing-and-Selection.ipynb) | | |
| 22 | [03.03-Operations-in-Pandas.ipynb](./../notebooks/03.03-Operations-in-Pandas.ipynb) | | |
| 23 | [03.04-Missing-Values.ipynb](./../notebooks/03.04-Missing-Values.ipynb) | | |
| 24 | [03.05-Hierarchical-Indexing.ipynb](./../notebooks/03.05-Hierarchical-Indexing.ipynb) | | |
| 25 | [03.06-Concat-And-Append.ipynb](./../notebooks/03.06-Concat-And-Append.ipynb) | | |
| 26 | [03.07-Merge-and-Join.ipynb](./../notebooks/03.07-Merge-and-Join.ipynb) | | |
| 27 | [03.08-Aggregation-and-Grouping.ipynb](./../notebooks/03.08-Aggregation-and-Grouping.ipynb) | | |
| 28 | [03.09-Pivot-Tables.ipynb](./../notebooks/03.09-Pivot-Tables.ipynb) | | |
| 29 | [03.10-Working-With-Strings.ipynb](./../notebooks/03.10-Working-With-Strings.ipynb) | | |
| 30 | [03.11-Working-with-Time-Series.ipynb](./../notebooks/03.11-Working-with-Time-Series.ipynb) | | |
| 31 | [03.12-Performance-Eval-and-Query.ipynb](./../notebooks/03.12-Performance-Eval-and-Query.ipynb) | | |
| 32 | [03.13-Further-Resources.ipynb](./../notebooks/03.13-Further-Resources.ipynb) | | |
| 33 | [04.00-Introduction-To-Matplotlib.ipynb](./../notebooks/04.00-Introduction-To-Matplotlib.ipynb) | | |
| 34 | [04.01-Simple-Line-Plots.ipynb](./../notebooks/04.01-Simple-Line-Plots.ipynb) | | |
| 35 | [04.02-Simple-Scatter-Plots.ipynb](./../notebooks/04.02-Simple-Scatter-Plots.ipynb) | | |
| 36 | [04.03-Errorbars.ipynb](./../notebooks/04.03-Errorbars.ipynb) | | |
| 37 | [04.04-Density-and-Contour-Plots.ipynb](./../notebooks/04.04-Density-and-Contour-Plots.ipynb) | | |
| 38 | [04.05-Histograms-and-Binnings.ipynb](./../notebooks/04.05-Histograms-and-Binnings.ipynb) | | |
| 39 | [04.06-Customizing-Legends.ipynb](./../notebooks/04.06-Customizing-Legends.ipynb) | | |
| 40 | [04.07-Customizing-Colorbars.ipynb](./../notebooks/04.07-Customizing-Colorbars.ipynb) | | |
| 41 | [04.08-Multiple-Subplots.ipynb](./../notebooks/04.08-Multiple-Subplots.ipynb) | | |
| 42 | [04.09-Text-and-Annotation.ipynb](./../notebooks/04.09-Text-and-Annotation.ipynb) | | |
| 43 | [04.10-Customizing-Ticks.ipynb](./../notebooks/04.10-Customizing-Ticks.ipynb) | | |
| 44 | [04.11-Settings-and-Stylesheets.ipynb](./../notebooks/04.11-Settings-and-Stylesheets.ipynb) | | |
| 45 | [04.12-Three-Dimensional-Plotting.ipynb](./../notebooks/04.12-Three-Dimensional-Plotting.ipynb) | | |
| 46 | [04.14-Visualization-With-Seaborn.ipynb](./../notebooks/04.14-Visualization-With-Seaborn.ipynb) | | |
| 47 | [04.15-Further-Resources.ipynb](./../notebooks/04.15-Further-Resources.ipynb) | | |
| 48 | [05.00-Machine-Learning.ipynb](./../notebooks/05.00-Machine-Learning.ipynb) | | |
| 49 | [05.01-What-Is-Machine-Learning.ipynb](./../notebooks/05.01-What-Is-Machine-Learning.ipynb) | | |
| 50 | [05.02-Introducing-Scikit-Learn.ipynb](./../notebooks/05.02-Introducing-Scikit-Learn.ipynb) | | |
| 51 | [05.03-Hyperparameters-and-Model-Validation.ipynb](./../notebooks/05.03-Hyperparameters-and-Model-Validation.ipynb) | | |
| 52 | [05.04-Feature-Engineering.ipynb](./../notebooks/05.04-Feature-Engineering.ipynb) | | |
| 53 | [05.05-Naive-Bayes.ipynb](./../notebooks/05.05-Naive-Bayes.ipynb) | | |
| 54 | [05.06-Linear-Regression.ipynb](./../notebooks/05.06-Linear-Regression.ipynb) | | |
| 55 | [05.07-Support-Vector-Machines.ipynb](./../notebooks/05.07-Support-Vector-Machines.ipynb) | | |
| 56 | [05.08-Random-Forests.ipynb](./../notebooks/05.08-Random-Forests.ipynb) | | |
| 57 | [05.09-Principal-Component-Analysis.ipynb](./../notebooks/05.09-Principal-Component-Analysis.ipynb) | | |
| 58 | [05.10-Manifold-Learning.ipynb](./../notebooks/05.10-Manifold-Learning.ipynb) | | |
| 59 | [05.11-K-Means.ipynb](./../notebooks/05.11-K-Means.ipynb) | | |
| 60 | [05.12-Gaussian-Mixtures.ipynb](./../notebooks/05.12-Gaussian-Mixtures.ipynb) | | |
| 61 | [05.13-Kernel-Density-Estimation.ipynb](./../notebooks/05.13-Kernel-Density-Estimation.ipynb) | | |
| 62 | [05.14-Image-Features.ipynb](./../notebooks/05.14-Image-Features.ipynb) | | |
| 63 | [05.15-Learning-More.ipynb](./../notebooks/05.15-Learning-More.ipynb) | | |
| 64 | [06.00-Figure-Code.ipynb](./../notebooks/06.00-Figure-Code.ipynb) | | |
| | | | |


---

## 3 | Study Notes

This section captures any insights or notes taken when walking through a specific chapter or notebook. In particular, will document any GitHub Copilot prompts that helped me with explainers, bug fixes or code generation ideas relating to the core concept taught.