# Choice of trimming proportion and number of clusters in robust clustering based on trimming

Code to reproduce the figures of paper "Choice of trimming proportion and number of clusters in robust clustering based on trimming"

Note: in order to run the files below you need to have [FSDA toolbox](https://https://www.mathworks.com/matlabcentral/fileexchange/72999-fsda-flexible-statistics-data-analysis-toolbox) installed

**Abstract**

So-called "classification trimmed likelihood curves" have been proposed as a heuristic
tool to determine the number of clusters and trimming proportion in trimmingbased
robust clustering methods. However, these curves needs a careful visual inspection,
and this way of choosing parameters requires subjective decisions. This work is
intended to provide theoretical background for the understanding of these curves and
the elements involved in their derivation. Moreover, a parametric bootstrap approach
is presented in order to automatize the choice of parameter more by providing a reduced
list of "sensible" choices for the parameters. The user can then pick a solution
that fits their aims from that reduced list.

---

In the table below you can find  the original source .mlx file and the corresponding .ipynb file. The .mlx file (after installing FSDA) can be run on your MATLAB desktop or in free MATLAB Online (please see the button Open in MATLAB Online below). In order to simply view the contents of the mlx files click on the corresponding link named ('File Exchange'). In order to run the .ipynb files inside the agnostic environment jupiter notebook follow the instructions in the file
[ipynbRunInstructions.md](https://github.com/UniprJRC/MonitoringBook/blob/main/ipynbRunInstructions.md).



| FileName | View :eyes:| Run ▶️ | Jupiter notebook |
| -------- | ---- | --- | ---- |
|`simulatedData.mlx`: generate Figure 1  | [![File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](XXX) |  [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=UniprJRC/boot-TCLUST&file=simulatedData.mlx) | [simulatedData.ipynb](https://github.com/UniprJRC/boot-TCLUST/blob/main/simulatedData.ipynb) |
 `simulatedDataBoot.mlx`: generate Figure 2 and Table 2 | [![File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](XXX) |  [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=UniprJRC/boot-TCLUST&file=simulatedDataBoot.mlx) | [simulatedDataBoot.ipynb](https://github.com/UniprJRC/boot-TCLUST/blob/main/simulatedDataBoot.ipynb)
|`geyserData.mlx`: generate Figure 6  | [![File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](XXX) |  [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=UniprJRC/boot-TCLUST&file=geyserData.mlx) | [geyserData.ipynb](https://github.com/UniprJRC/boot-TCLUST/blob/main/geyserData.ipynb) |
 `covidData.mlx`: generate Figures 7 and 8 | [![File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](XXX) |  [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=boot-TCLUST/2025tobit&file=covidData.mlx) | [covidData.ipynb](https://github.com/UniprJRC/boot-TCLUST/blob/main/covidData.ipynb) |


---



![GitHub top language](https://img.shields.io/github/languages/top/UniprJRC/boot-TCLUST)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/UniprJRC/boot-TCLUST)
[![View on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/180239-censored-regression-using-extended-box-cox-transformations)


[![GitHub contributors](https://img.shields.io/github/contributors/UniprJRC/boot-TCLUST)](https://github.com/UniprJRC/2025tobit/graphs/contributors)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/UniprJRC/boot-TCLUST/graphs/commit-activity)
![master](https://img.shields.io/github/last-commit/badges/shields/master)
