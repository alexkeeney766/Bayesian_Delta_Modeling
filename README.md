# Introduction

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/alexkeeney766/Bayesian_Delta_Modeling/HEAD) [![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

The goal of this analysis is to find a model that fits the observed cumulative cases of COVID-19 in the US, starting in Mid-July 2021 and ending in late November 2021. Mid-July coincides with the introduction and subsequent domination of the delta variant of COVID-19 and late November is the latest data released by the World Health Organization at the time of writing. The data used for this project is made freely available by the World Health Organization (WHO) [here](https://covid19.who.int/info?openIndex=2). The first section includes exploratory data analysis and formatting. The second section includes several helper functions for plotting data and results. The third section is comprised of the candidate models defined in increasing levels of complexity. The final section is the comparison and conclusion.

This work is heavily inspired by the Thomas Wiecki talk given at PyMCon 2020:

https://www.youtube.com/watch?v=ZxR3mw-Znzc&t=559s
