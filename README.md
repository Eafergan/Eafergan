# Nati Eafergan, PhD

**Data science · Mathematical modeling · Statistical inference**

I’m a quantitative researcher with a PhD from Tel Aviv University. I use Python and MATLAB to turn experimental data into measurements, build mathematical models, and estimate parameters and their uncertainty. My work combines mathematical modeling, statistical analysis, applied machine learning and quantitative image analysis.

These repositories bring together methods I developed through doctoral research, a coauthored publication, and data analysis consultancy.

[LinkedIn](https://www.linkedin.com/in/natanel-eafergan/) · [ORCID](https://orcid.org/0000-0003-1822-1226)

## Selected projects

### [Multi model fitting and cooperativity inference](https://github.com/Eafergan/multi-model-cooperativity-inference)

`#MathematicalModeling` `#ParameterEstimation` `#Bootstrap` `#Vectorization` `#ParallelComputing` `#MATLAB`

A MATLAB framework that fits three binding states jointly to estimate shared parameters in a statistical-mechanics model.

I used vectorized calculations to evaluate parameter combinations and parallel processing for **1,000 bootstrap fits**. Histogram checks guide iterative adjustment of parameter ranges. The analysis estimates binding affinity and cooperativity from the same measurements, with bootstrap distributions describing uncertainty in the fitted parameters.

### [Relational analysis of microscopy measurements](https://github.com/Eafergan/AsoPeroxisome)

`#TabularData` `#Pandas` `#RelationalJoins` `#DataValidation` `#StatisticalTesting` `#Python`

Python analysis developed for a data analysis consultancy with Dr. Einat Zalckvar’s lab at Bar-Ilan University.

I connected cell and object tables using **composite keys and validated many-to-one joins**, then used control measurements to define comparison groups. The workflow combines filtering, group summaries, distribution plots, and nonparametric tests. These SQL-style table operations are implemented in pandas, preserving the relationship between individual objects and their parent cells.

### [Quantitative image analysis and kinetic modeling](https://github.com/Eafergan/Quantitative-analysis-and-modeling-of-the-Notch-transcriptional-response)

`#ImageAnalysis` `#Regression` `#KineticModeling` `#AppliedMachineLearning` `#DataVisualization` `#Python`

Python workflows from my doctoral research, connecting microscopy measurements with statistical and kinetic models.

I developed scripts for image processing, fluorescence calibration, regression, and decay and recovery fitting. Resampling propagates measurement variability through the fits, while diagnostic plots support comparisons across conditions. The analysis quantified subnuclear structures across hundreds of cells from multiple experiments, alongside kinetic modeling of protein lifetimes and recovery dynamics.

### [Exponential decay modeling and parameter uncertainty](https://github.com/Eafergan/EMSA-Kuang-et-al)

`#NonlinearRegression` `#DecayModeling` `#ParameterEstimation` `#ConfidenceIntervals` `#MATLAB`

A related MATLAB analysis that fits repeated time-course measurements with an exponential decay model and a residual plateau.

I normalized experimental repeats, estimated decay rates, and converted parameter confidence bounds into half-life ranges. This provides a kinetic comparison alongside the equilibrium analysis in the joint-fitting repository.

The two MATLAB repositories contain analyses for Figures 1 and 2 of [Kuang et al., *PLOS Genetics* (2021)](https://doi.org/10.1371/journal.pgen.1009039), which I coauthored.

## Tools and methods

- **Python:** NumPy, pandas, SciPy, Matplotlib, statsmodels.
- **MATLAB:** numerical model evaluation, curve fitting, vectorization, and parallel processing.
- **Modeling and statistics:** joint parameter estimation, regression, kinetic models, bootstrap resampling, and uncertainty estimation.
- **Data analysis:** relational joins, filtering and group summaries, image measurements, calibration, normalization, and visualization.
- **Applied machine learning:** supervised image segmentation using random forests (decision-tree ensembles), feature selection, and iterative classifier refinement.